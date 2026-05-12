# Week 8 – Bots & Generators

## The Artifact
**Title:** Paper Title Generator (local Claude session)

This artifact is an HTML export of a local Claude agent session that generated paper-title ideas and related metadata using a local-agent mode run. The original agent output was saved as `paper-title-generator.html` and is available in the `makes/` folder.

Open the generator here: [Paper Title Generator](week08-paper-title-generator.html)

Use the page to browse and test the titles produced during the session. The output is interactive HTML produced by the local agent and includes multiple title suggestions and contextual notes.

## Process Notes
Process notes
- Source: local Claude `local-agent-mode` session output (HTML export)
- How I added it: copied the agent's HTML output into `makes/week08-paper-title-generator.html` and linked it from this week page.
- Tools: local Claude agent, file export, Markdown editing in this repo.
- Decisions: I preserved the original HTML output as-is to maintain provenance and to let you view the agent's exact suggestions. If you'd like, I can extract the top titles into this page as a summary.

## Reflection
Reflection

Working with a local agent session felt different from cloud-based generation because the output is self-contained and reproducible from the session folder. The paper-title generator is useful as an example of how generative systems can act as creative assistants: they rapidly produce idea-space, surface patterns, and offer starting points for iteration. The artifact also highlights questions about authorship and provenance — who owns a title idea produced by an agent running locally with prompts from a human? For classroom use, it can spark discussion about how to evaluate and curate machine-generated suggestions.

## Attribution & AI Use
Attribution & AI Use

Tools used: local Claude agent (local-agent-mode), Markdown editor

AI prompts (summary): prompts asked the agent to produce concise, publishable paper titles across a range of tones and disciplinary angles

What AI generated: a list of candidate paper titles, short descriptors, and optional subtitles — exported as an HTML file

What you changed or decided: moved the original HTML export into `makes/`, linked it from this page, and wrote the reflection and process notes above. I did not modify the agent's exported content.
