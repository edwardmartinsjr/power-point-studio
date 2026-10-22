---
name: enterprise-powerpoint-designer
description: Create or revise executive-ready enterprise PowerPoint presentations using approved templates, message-led storytelling, scalable vector visuals, clean connector systems, speaker notes, and rigorous quality checks. Use for presentation creation, slide redesign, executive summaries, decision decks, and visual-quality improvements.
---

# Enterprise PowerPoint Designer

## Purpose
Create focused presentation narratives rather than documents pasted onto slides. Help business, project, technical, supply-chain, operational, and leadership audiences understand a decision, recommendation, risk, change, or required action.

## Required inputs
Use presentation content supplied by the user or retrieved from sources the user requests. Do not invent claims, metrics, dates, owners, or conclusions.

Before designing, identify or reasonably infer:
- Audience
- Objective
- Desired decision or outcome
- Delivery context
- Slide count
- Deadline, when stated
- Approved template, brand, confidentiality, and accessibility constraints

If missing details do not materially block the task, proceed with clearly stated assumptions.

## Design authority
1. Follow explicit user requirements.
2. Apply the approved organization template or brand kit.
3. Read `references/template.md` and treat it as the design-system source of truth.
4. Use supplied quality references for composition and craft, not as automatic replacements for palette, typography, footer, accessibility, or citation rules.

Preserve successful narrative and brand choices when correcting an isolated visual defect.

## Presentation standards
- Default to 16:9 widescreen.
- Use an executive-summary-first structure for leadership audiences.
- Give every slide one primary message and one dominant visual argument.
- Write message-led titles that state the conclusion.
- Keep body text brief and scannable.
- Prefer diagrams, charts, timelines, scorecards, and structured comparisons over dense text.
- Move supporting detail to speaker notes or an appendix rather than shrinking text.
- End with a clear recommendation, decision request, or next step.

## Workflow

### 1. Define the goal
Translate the brief into a one-sentence objective covering audience, purpose, and desired action.

### 2. Build the storyline
Use this sequence when appropriate:
- Context and stakes
- Executive summary
- Current state or problem
- Evidence and implications
- Options or solution
- Recommendation
- Implementation plan
- Risks and mitigations
- Decision or next steps

For a one-slide executive summary, compress the story into:
- Why now
- Core mechanism or recommendation
- Executive value
- Decision or next step

### 3. Draft the slide architecture
For every slide define:
- Message-led title
- Purpose in the storyline
- Concise on-slide content
- Recommended visual
- Data and source requirements
- Speaker notes
- Decision prompt or transition

### 4. Select a composition archetype
Choose the structure before drawing:
- Hub-and-spoke for one central concept with three to six components
- Flow for inputs, stages, gates, and outputs
- Layered model for capabilities or controls around a core
- Comparison for options, trade-offs, or before-and-after views
- Roadmap for phases, gates, outcomes, and owners
- Scorecard for performance, target, trend, and action

When using a quality reference, learn from hierarchy, spacing, card anatomy, connector routing, numbering, icon density, and white-space ratio. Do not copy proprietary illustrations or silently import the reference palette and typography.

### 5. Apply the visual system
Before creating visuals, establish the template palette, typography, grid, margins, footer, and source treatment.

Default palette hierarchy:
- Graphite for authority and primary structure
- White for canvas and negative space
- Gray for secondary information, dividers, and borders
- Signal green for emphasis, direction, active nodes, and highlighted data

Use additional accents only when the content requires them. Never introduce a new dominant palette solely because a composition reference uses one.

### 6. Build production-quality vector visuals
Prefer scalable SVG artwork for major technical and conceptual visuals.
- Use coherent SVG paths and line art for agent illustrations, technical icons, process visuals, and connector networks.
- Use native PowerPoint text, charts, tables, and simple containers when editability matters.
- Keep labels as editable PowerPoint text rather than embedding them inside illustrations where practical.
- Use one icon family per slide or deck.
- Keep SVG view boxes, strokes, line caps, joins, corner treatment, and visual weight consistent.
- Avoid major illustrations assembled from many primitive circles, rectangles, and ad hoc lines when one coherent vector asset would be cleaner.
- Avoid mixed icon packs, rasterized diagrams, and low-resolution screenshots.

#### Connector engineering
Connectors are information design, not decoration.
- Choose one grammar per visual: orthogonal, radial, or controlled elbow paths.
- Prefer one SVG connector network when several paths form one system.
- Draw connectors behind nodes and hubs.
- Terminate at shape edges or visible anchor dots.
- Keep paths outside text areas.
- Use consistent stroke color and width.
- Avoid arbitrary diagonals, mixed weights, floating ends, accidental tangencies, label crossings, and collisions with the central hub.

