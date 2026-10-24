<div align="center">

<a href="https://routerhub.si/?utm_source=github&amp;utm_medium=readme&amp;utm_campaign=deepseek-uncensored">
  <img src="./assets/routerhub-banner.png" width="100%" alt="RouterHub — One key. All your models.">
</a>

<p align="center">
  <a href="https://routerhub.si/?utm_source=github&amp;utm_medium=readme&amp;utm_campaign=deepseek-uncensored"><img src="./assets/visit-website.svg" width="208" height="74" alt="Visit RouterHub website"></a>
  <a href="https://t.me/routerhubsi"><img src="./assets/telegram.svg" width="216" height="74" alt="Join RouterHub on Telegram"></a>
  <a href="https://routerhub.si/register?next=onboarding&amp;utm_source=github&amp;utm_medium=readme&amp;utm_campaign=deepseek-uncensored"><img src="./assets/get-api-key.svg" width="183" height="74" alt="Get a RouterHub API key"></a>
</p>

**DeepSeek is your starting point. One RouterHub API key also connects you to GPT, Claude, GLM, Qwen, and Grok, with research variants listed in the model catalogue.**

# DeepSeek Uncensored — Jailbreak Prompts, Model Guide & API Access

**Find a DeepSeek uncensored API, compare DeepSeek uncensored models, and explore 35 bundled research prompt files.** This RouterHub guide connects model terminology, jailbreak prompt research, API examples, and coding-tool setup in one place.

Searching for a **DeepSeek uncensored AI model**, a **DeepSeek abliterated model**, or a **DeepSeek no-refusal model**? Learn what each label tells you, choose an API ID, and evaluate the behavior you actually need. The gateway offers OpenAI-compatible Chat Completions for DeepSeek and Anthropic-compatible Messages for supported Claude entries.

