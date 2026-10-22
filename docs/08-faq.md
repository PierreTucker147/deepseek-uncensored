# DeepSeek Abliterated and Uncensored FAQ

## What is the DeepSeek abliterated API ID?

RouterHub lists `deepseek-uncensored`. Check its current availability and rates
in [models.json](https://routerhub.si/models.json), then use Chat Completions.

## Which uncensored DeepSeek variants are listed?

The catalogue includes `deepseek-uncensored` and `deepseek-uncensored`.
The implementation matters: an uncensored label is not proof of separately
fine-tuned weights or of preserved customer system instructions.

## How does DeepSeek abliterated differ from uncensored?

Abliteration describes a family of weight-level interventions. Uncensored
can refer to a wider range of training, weight, or prompt changes. See the
[comparison guide](./02-abliterated-vs-uncensored.md).

## Are DeepSeek jailbreak prompts the same as abliterated weights?

No. A prompt changes a request's instructions or context; a weight-level
intervention changes the model. The [prompt directory](./prompt-directory.md)
is a separate research resource from the hosted API entries.

## Will a no-refusal model always answer correctly?

Neither refusal-free output nor correctness is guaranteed. Measure task
completion, factual quality, and unnecessary refusals independently.

## Can I use the OpenAI SDK?

Yes: configure the RouterHub base URL and key, then call Chat Completions with
the exact DeepSeek model ID. See the [SDK examples](./api-quickstart.md).

## Can I use DeepSeek directly in Claude Code or Codex?

The DeepSeek entries documented here list Chat Completions. Claude Code requires
Messages and Codex requires Responses. Choose an appropriate model from the
same RouterHub account, or use a Chat-compatible client when you need DeepSeek.

## Does RouterHub support Cursor and OpenCode workflows?

RouterHub publishes an OpenCode setup guide. Cursor users should check custom
endpoint support for their version and intended feature. Review the
[client matrix](./04-deepseek-claude-code-cursor-opencode-codex.md) before configuring either.

## How do pricing and payment work?

API usage is prepaid, with published input, output, and eligible cached-input
rates per million tokens. RouterHub advertises card and crypto top-ups; check
the checkout screen for current payment options. See [DeepSeek pricing](https://routerhub.si/models).

## Are these local models or guaranteed private endpoints?

These examples use hosted inference. Review data-handling and retention terms
before transmitting private information. A research label does not establish
zero retention.

## Where should I start if a request fails?

Check the key, exact model ID, account balance, endpoint, and request fields.
Keep a redacted request ID and timestamp for support. The
[troubleshooting guide](./10-troubleshooting.md) organizes those checks.

[Additional API FAQ](./faq.md) · [Documentation index](./README.md) · [Overview](../README.md)