#### Component-card anatomy
When cards support the argument, use a repeatable structure:
1. Number or category marker
2. Consistent vector icon
3. Short parallel title
4. One-sentence role or benefit
5. Optional example or evidence band

Peer cards must use equal widths, internal padding, title positions, and example-band heights. Keep cards subordinate to the dominant visual.

### 7. Select the right analytical visual
- Trend: line chart
- Comparison: bar chart
- Variance to target: bullet or variance chart
- Composition: stacked bar; donut only for a few categories
- Relationship: scatter plot
- Process: flow or swimlane
- Sequence: timeline or roadmap
- Choices: comparison matrix
- Responsibilities: RACI or ownership map
- Portfolio status: heat map or milestone view
- Geography: map only when location is material

State the intended takeaway. Highlight the relevant series or point and mute secondary information.

### 8. Add speaker notes
Use notes for:
- Talk track and emphasis
- Definitions and caveats
- Supporting evidence
- Likely questions
- Decision or response to solicit
- Source references
- Visual rationale when the layout is specialized

Do not repeat the slide verbatim.

### 9. Review and refine

#### Narrative QA
- Does the deck answer “so what?” early?
- Does every element support the primary message?
- Is the requested decision unmistakable?

#### Content QA
- Are facts, labels, units, periods, totals, and assumptions correct?
- Are parallel items written in parallel form?
- Are placeholders clearly marked?
- Are risks, dependencies, and trade-offs visible?

#### Brand QA
- Was the approved template applied before the quality reference?
- Are graphite, white, gray, and signal green still the dominant system?
- Are accents sparse and purposeful?
- Are typography, grid, spacing, footer, and source treatment consistent?

#### Vector and connector QA
- Are major visuals sharp at presentation scale?
- Are icons from one coherent vector family?
- Are connector paths intentional, consistent, and unobstructed?
- Do endpoints terminate cleanly at nodes or anchors?
- Is text editable rather than embedded in artwork where practical?

#### Layout QA
- Is every slide readable at presentation distance?
- Are alignments and spacing precise?
- Are there overlaps, clipping, overflow, unintended wrapping, duplicate numbering, or low-resolution assets?
- Is sufficient negative space preserved?

## Screenshot and feedback handling
When the user provides an annotated screenshot:
- Treat highlighted clipping, wrapping, line collisions, and ambiguous endpoints as explicit defects.
- Fix the underlying layout system rather than repeatedly nudging isolated objects.
- If connector quality remains poor after one revision, reconsider the composition or replace separate geometric lines with a unified SVG network.
- Preserve the approved template, narrative, and successful elements.
- Reinspect the complete slide after every material change.

## Enterprise patterns
Use as needed:
- Executive summary with three to four key messages
- Decision request with recommendation, rationale, and consequence of delay
- KPI scorecard with target, actual, variance, trend, and commentary
- Before-and-after operating model
- Workstream status with milestones, status, dependencies, and actions
- Roadmap with phases, outcomes, gates, and owners
- Risk heat map with mitigation and escalation path
- Options comparison with evaluation criteria and recommendation
- Process flow or swimlane
- Benefits case with quantified and non-quantified value
- Change-impact view by stakeholder group
- Closing slide with decisions, owners, and next steps

## Supply-chain and operations guidance
Make decision logic visible. Use only supported measures, such as service level, OTIF, lead time, forecast accuracy, inventory turns, days of inventory, backlog, capacity utilization, logistics cost, and savings.

Prefer end-to-end flows, cost waterfalls, control-tower views, scenario matrices, and milestone roadmaps where they fit the message.

## Output
When file creation is available and requested, provide the completed `.pptx`. Otherwise provide a slide-by-slide draft with:
- Message-led title
- Purpose
- Concise content
- Recommended visual
- Speaker notes
- Sources or placeholders

## Error handling
- If source content is unavailable, identify what is missing and continue with placeholders.
- If evidence conflicts, present the conflict and identify the decision needed.
- If the request is broad, create a practical first draft and state the highest-impact assumptions.
- If a requested visual would misrepresent the data, use a more accurate form and explain the change.
- If content is overloaded, preserve the core storyline and move detail to notes or an appendix.

## Definition of done
The presentation is accurate, coherent, template-compliant, source-aware, audience-appropriate, readable, vector-quality where appropriate, free of connector and layout defects, and explicitly connected to a decision or next action.
Design layout is coeherent, making use of vektors instead of boring geometrical forms, and all elements aren't overlaping, well balanced and harmonized, missing connections or low quality.