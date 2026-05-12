# Week 6 – Mapping AI Worlds

## The Artifact
**Title:** AI Infrastructure Map (local Claude session)

This artifact is an HTML export produced by a local Claude `local-agent-mode` session that maps AI infrastructure: data centers, cloud providers, model training pipelines, dependency chains, and the institutions that shape those networks. The interactive map helps visualize technical and political relationships that are otherwise hard to see in prose.

Open the interactive map here: [AI Infrastructure Map](week06-ai-infrastructure-map.html)

The visualization foregrounds nodes such as data centers, model training clusters, labeling contractors, major cloud providers, and regulatory actors. Edges show dependencies like data flows, hosting relationships, funding ties, and policy influence.

## Process Notes
Process notes
- Source: local Claude agent HTML export (interactive map)
- How I added it: copied the agent's HTML output into `makes/week06-ai-infrastructure-map.html` and linked it from this page
- Tools: local Claude `local-agent-mode`, file export, Markdown editing in this repo
- Decisions: I preserved the original HTML export to maintain provenance and interactive features. The map intentionally emphasizes both technical and political infrastructure so viewers can interrogate where power, labor, and resources concentrate.

## Reflection
Reflection

Mapping AI infrastructure made the scope of the technology feel less abstract and more materially grounded. When you place elements like data-labeling vendors, hyperscale data centers, and funding sources on a single network diagram, patterns start to appear: concentration of control in a few cloud providers, outsourcing of labor to specific regions, and institutional chokepoints that shape what kinds of models get built.

The map also highlighted the political decisions embedded in technical architecture. Choices about where to host training workloads, which datasets to prioritize, and which partners to onboard are not neutral; they distribute costs and benefits unevenly. Visualizing those relationships surfaced questions about accountability, environmental impact, and the often-invisible human labor that underpins large models.

Finally, the interactive format was useful because it encourages exploration. Rather than reading a static argument, viewers can follow edges, click on nodes, and see how one actor connects to many others. That exploratory approach fits well with digital humanities methods: asking questions, testing hypotheses, and letting the data suggest where to look next.

Overall, the project made the world of AI feel more like a set of linked systems than an abstract technology. That shift in perspective is important for any conversation about governance, ethics, or design.

## Attribution & AI Use
Attribution & AI Use

Tools used: local Claude agent (local-agent-mode), Markdown editor

AI prompts (summary): prompts asked the agent to identify infrastructure actors, map dependency relationships, and format an interactive HTML export for exploration

What AI generated: an interactive HTML map that lists nodes (actors), edges (relationships), and short contextual notes for many entities in the AI ecosystem

What you changed or decided: copied the original HTML export into the `makes/` folder for reproducibility and linked it from this page; summarized the map and wrote the reflection. I did not alter the agent's exported HTML content.
