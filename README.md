# Scientific Figure Prompts & Examples for Researchers

**Reusable AI prompt patterns for graphical abstracts, biological pathways, experimental schematics, and research diagrams.**

[**Create a figure with SciDraw**](https://scidraw.org/) · [Scientific Figure Generator](https://scidraw.org/tools/scientific-figure-generator) · [Graphical Abstract Generator](https://scidraw.org/tools/graphical-abstract-generator)

> **About this repository:** An official prompt and examples guide for [SciDraw.org](https://scidraw.org/), a hosted AI scientific figure generator. This repository provides educational prompts and review checklists; it does **not** include the SciDraw application's source code or a locally runnable model.

## What is SciDraw?

SciDraw helps researchers, graduate students, educators, and science communicators turn text descriptions, rough sketches, references, and research notes into **scientific figure drafts**. Supported use cases include graphical abstracts, biological pathway diagrams, experimental setup schematics, mechanism diagrams, and research system diagrams.

The workflow is simple: describe the science, generate a visual, **review the scientific content**, refine the prompt, and export a figure suitable for subsequent review or editing. The website advertises high-resolution output and SVG export on eligible plans; do not assume every element of an exported image will be independently editable without testing the file.

## Research use cases

| Figure type | When it helps | Example guide |
| --- | --- | --- |
| Graphical abstract | Summarize a study question, method, and outcome | [Carbon capture cycle](examples/graphical-abstract.md) |
| Biological pathway | Show known components and directed interactions | [Cell signaling pathway](examples/biological-pathway.md) |
| Experimental setup schematic | Communicate equipment, flow, and measurement points | [Microfluidic setup](examples/experimental-setup.md) |

SciDraw can also be used to draft AI architecture diagrams, materials-science figures, and teaching illustrations.

## Get started

1. Go to [SciDraw.org](https://scidraw.org/).
2. Choose a figure workflow, such as a graphical abstract or scientific schematic.
3. Provide your verified scientific concepts, source notes, labels, and intended audience.
4. Specify a layout (left-to-right process, multi-panel, pathway, or apparatus diagram).
5. Generate a draft, then check every arrow, label, mechanism, and claim against your own sources.
6. Revise as needed, download in an available format, and complete final editing and journal checks separately.

## Example prompt: graphical abstract

```text
Create a 16:9 graphical abstract illustrating a generic cyclic solid-sorbent
carbon capture process. Divide the composition into four stages:
(1) CO2-containing gas enters the capture unit,
(2) the sorbent selectively captures CO2,
(3) the sorbent is regenerated using an energy input, and
(4) a concentrated CO2 stream is collected for storage or utilization.
Use short English labels, clear left-to-right arrows, and a consistent
scientific illustration style. Do not add performance statistics,
chemical reactions, or materials that are not provided in the source.
```

**Review checklist:** Are the process stages in the intended order? Does the regeneration arrow return to the sorbent? Are all material and energy streams identified? Have unsupported efficiencies or scientific claims appeared?

## Better prompts for scientific figures

- **State the evidence boundary:** what is established, hypothetical, or illustrative?
- **Supply exact terminology:** spell out labels and abbreviations.
- **Specify relationships:** name the direction of arrows and distinguish activation from inhibition.
- **Define the audience:** journal readers, lab colleagues, students, or the public.
- **Provide source material:** check output against the cited paper, method, or data—not just against the prompt.

## Accuracy and publication considerations

AI-generated figures are **visual drafts, not evidence**. Check mechanisms, axes, labels, experimental conditions, and study claims before using them in manuscripts, posters, or teaching material. Figures created from imagined data should not be presented as measured results. Follow your journal's disclosure, image-integrity, resolution, and copyright policies.

SciDraw is not a replacement for statistical plotting packages when you need reproducible graphs built directly from numerical datasets.

## Example library

- [Graphical abstract prompt and QA](examples/graphical-abstract.md)
- [Biological pathway prompt and QA](examples/biological-pathway.md)
- [Experimental setup prompt and QA](examples/experimental-setup.md)

## Repository scope and feedback

This repository shares examples for the **hosted SciDraw product**, not open-source source code. Example prompts are illustrative; final figures depend on the provided scientific information and human review. Suggestions for new educational prompts are welcome via GitHub issues. Please do not submit restricted research data or unpublished confidential content.

**Official website:** https://scidraw.org/
