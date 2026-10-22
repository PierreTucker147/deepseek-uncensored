# DeepSeek API Quickstart

Connect to the DeepSeek Uncensored API through RouterHub's
Chat Completions endpoint. Executing inference requests consumes prepaid credits.

## Account and API key

1. [Register with RouterHub](https://routerhub.si/register?next=onboarding&utm_source=github&utm_medium=docs&utm_campaign=deepseek-uncensored).
2. Add credits through your account's billing page.
3. Create a private API key and enter it directly into your local environment.

Use `ROUTERHUB_API_KEY` for the secret. The API base is `https://routerhub.si/v1`.
Do not send your key to another person, embed it in browser code, or commit it
to a repository. Keys are shown once when created; store yours securely.

## Choose an exact model ID

| API ID | Selection |
|---|---|
| `deepseek-uncensored` | Abliterated research entry |
| `deepseek-uncensored` | Uncensored entry |
| `deepseek-uncensored` | Uncensored Flash entry |
| `deepseek` | Standard baseline |
| `deepseek-flash` | Standard Flash entry |

The [public catalogue](https://routerhub.si/models.json) listed all five as
Chat Completions entries with preview availability on October 24, 2026.
Availability and supported capabilities must be checked again before use.

## Send a short request

From a shell where `ROUTERHUB_API_KEY` is already configured:

```bash
curl https://routerhub.si/v1/chat/completions \
  -H "Authorization: Bearer $ROUTERHUB_API_KEY" \
  -H "Content-Type: application/json" \
  --data '{"model":"deepseek-uncensored","messages":[{"role":"user","content":"Reply with OK."}]}'
```

For SDK code, use the [Python, JavaScript, and streaming examples](./api-quickstart.md).
A dependency-free Python option is available in [examples/chat.py](../examples/chat.py).
Its `--help` option does not make a network request.

## Pricing and limits

RouterHub publishes input, output, and eligible cached-input prices in USD per
million tokens. Consult the [DeepSeek pricing page](https://routerhub.si/models?utm_source=github&utm_medium=docs&utm_campaign=deepseek-uncensored)
for current rates. An omitted cache rate is not a promise of a cache discount.

A basic estimate is input tokens multiplied by the input rate plus output tokens
multiplied by the output rate, with each token count divided by one million.
Reported cached usage and provider-specific charges can affect the final amount.
Inspect recorded usage after your initial short request.

Context and output limits belong to each model entry. Do not copy a limit from
one DeepSeek variant to another when the catalogue does not publish it.

## Select a compatible client

The DeepSeek entries here use Chat Completions, not Messages or Responses. Match
that protocol in your application before troubleshooting authentication.

[Client setup](./04-deepseek-claude-code-cursor-opencode-codex.md) · [Troubleshooting](./10-troubleshooting.md) · [Overview](../README.md)
