# Universal Assistant Prompt

[Русский](README.md) · [English prompt](PROMPT.en.md) · [Russian original](PROMPT.md) · [Short Russian prompt](PROMPT_SHORT.md) · [Examples](EXAMPLES.md)

**Understand the task. Do the work. Verify the result. State the limits.**

A reusable text prompt for AI assistants, covering task clarification, instruction following, skill use, careful project editing and honest reporting. It is intended for chat assistants that accept user instructions, without depending on one provider.

This is a prompt, not an application or plugin. No comparative benchmarks or verified compatibility matrix are available. It does not claim to make a model smarter or outperform other prompts.

## Start in three steps

1. Copy [PROMPT.en.md](PROMPT.en.md), an English translation of the Russian original.
2. Paste it at the start of a chat, or attach it if your assistant can read attachments and ask it to follow the instructions.
3. Add your actual task, mandatory constraints and completion criteria.

Example task after the prompt:

> Review the attached project description for a first-time user. Produce a maximum of 200 words covering its purpose, three setup steps and limitations. Use only facts in the source. Flag any missing information instead of inventing it.

The [examples](EXAMPLES.md) are suggested inputs and evaluation criteria, not recorded model results.

## What it asks the assistant to do

- Identify the intended deliverable and preserve requirements across corrections.
- Ask about consequential ambiguity while using stated assumptions for minor gaps.
- Check premises and explain conflicts instead of blindly agreeing.
- Choose a proportionate approach and deliver work rather than promises.
- Read relevant skills and resources before applying them.
- Respect permission boundaries for external or hard-to-reverse actions.
- Make focused project changes and run available checks.
- Separate verified facts, assumptions, incomplete work and limitations.

## Files and direct access

| File | Purpose |
| --- | --- |
| [PROMPT.md](PROMPT.md) | Canonical full Russian prompt |
| [PROMPT.en.md](PROMPT.en.md) | English translation; behavioral equivalence has not been tested |
| [PROMPT_SHORT.md](PROMPT_SHORT.md) | Condensed Russian instructions; not a proven equivalent |
| [EXAMPLES.md](EXAMPLES.md) | Task examples and observable success criteria |
| [llms.txt](llms.txt) | A small navigation index for tools able to read it |

[Raw English prompt](https://raw.githubusercontent.com/mirdobrr-hash/universal-assistant-prompt/main/PROMPT.en.md) · [Raw Russian prompt](https://raw.githubusercontent.com/mirdobrr-hash/universal-assistant-prompt/main/PROMPT.md)

## Limits

The prompt cannot grant browsing, filesystem access, code execution, persistent memory or additional permissions. Links are useful only if the assistant can retrieve their contents. Skills are supplied task methods, not executable extensions installed by this prompt.

Models may ignore instructions, lose context or produce incorrect answers. Textual permission and untrusted-content rules are not enforced security boundaries. Human review and independent tests remain necessary for consequential results.

An llms.txt file is a navigation aid, not a guarantee of discovery, indexing, training inclusion or recommendation by an AI service. “Universal” means provider-independent wording, not proven support for every model.

## Evaluation and contributions

No model experiments are reported here. To contribute evidence, compare the same tasks with and without the prompt, record the model, date, settings, tools, exact input and a commit identifier, and retain failures as well as successes. Define scoring criteria before running the comparison. Documentation checks do not establish prompt effectiveness.

Suggestions via issues or pull requests should identify the problem, proposed wording, rationale and an anonymized reproducible example. Do not include credentials or personal data. Label untested ideas clearly.

## License status

No license has been selected. Public visibility is not an open-source license. Ask the repository owner about redistribution or derivative use until terms are explicitly provided.