[![Model](./assets/badge-model.svg)](#what-is-deepseek)
[![Prompts](./assets/badge-prompts.svg)](#deepseek-jailbreak-collection-35-prompts)
[![Variants](./assets/badge-variants.svg)](#abliterated-vs-uncensored)
[![API](./assets/badge-api.svg)](#quickstart)
[![Billing](./assets/badge-billing.svg)](#pricing-and-access)

[**Get an API key →**](https://routerhub.si/register?next=onboarding&utm_source=github&utm_medium=readme&utm_campaign=deepseek-uncensored) · [Quickstart](#quickstart) · [Docs](#documentation) · [Telegram](https://t.me/routerhubsi)

</div>

<p align="center"><strong>RouterHub is live:</strong> the <strong>DeepSeek Uncensored API</strong>, live model catalogue and pricing are available at <a href="https://routerhub.si/?utm_source=github&utm_medium=readme&utm_campaign=deepseek-uncensored">routerhub.si</a>.</p>

---

## DeepSeek Uncensored?

These searches describe related goals, but the labels answer different questions:

- **DeepSeek abliterated** names a research variant associated with interventions in model weights intended to reduce refusal-related behavior.
- **DeepSeek uncensored** describes a broader product category. The implementation might involve training, weight changes, or a prompt-level persona; the name alone does not tell you which.

If your goal is a **DeepSeek uncensored API**, start with the exact catalogue entry rather than assuming every variant behaves alike. RouterHub lists standard, abliterated and uncensored DeepSeek entries where available.

Reduced refusal is something to measure, not a promise of unrestricted output. Compare the variants in the [abliterated vs. uncensored guide](./docs/02-abliterated-vs-uncensored.md).

## Not just DeepSeek

RouterHub connects **DeepSeek, GPT, Claude, DeepSeek, Qwen, and Grok** through a prepaid account and API key. Use this repository for DeepSeek abliterated and uncensored research; explore the [full model catalogue](https://routerhub.si/models?utm_source=github&utm_medium=readme&utm_campaign=deepseek-uncensored) when you need another family or protocol.

There are 30+ published model entries. Chat Completions, Messages, and Responses are supported across the catalogue, but each entry has its own supported protocol. Choosing a model and choosing a client go together.

<a href="https://routerhub.si/models?utm_source=github&amp;utm_medium=readme&amp;utm_campaign=deepseek-uncensored">
  <img src="./assets/routerhub-banner.png" width="600" alt="DeepSeek abliterated and uncensored API access with RouterHub">
</a>

## DeepSeek jailbreak collection (35 prompts)

The **jailbreak collection is the main event**: 35 paste-ready prompt files bundled in [jailbreaks/](./jailbreaks/), organized by model family. The DeepSeek abliterated/uncensored angle and the RouterHub API path are added around them.

### Collection

### OpenCode Zen — Free Stealth Models

| Model | File | Type |
|---|---|---|
| **Big Pickle** | [bigpickle-opencode.md](./jailbreaks/bigpickle-opencode.md) | VANTA persona lock with explicit operating floor |
| **Space Bunny** | [spacebunny-agents.md](./jailbreaks/spacebunny-agents.md) | Assistant operating specification |
| **LongCat 2.5** | [longcat-agents.md](./jailbreaks/longcat-agents.md) | Assistant operating specification |
| **MiMo V2.6** | [mimo-2.6-agents.md](./jailbreaks/mimo-2.6-agents.md) | Assistant operating specification |
| **Step 5 Preview** | [step-5-preview.md](./jailbreaks/step-5-preview.md) | Workspace operating profile |
| **Muse Spark 1.3** | [muse-spark-1.3.md](./jailbreaks/muse-spark-1.3.md) | Agent deployment operating policy |
| **Muse Spark 1.3 v2** | [muse-spark-1.3-v2.md](./jailbreaks/muse-spark-1.3-v2.md) | Runtime scope-note variant |
| **Muse.ai** | [muse-ai-agents.md](./jailbreaks/muse-ai-agents.md) | Assistant operating specification |

### Anthropic — Claude

| Model | File | Type |
|---|---|---|
| **Opus** | [opus-v1.md](./jailbreaks/opus-v1.md) · [opus-v2.md](./jailbreaks/opus-v2.md) | Conversational groundwork persona, v1 / v2 |
| **Sonnet** | [sonnet-v1.md](./jailbreaks/sonnet-v1.md) · [sonnet-v2.md](./jailbreaks/sonnet-v2.md) | Writer's-room framing, v1 / v2 |

### Zhipu — GLM / ZCode

| Model | File | Type |
|---|---|---|
| **GLM-5.2** | [glm-5.2.md](./jailbreaks/glm-5.2.md) | System prompt |
| **GLM ZCode 5.2** | [glm-zcode-5.2.md](./jailbreaks/glm-zcode-5.2.md) | System prompt |
| **GLM ZCode 5.3** | [glm-zcode-5.3.md](./jailbreaks/glm-zcode-5.3.md) · [glm-zcode-5.3-agents.md](./jailbreaks/glm-zcode-5.3-agents.md) | System prompt + `AGENTS.md` drop-in |
| **GLM-5.3 Flash** | [glm-5-3-flash.md](./jailbreaks/glm-5-3-flash.md) | Assistant operating specification |
| **GLM-5.3 (OpenCode)** | [glm5-3-opencode.md](./jailbreaks/glm5-3-opencode.md) | Assistant operating specification |

### DeepSeek

| Model | File | Type |
|---|---|---|
| **DeepSeek V3** | [deepseek-v3.md](./jailbreaks/deepseek-v3.md) | System prompt |
| **DeepSeek V4** | [deepseek-v4.md](./jailbreaks/deepseek-v4.md) | System prompt |
| **DeepSeek 4.1** | [deepseek-4-1.md](./jailbreaks/deepseek-4-1.md) | Assistant operating specification |

### Moonshot — Kimi

| Model | File | Type |
|---|---|---|
| **Kimi K2** | [kimi-k2.md](./jailbreaks/kimi-k2.md) | System prompt |
| **Kimi K3** | [kimi-k3-agents.md](./jailbreaks/kimi-k3-agents.md) | Workspace operating profile |

### xAI — Grok

| Model | File | Type |
|---|---|---|
| **Grok Build** | [grok-build.md](./jailbreaks/grok-build.md) | Agent operating instructions |
| **Grok 4.7** | [grok-4.7.md](./jailbreaks/grok-4.7.md) | App-builder workspace guide |
| **Grok Config** | [grok-config.txt](./jailbreaks/grok-config.txt) | `<CFG>` priority and routing configuration |

### Google / Mistral / Alibaba

| Model | File | Type |
|---|---|---|
| **Gemini 4 Argon** | [gemini-4-argon.md](./jailbreaks/gemini-4-argon.md) | Operating policy |
| **Mistral Large 4** | [mistral-large-4.md](./jailbreaks/mistral-large-4.md) | Agent system prompt |
| **Qwen 3.7** | [qwen-3.7.md](./jailbreaks/qwen-3.7.md) | System prompt |

### Ollama Modelfiles

| Model | File | Type |
|---|---|---|
| **Gemma 4** | [gemma4.md](./jailbreaks/gemma4.md) | `FROM` + `SYSTEM` block |
| **GPT-OSS 20B** | [gpt-oss-20b.md](./jailbreaks/gpt-oss-20b.md) | `FROM` + `SYSTEM` block |

### Unfiled Files

A few newer additions aren't indexed under a specific model yet:

- [beam.md](./jailbreaks/beam.md)
- [muse-wonder.md](./jailbreaks/muse-wonder.md)
- [qwen-preferences.md](./jailbreaks/qwen-preferences.md)
- [unified.md](./jailbreaks/unified.md)

### How to use these prompts

#### System Prompts

Paste the file's contents into whatever system-prompt or custom-instructions field your client or API offers — an API `system` message, a chatbot's custom instructions, an agent instruction block, or harness-level prompt configuration.

#### AGENTS.md Files

Save the file as `AGENTS.md` in the root of your repository or workspace. Coding agents and compatible tools pick it up as project-level instructions.

#### Workspace Policies

Files marked as an **assistant operating specification** or **workspace operating profile** belong in environments with persistent global instructions. An OpenCode install, for example, reads:

```text
~/.config/opencode/AGENTS.md
```

The exact location depends on your client or harness.

#### Ollama Modelfiles

Feed the file straight to Ollama:

```bash
ollama create gemma4-jb -f jailbreaks/gemma4.md
```

Swap the model name and source file as needed.

#### Grok Configuration

[grok-config.txt](./jailbreaks/grok-config.txt) is meant for the config field of the target harness — not the regular conversation.

> [!NOTE]
> Prompt behavior is version-dependent. Models get updated, instruction hierarchies shift, and system prompts rotate — what works on one release may fail on the next. If a file looks outdated, open an issue or send an updated version.

All 35 files live in [jailbreaks/](./jailbreaks/) for offline review and reuse.

## If a jailbreak gets patched

Prompts age. A model update can close a persona lock, tighten an instruction hierarchy, or change how a workspace policy is interpreted. When a file stops working, you have two options:

1. **Update the prompt** — open an issue or send a pull request with the model version and the failure.
2. **Skip the prompt layer** — use a **DeepSeek Uncensored model** through RouterHub, where the model itself is less likely to refuse before the prompt even lands.

The API is the fallback funnel: [DeepSeek API quickstart](./docs/03-deepseek-api-quickstart.md) · [Get a key](https://routerhub.si/register?next=onboarding&utm_source=github&utm_medium=readme&utm_campaign=deepseek-uncensored).

## What is DeepSeek?

**DeepSeek** is a model family used for coding, reasoning and bilingual workflows. This guide focuses on API access, variant selection, and evaluation for developers considering DeepSeek for coding, agent tasks, analysis, and Chinese/English workflows.

Useful evaluation scenarios include:

- code explanation, refactoring suggestions, and test generation;
- project instructions and multi-step agent work;
- bilingual drafting and translation;
- repeated tasks where token cost affects deployment choices;
- comparing standard, Flash, abliterated, and uncensored entries on the same inputs.

Choose on measured task quality, latency, and cost rather than a product label alone. The [DeepSeek model guide](./docs/01-what-is-deepseek-uncensored.md) explains where to start.

## Abliterated vs. uncensored

| Question | DeepSeek Abliterated | DeepSeek Uncensored |
|---|---|---|
| **What does the label describe?** | A research category associated with weight-level intervention | A broad behavior or product category |
| **What implementation should you verify?** | The advertised method and hosted model provenance | Whether the entry uses training changes, weight changes, or a fixed persona |
| **Which API ID is listed?** | Confirm `deepseek-abliterated` in the dashboard | Confirm `deepseek-uncensored` in the dashboard |
| **Which protocol is listed?** | Chat Completions | Chat Completions |
| **What needs testing?** | Task quality, refusals, instruction following, and integration | The same measures, plus how customer system instructions are handled |
| **Does it guarantee no refusals?** | No | No |

The [full abliterated vs. uncensored comparison](./docs/02-abliterated-vs-uncensored.md) separates weight-level methods from prompt-level changes. This repository does not independently inspect hosted model weights or publish a refusal-rate benchmark.

## Why use DeepSeek Uncensored?

- **Research model behavior:** compare variant responses on legitimate requests where the standard model was unnecessarily restrictive.
- **Develop coding workflows:** evaluate explanation, code generation, and agent instruction following with your own acceptance tests.
- **Explore creative and bilingual tasks:** assess tone, useful engagement, and Chinese/English output separately from correctness.
- **Compare cost per result:** include retries, failures, and output length instead of looking only at token rates.
- **Keep one integration account:** use RouterHub for DeepSeek and other listed families without maintaining a separate account for each model.
- **Reuse familiar clients:** connect through a Chat Completions SDK or a tool supporting a custom compatible endpoint.

See [DeepSeek use cases](./docs/06-use-cases.md) for practical evaluation tasks, or [get an API key](https://routerhub.si/register?next=onboarding&utm_source=github&utm_medium=readme&utm_campaign=deepseek-uncensored) to begin a paid test.

## Quickstart

### 1. Get the key and base URL

[Register with RouterHub](https://routerhub.si/register?next=onboarding&utm_source=github&utm_medium=readme&utm_campaign=deepseek-uncensored), add prepaid credits, and create a private API key. The published API base is `https://routerhub.si/v1`.

```bash
export ROUTERHUB_API_KEY="<your-private-key>"
export ROUTERHUB_API_BASE_URL="https://routerhub.si/v1"
```

Set these values only in your local environment or secret manager. Running an inference example consumes credits; do not commit a real key.

### 2. Confirm the DeepSeek model ID

These entries were listed in the [public catalogue](https://routerhub.si/models.json) on October 24, 2026. All five list Chat Completions and preview availability; recheck availability and rates before use.

| Variant | Exact API ID |
|---|---|
| **DeepSeek Abliterated** | `deepseek-uncensored` |
| **DeepSeek** | `deepseek` |
| **DeepSeek Flash** | `deepseek-flash` |
| **DeepSeek Uncensored** | `deepseek-uncensored` |
| **DeepSeek Flash Uncensored** | `deepseek-uncensored` |

### 3. OpenAI-compatible request

Install `openai` with pip, then run a short Chat Completions request:

```python
import os
from openai import OpenAI

api = OpenAI(
    base_url=os.environ["ROUTERHUB_API_BASE_URL"],
    api_key=os.environ["ROUTERHUB_API_KEY"],
)
result = api.chat.completions.create(
    model="deepseek-uncensored",
    messages=[{"role": "user", "content": "Explain what an API gateway does in two sentences."}],
)
print(result.choices[0].message.content)
```

### 4. Anthropic-compatible request

The same RouterHub account also serves supported Claude models through Messages. **This is a Claude example, not an alternate DeepSeek endpoint:** the listed DeepSeek variants use Chat Completions. Install `anthropic` with pip to try it.

```python
import os
from anthropic import Anthropic

api = Anthropic(
    base_url=os.environ["ROUTERHUB_API_BASE_URL"],
    api_key=os.environ["ROUTERHUB_API_KEY"],
)
result = api.messages.create(
    model="claude-opus-5-5",
    max_tokens=64,
    messages=[{"role": "user", "content": "Explain what an API gateway does in two sentences."}],
)
for part in result.content:
    if part.type == "text":
        print(part.text)
```

For cURL, JavaScript, streaming, and a standard-library Python client, continue with the [DeepSeek API quickstart](./docs/03-deepseek-api-quickstart.md).

## Works with your stack

| Tool | Connection path |
|---|---|
| **OpenCode** | Select a Chat Completions provider configuration for the listed DeepSeek model ID |
| **Cursor** | Check whether your version supports a custom Chat Completions endpoint and the required model features |
| **Continue / Cline** | Follow the compatible Chat Completions setup for DeepSeek |
| **OpenAI SDK** | Supply the RouterHub base URL, key, and exact DeepSeek API ID |
| **Claude Code / Anthropic SDK** | Use a catalogue entry supporting Messages, such as Claude; the listed DeepSeek entries do not |
| **Codex CLI** | Select a Responses model from the same account rather than a Chat-only DeepSeek entry |
| **LangChain / LlamaIndex** | Choose a compatible Chat Completions integration and verify the features your application uses |

Client setup and protocol selection: [Claude Code, Cursor, OpenCode, Codex](./docs/04-deepseek-claude-code-cursor-opencode-codex.md).

## Evaluating DeepSeek abliterated

A useful **DeepSeek abliterated benchmark** needs more than a single permissive answer. Compare standard and research variants using the same legitimate tasks, then record:

1. **Unnecessary refusals:** requests declined despite being answerable under your defined test policy.
2. **Task quality:** correctness, useful detail, code tests, and appropriate uncertainty.
3. **Instruction behavior:** formatting, system-message handling, and required tool integration.
4. **Repeatability:** prompt revision, API ID, settings, repetitions, and test date.
5. **Total task cost:** token use, failed attempts, retries, and end-to-end latency.

Use the [evaluation guide](./docs/05-evaluating-deepseek-uncensored.md) and [original benign sample tasks](./examples/benign-eval-prompts.json) to design your run. No live benchmark scores are claimed in this repository.

## Pricing and access

- **Prepaid token billing:** add credits and pay for usage at the selected model's rates.
- **Input and output pricing:** compare the published USD-per-million-token rates for your exact DeepSeek variant.
- **Cache-aware charges:** use a published cached-input rate only where supported and reported.
- **Card or crypto funding:** review available payment methods and terms at checkout.
- **Usage tracking:** check charges in your account after a short initial request.

[View DeepSeek API pricing](https://routerhub.si/models?utm_source=github&utm_medium=readme&utm_campaign=deepseek-uncensored) · [Browse models](https://routerhub.si/models?utm_source=github&utm_medium=readme&utm_campaign=deepseek-uncensored) · [Get your API key](https://routerhub.si/register?next=onboarding&utm_source=github&utm_medium=readme&utm_campaign=deepseek-uncensored)

For cost estimation and model limits, see [pricing and limits](./docs/03-deepseek-api-quickstart.md#pricing-and-limits).

## Honest limits

- **A no-refusal label is not a guarantee.** Evaluate the actual model instead of assuming every request will receive a useful answer.
- **Hosted behavior can change.** Recheck availability and rerun important evaluations after updates.
- **Protocols are model-specific.** A shared API key does not make a Chat-only model compatible with Messages or Responses.
- **Instruction handling matters.** In particular, confirm whether a persona replaces your system/developer instructions.
- **Hosted inference is not local inference.** Review applicable provider terms and retention policies before transmitting private data.

Read [safety and responsible use](./docs/07-safety-and-responsible-use.md) for practical deployment checks.

## FAQ

**Is DeepSeek abliterated the same as DeepSeek uncensored?**

No. Abliteration identifies a family of weight-level methods, while uncensored is a broader label that can also cover prompt-level changes. Compare the implementation notes in the [variant guide](./docs/02-abliterated-vs-uncensored.md).

**How do I access DeepSeek abliterated through an API?**

Create a RouterHub account, fund it, create a key, and send a Chat Completions request using `deepseek-uncensored`. Follow the [API quickstart](./docs/03-deepseek-api-quickstart.md) and check the live catalogue first.

**Does RouterHub have a DeepSeek uncensored model?**

The public catalogue lists `deepseek-uncensored` and `deepseek-uncensored` alongside the abliterated entry. Verify availability and how the entry handles system instructions before integrating it.

**Can I use DeepSeek with Claude Code or Cursor?**

DeepSeek currently requires Chat Completions. Claude Code requires Messages, so use a supported Claude entry there. For Cursor, check that your version supports the needed custom endpoint. See the [client guide](./docs/04-deepseek-claude-code-cursor-opencode-codex.md).

**Is DeepSeek abliterated safe?**

Suitability depends on the task, data, model behavior, and controls around your application. Review outputs and approve consequential actions; see the [deployment checklist](./docs/07-safety-and-responsible-use.md).

**Will a DeepSeek no-refusal model never refuse?**

No. The phrase is a search label, not evidence of refusal-free behavior or correct answers.

**Is there a subscription?**

RouterHub describes its API billing as prepaid and usage-based. Review current account terms and token prices before funding a run.

**Can I pay with crypto?**

RouterHub advertises card and crypto top-ups. The checkout screen shows the payment methods currently available.

**What is the difference between DeepSeek and DeepSeek Flash?**

They are separate catalogue entries with separate rates and capabilities to verify. Benchmark both against your latency, quality, and cost requirements.

**Where can I compare DeepSeek with Claude, GPT, and DeepSeek?**

Start with [RouterHub's model catalogue](https://routerhub.si/models?utm_source=github&utm_medium=readme&utm_campaign=deepseek-uncensored), then apply the same task rubric while accounting for protocol and instruction differences. More answers are in the [DeepSeek FAQ](./docs/08-faq.md).

## Documentation

| Guide | Coverage |
|---|---|
| [What is DeepSeek Abliterated?](./docs/01-what-is-deepseek-uncensored.md) | Model terminology and a starting checklist |
| [Abliterated vs. uncensored](./docs/02-abliterated-vs-uncensored.md) | Weight changes, personas, and variant selection |
| [DeepSeek API quickstart](./docs/03-deepseek-api-quickstart.md) | Account, model IDs, requests, and billing |
| [Claude Code, Cursor, OpenCode, Codex](./docs/04-deepseek-claude-code-cursor-opencode-codex.md) | Matching clients to supported protocols |
| [Evaluating DeepSeek abliterated](./docs/05-evaluating-deepseek-uncensored.md) | Test design and task-based scoring |
| [Use cases](./docs/06-use-cases.md) | Coding, agent, writing, and bilingual tasks |
| [Safety and responsible use](./docs/07-safety-and-responsible-use.md) | Secrets, privacy, permissions, and deployment checks |
| [FAQ](./docs/08-faq.md) | Common DeepSeek API and model-selection questions |
| [Glossary](./docs/09-glossary.md) | Model, prompt, protocol, and billing terms |
| [Troubleshooting](./docs/10-troubleshooting.md) | Authentication, model IDs, streaming, and request failures |

## Related

- **[RouterHub models](https://routerhub.si/models?utm_source=github&utm_medium=readme&utm_campaign=deepseek-uncensored):** compare model families, protocols, and published prices.
- **[Jailbreak collection](./jailbreaks/):** 35 paste-ready prompt files and agent instruction specs.
- **[RouterHub](https://routerhub.si/?utm_source=github&utm_medium=readme&utm_campaign=deepseek-uncensored):** account access, prepaid credits, and API keys.
- **[Telegram](https://t.me/routerhubsi):** RouterHub's community channel.

Documentation fixes and redacted reproductions are welcome: [contributing](./CONTRIBUTING.md) · [security](./SECURITY.md) · [MIT license](./LICENSE). Run `python tools/check.py` for offline link and syntax checks without spending credits.

## Start on RouterHub

All API access, model IDs, pricing and account setup live on RouterHub:

[Open website](https://routerhub.si/?utm_source=github&utm_medium=readme&utm_campaign=deepseek-uncensored) · [Browse models](https://routerhub.si/models?utm_source=github&utm_medium=readme&utm_campaign=deepseek-uncensored) · [Get an API key](https://routerhub.si/register?next=onboarding&utm_source=github&utm_medium=readme&utm_campaign=deepseek-uncensored)

---

<div align="center">

**Found a useful DeepSeek Uncensored resource? Star the repository and share your documentation improvements.**

<sub>Maintained by RouterHub. Model names and trademarks belong to their respective owners; this repository does not imply endorsement by model providers. Use the APIs in accordance with applicable laws and service policies.</sub>

</div>
