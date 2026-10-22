# PowerPoint Designer for Microsoft Copilot

This project provides a skill, operating guidance, and visual design reference for a Microsoft Copilot agent that creates and reviews PowerPoint presentations. It is intended to help Copilot turn briefs and source material into focused, persuasive decks for executive, business, project, technical, and operational audiences.

The goal is decision-ready storytelling, not documents pasted onto slides: clear narrative, concise message-led titles, evidence-backed content, and visual explanations.

## What's Included

| File | Purpose |
|---|---|
| [`SKILL.md`](SKILL.md) | Task-specific PowerPoint design skill for the Copilot agent, including its workflow and quality checks. |
| [`references/template.md`](references/template.md) | Supporting design-system knowledge referenced by the skill; keep it available at that relative path. |
| [`instructions.md`](instructions.md) | Agent-wide behavior and operating instructions for planning, drafting, reviewing, and delivering presentations. |
| [`suggested-prompts.md`](suggested-prompts.md) | Example requests to adapt for common presentation tasks. |
| [`enterprise-powerpoint-designer-skill.zip`](enterprise-powerpoint-designer-skill.zip) | Packaged skill archive. |

## Include These in the Agent Build

The skill and instructions are complementary build components, not alternatives:

1. Add `instructions.md` to the Copilot agent's general instructions so its behavior and presentation standards apply across requests.
2. Include or register `SKILL.md` as the PowerPoint design skill so the agent can use its task-specific workflow when creating or reviewing decks.
3. Package `references/template.md` with the skill and preserve the relative path expected by `SKILL.md`.
4. Use `suggested-prompts.md` as optional examples for testing or demonstrating the configured agent; it is not a replacement for its instructions or skill.

This repository contains the agent's build inputs and supporting guidance, rather than a standalone presentation application.

## Using the Skill

Use the skill when asking the Copilot agent to create a deck, turn source material into slides, review an existing presentation, or recommend visuals. Start with a prompt from [`suggested-prompts.md`](suggested-prompts.md), or describe the task in your own words and provide the relevant source files.

Include these details when they matter:

- Audience and presentation objective
- Desired decision, action, or outcome
- Delivery context, such as a live meeting, workshop, or pre-read
- Requested slide count and deadline
- Brand requirements, including an existing PowerPoint template, logo, fonts, colors, and confidentiality marking
- Source material, datasets, and required citations

If important details are missing, the agent should clarify when they materially affect the result or proceed with explicit assumptions. It must not invent facts, metrics, dates, owners, or conclusions.

## Presentation Defaults

- Use a 16:9 widescreen canvas unless another format is requested.
- Give each slide one primary message and use a conclusion-led title.
- Prefer diagrams, charts, timelines, and other visual structures over dense copy and default bullet lists.
- Follow the reference design system: dark graphite, white and gray text, signal green as the primary accent, and other colors used consistently for semantic distinctions.
- Build analytical slides around a dominant, editable vector composition when practical. Use containers only when they represent a meaningful boundary or component.
- Keep text concise, legible at presentation distance, and accessible. Clearly distinguish sourced facts, assumptions, and placeholders.

These defaults are subordinate to an explicitly supplied brand kit, approved template, or visual direction.

## Expected Deliverables

When PowerPoint file creation is available and requested, deliver a `.pptx`. Otherwise, provide a slide-by-slide draft with a message-led title, slide purpose, concise on-slide content, recommended visual, optional speaker notes, and source references or clearly marked placeholders.

Before delivery, review the narrative, factual accuracy, readability, visual consistency, accessibility, and slide order. Make the requested decision or next action clear.