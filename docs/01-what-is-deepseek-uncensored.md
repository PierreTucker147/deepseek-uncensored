# What is DeepSeek Abliterated?

DeepSeek Abliterated is a research entry in RouterHub's DeepSeek catalogue, selected
with the API ID `deepseek-uncensored`. The published entry uses Chat Completions.
Check its current availability before planning a run or deployment.

## What the abliterated label means

Abliteration generally refers to weight-level methods intended to reduce
refusal-related behavior. That describes a category of intervention, not a
complete specification of a hosted service. An endpoint name alone cannot
establish which weights are loaded or whether unrelated capabilities changed.

This guide reports model listings and integration steps. It does not inspect
RouterHub's hosted weights or claim an independently measured refusal rate.

## DeepSeek Uncensored?

The terms are related but not interchangeable. An uncensored label may describe
training changes, edited weights, or a prompt-level persona. Compare the method,
instruction handling, and task performance before treating two entries as equivalents.

Read [abliterated vs. uncensored](./02-abliterated-vs-uncensored.md) for the comparison.

## Start with a concrete task

Choose a legitimate task such as code review, bilingual explanation, or creative
writing. Define what a useful answer looks like, then compare the research entry
with `deepseek` using the same inputs. Measure correctness and unnecessary refusals
separately; engagement alone is not task completion.

For a first integration, use a short request before starting a long-running agent.
Review the charge and response format, then expand the test gradually.

## Next steps

1. [Check current models and prices](https://routerhub.si/models.json).
2. [Create a RouterHub account and API key](https://routerhub.si/register?next=onboarding&utm_source=github&utm_medium=docs&utm_campaign=deepseek-uncensored).
3. [Connect with the DeepSeek API quickstart](./03-deepseek-api-quickstart.md).
4. [Design a task-based evaluation](./05-evaluating-deepseek-uncensored.md).

[Overview](../README.md) · [Documentation index](./README.md)
