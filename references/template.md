# Enterprise PowerPoint Design-System Knowledge Base

## Status
This file is the design-system source of truth for the Enterprise PowerPoint Designer skill. A supplied quality reference may influence composition and craft, but it must not silently replace this system.

## Design hierarchy
Apply visual inputs in this order:
1. Explicit user requirements
2. Approved organization template or brand kit
3. This design-system reference
4. User-supplied quality references for composition and craft
5. General presentation conventions

## Core palette
Anchor the system in:
- **Graphite:** headings, body emphasis, decision bars, and authoritative structure
- **White:** canvas and negative space
- **Gray:** secondary text, dividers, borders, metadata, and supporting structure
- **Signal green:** emphasis, direction, active nodes, key numbers, highlights, and selected data

Rules:
- Use signal green as emphasis, not as a large text-heavy background.
- Use pale green-gray tints for contextual bands and subtle fills.
- Use additional accents only when meaningfully required.
- Do not let a composition reference introduce a new dominant palette without explicit approval.
- Do not rely on color alone to communicate status.

## Typography
- Use the organization-approved sans-serif.
- Use Aptos or Arial only when the approved font is unavailable.
- Use message-led titles with clear hierarchy.
- Maintain at least 11 pt body text.
- Use uppercase eyebrow labels sparingly.
- Avoid compressed text, excessive tracking, and all-caps paragraphs.
- Do not shrink text to solve overloaded layouts.

## Grid and spacing
- Use a shared grid with precise alignment.
- Use generous outer margins and consistent gutters.
- Prefer intentional asymmetry unless a radial or hub composition requires symmetry.
- Use equal internal padding for peer cards.
- Keep a consistent vertical rhythm between labels, titles, descriptions, and examples.
- Preserve sufficient negative space for presentation-distance readability.

## Composition
- Give each slide one dominant visual argument.
- Use executive-summary-first structure for leadership audiences.
- Prefer paths, networks, flows, matrices, timelines, layered models, and focused charts.
- Avoid default SmartArt, dense grids of unrelated boxes, decorative icon collections, and long bullet lists.
- Use photography and screenshots only when they add evidence or narrative scale.

## Vector illustration standard
Use scalable vector artwork for prominent technical and conceptual visuals.

Preferred:
- SVG path-based icons and illustrations
- Coherent line-art systems
- Vector connector networks
- Editable PowerPoint text layered separately from artwork
- Native charts, tables, and simple containers when editability matters

Avoid:
- Major illustrations assembled from many primitive circles and rectangles
- Mixed icon families
- Rasterized diagrams and low-resolution screenshots
- SVG artwork with excessive embedded text
- Decorative icons that do not carry meaning

Vector consistency requirements:
- Shared view-box logic
- Consistent stroke width and visual weight
- Consistent line caps and joins
- Consistent corner and geometric language
- Restrained signal-green accents within graphite line art
- Legibility at slide and projected scale

## Connector grammar
Approved connector grammars:
- **Orthogonal:** systems, architectures, and operating models
- **Radial:** true hub-and-spoke relationships
- **Elbow-routed:** controlled card-to-hub compositions

Rules:
- Use one connector grammar per visual.
- Prefer one SVG connector network when paths form one system.
- Draw connectors behind nodes, cards, and hubs.
- Terminate paths at shape edges or anchor dots.
- Keep paths outside text areas.
- Use consistent stroke color and width.
- Keep anchor dots small and purposeful.
- Avoid floating endpoints, accidental tangencies, arbitrary diagonals, mixed weights, label crossings, and hub collisions.

## Component cards
A standard component card contains:
1. Number or category marker
2. Consistent vector icon
3. Short component title
4. One-sentence role, capability, or benefit
5. Optional example or evidence band

Use equal widths, padding, title positions, and example-band heights. Use white fills, subtle gray borders, and shallow or no shadows unless depth is necessary.

## Central hubs
For agent, platform, control-tower, or operating-model diagrams:
- Use a visually calm central hub.
- Clearly name the hub and role.
- Limit surrounding components to a readable number.
- Use a subtle halo, boundary, or tint to establish hierarchy.
- Keep the illustration vector-based and consistent with surrounding icons.
- Keep connector endpoints and labels out of the hub's key text area.

## Chart conventions
- State the intended takeaway.
- Highlight the relevant series or data point in signal green.
- Mute secondary information in gray.
- Use line charts for trends, bars for comparisons, bullet or variance charts for target gaps, stacked bars for composition, and scatter plots for relationships.
- Use maps only when geography is material.
- Use pie or donut charts only for a small number of categories.
- Label units, periods, assumptions, and sources.

## Footer and sources
- Keep footers restrained and consistent.
- Include classification, slide number, and source treatment where required.
- Keep short citations on the slide.
- Move long references to speaker notes or a references slide.
- Do not let the footer compete with the dominant visual.

## Speaker notes
Include, where relevant:
- Talk track and emphasis
- Definitions and caveats
- Supporting evidence
- Likely questions
- Decision or response to solicit
- Source references
- Visual rationale

Do not repeat the slide verbatim.

## Accessibility
- Ensure readable contrast and presentation-distance legibility.
- Do not rely on color alone.
- Reinforce meaning with labels, patterns, icons, or position.
- Preserve logical reading order.
- Use descriptive alternative text where supported.
- Avoid overly thin strokes and tiny text.

## Visual quality checklist
Confirm before delivery:
- The template palette remains dominant.
- Typography is consistent and readable.
- The slide has one dominant visual argument.
- Vector icons belong to one coherent family.
- Connector paths are clean, intentional, and unobstructed.
- No connector crosses text or terminates ambiguously.
- Peer cards use equal spacing and padding.
- No clipping, overflow, accidental wrapping, or duplicate numbering exists.
- No low-resolution assets are present.
- Decision requests and next steps are unmistakable.
- Footer and source treatment are consistent.

## Learning from quality references
A quality reference may inform hierarchy, composition archetype, white-space ratio, connector routing, card anatomy, numbering, and icon weight.

A quality reference must not automatically override palette, typography, footer, accessibility, citation style, confidentiality markings, or approved terminology.

## Iterative review
- Treat annotated clipping, line collisions, and wrapping as defects.
- Fix the layout system, not only the individual object.
- Preserve approved narrative and brand decisions.
- If separate connector shapes remain unstable, replace them with one SVG connector network.
- Reinspect the complete slide after every material change.

---

## Reference-derived visual definitions

### Purpose and interpretation

The following definitions enrich the design system by translating the supplied presentation into reusable visual rules. They are generic enough for enterprise presentations and specific enough for a agent designer to execute without reverse-engineering the example deck.

The supplied presentation is a **quality and visual-language reference**, not a mandatory master. Apply these definitions beneath explicit user requirements and approved brand assets. Preserve the original hierarchy, accessibility, confidentiality, source, and terminology rules above.

### Reference profile

The reference establishes an executive, technology-forward presentation language characterized by:

- 16:9 widescreen composition.
- Predominantly dark graphite canvases with white or cool-gray text.
- Bright green as the principal signal color.
- Blue, cyan, orange, amber, and coral used as secondary semantic accents.
- Strong message-led titles, compact supporting copy, fine rules, outlined cards, and low-decoration layouts.
- A mix of dark narrative slides and light analytical or learning slides.
- Left-aligned content as the default; centered typography reserved for chapter dividers, breaks, or single-question slides.
- Thin line work, square or mildly rounded geometry, minimal shadows, and a high ratio of negative space.

Do not imitate individual slides literally. Reuse the visual grammar: hierarchy, contrast, spacing, stroke discipline, and controlled color coding.

## Canvas, master, and safe area

### Slide format

- Use **16:9 widescreen** at **13.333 × 7.5 in**.
- Build all layouts from a common master rather than positioning recurring elements manually.
- Keep all essential content inside a practical safe area of approximately:
  - **0.35–0.55 in** left and right.
  - **0.25–0.45 in** top.
  - **0.25–0.40 in** bottom, excluding approved footer elements.
- Use a consistent title origin across content slides. A practical default is 0.40–0.55 in from the left edge and 0.35–0.55 in from the top edge.
- Reserve a fixed footer zone. Do not allow charts, cards, or imagery to drift into classification, page-number, brand-mark, or source areas.

### Grid

Use a flexible **12-column grid** with consistent gutters. Recommended implementation:

- 12 equal columns across the safe area.
- Gutters of approximately **0.14–0.20 in**.
- Primary compositions should resolve into 3, 4, 6, 8, or 12-column spans.
- Use a minimum visible separation of **0.20 in** between unrelated blocks.
- Align text, card edges, chart plot areas, rules, and image crops to the same column or baseline system.

For dense executive slides, establish three horizontal zones:

1. **Header zone:** eyebrow, title, optional subtitle.
2. **Content zone:** dominant visual argument and supporting evidence.
3. **Footer zone:** sources, classification, slide number, or mark.

### Alignment discipline

- Use left alignment for most titles, body copy, labels, and tables.
- Use centered alignment only for chapter dividers, deliberate pauses, single statements, and single questions.
- Avoid visually centered objects that are not geometrically aligned to the grid.
- Align peer elements by both edge and baseline, not by eye.
- Use optical correction only when an icon, numeral, or irregular shape appears off-center despite mathematical alignment.

## Color system

### Core dark theme

Use the following reference-derived colors as a controlled enterprise palette:

| Token | Hex | Primary use |
|---|---:|---|
| Graphite canvas | `#303034` | Main dark slide background |
| Deep graphite | `#1F2023` | Dark text on light slides; deep emphasis areas |
| Dark surface | `#38383D` | Cards, panels, cover details, secondary dark surfaces |
| Raised dark surface | `#47474D` | Card fills, separators, subdued structure |
| White | `#FFFFFF` | Primary typography on dark backgrounds |
| Cool light gray | `#E3E6EB` | Secondary text, body copy, subtle lines on dark backgrounds |
| Mid gray | `#A8ABB2` | Metadata, captions, inactive states, tertiary labels |
| Dark mid gray | `#6F7378` | Body text and captions on light backgrounds |
| Signal green | `#00E676` | Primary emphasis, selected state, key number, active path |
| Deep signal green | `#00C875` | Secondary green state or supporting emphasis |
| Electric blue | `#1F6BFF` | Secondary category, second pathway, planning state |
| Cyan | `#39D8FF` | Tertiary pathway or learning-stage distinction |
| Orange | `#ED7D31` | Regional/local category, caution, or a third semantic pathway |
| Amber | `#FFB300` | Warning or limitation requiring attention |
| Coral | `#FF6A5A` | Gap, risk, unresolved ownership, or adverse condition |

### Light theme

For analytical, training, and matrix slides, use:

- Canvas: `#F4F5F6`, `#FFFFFF`, or a similarly neutral cool white.
- Primary text: `#1F2023`.
- Secondary text: `#6F7378`.
- Dividers and table fills: pale cool grays such as `#DFE2E5`.
- Retain signal green and electric blue as the principal semantic accents.

### Color application rules

- Keep one dominant accent color per slide, normally signal green.
- Use secondary accents only when they encode distinct categories, stages, or statuses.
- Do not use accent colors as decoration without semantic meaning.
- Dark slides should normally use white for titles and cool light gray for body copy.
- Light slides should use deep graphite for titles and dark mid gray for body copy.
- Use colored text primarily for short labels, values, category names, or questions. Avoid long paragraphs in bright accent colors.
- Use muted colors for inactive, historical, contextual, or unselected information.
- Restrict warning colors to genuine risks, constraints, or exceptions.
- When several accents appear, define their meaning once and reuse it consistently throughout the deck.
- Pair every status color with a text label, icon, line style, or position.

### Contrast target

- Design normal text to meet at least **4.5:1** contrast against its background.
- Large text may use a minimum of **3:1**, but stronger contrast is preferred for projected presentations.
- Do not place cool-gray body text over photography unless a solid or sufficiently opaque contrast layer is used.

## Typography system

### Typeface strategy

The reference uses **Aptos** as the dominant working typeface, with limited use of organization-specific display fonts. Apply this generic rule:

1. Use the approved organization font family when it is available to all editors and viewers.
2. Use its display or semibold face for titles and its book or regular face for body copy.
3. Use **Aptos** as the preferred cross-platform fallback.
4. Use **Arial** only when broader compatibility is required and Aptos is unavailable.
5. Do not mix more than two font families in one presentation.

If brand display fonts are used, restrict them to cover typography, chapter markers, or major display labels. Keep operational slide text in a highly legible sans-serif.

### Recommended type scale

Use the following ranges as starting points. Select a size based on content density and viewing distance, then keep the chosen hierarchy consistent.

| Role | Recommended size | Weight and treatment |
|---|---:|---|
| Cover title | 30–48 pt | Semibold/bold; 1–3 lines maximum |
| Chapter-divider title | 28–40 pt | Regular to semibold; centered only when intentional |
| Content-slide title | 24–30 pt | Semibold/bold; message-led |
| Major question or callout | 22–32 pt | Medium/semibold; may use signal color |
| Section or card heading | 14–18 pt | Semibold/bold |
| Body copy | 12–16 pt | Regular; 14 pt preferred for normal content |
| Table text | 10.5–14 pt | Regular; semibold for headers |
| Labels, legends, metadata | 9–12 pt | Regular or semibold |
| Sources and footer | 8–10 pt | Regular; never below 8 pt unless mandated |
| Large KPI | 28–48 pt | Semibold/bold; units visually secondary |

Observed reference sizes cluster around 11, 12, 14, 16, 17, 18, 24, and 28 pt. Use a small, repeatable scale rather than many near-duplicate sizes.

### Type hierarchy rules

- Write slide titles as conclusions, questions, or action statements rather than neutral topics when the narrative permits.
- Keep content titles to one line where possible and two lines maximum.
- Use sentence case for titles. Reserve uppercase for short eyebrow labels, categories, statuses, and table headers.
- Use bold to establish hierarchy, not to emphasize entire paragraphs.
- Use accent color on a short phrase or key word rather than styling the whole title.
- Use line spacing of roughly **1.0–1.15** for large titles and **1.05–1.25** for body copy.
- Use paragraph spacing rather than manual blank lines.
- Keep tracking neutral. Do not artificially expand body text.
- Avoid widows, orphans, and single-word final lines in titles or key statements.
- Do not use underlining except for actual hyperlinks.

## Surfaces, strokes, corners, and depth

### Cards and panels

- Use cards only when they create meaningful grouping or comparison.
- On dark slides, cards may use transparent fills, `#38383D`, or `#47474D` with a restrained border.
- On light slides, use white or pale-gray surfaces with subtle gray dividers.
- Standard card border: **0.75–1.25 pt**.
- Primary or selected card border: **1.25–2 pt** in the semantic accent.
- Internal padding: approximately **0.15–0.25 in**, increasing for large cards.
- Corner radius should be square to mildly rounded. Do not combine sharp and highly rounded cards in the same system.
- Prefer no shadow. If separation is necessary, use a very soft, low-opacity shadow with minimal offset and blur.

### Lines and dividers

- Use fine rules to organize sections and tables.
- Default divider: **0.5–1 pt**, cool gray, low contrast.
- Primary accent rule: **1–2 pt** in signal green or the relevant category color.
- Keep line endings consistent across the deck.
- Avoid thick ornamental lines, beveled strokes, glow, gradient outlines, and pseudo-3D treatment.

### Reusable edge treatments

Approved recurring treatments include:

- A thin signal-green line along the top edge of a dark slide.
- A slender vertical signal-green rule beside a cover title or agenda block.
- Thin horizontal rules separating narrative sections.
- An accent underline indicating the active category or pathway.

Use such treatments consistently through the master. Do not add them sporadically.

## Layout archetypes

### Cover slide

Use when establishing the subject, audience, and session context.

- Dark graphite canvas.
- Strong left-aligned title block.
- Short eyebrow or organizational label in signal green.
- Supporting date, meeting, or author information in cool gray.
- Optional oversized, low-contrast thematic letterform or vector on the opposite side.
- Optional fine multicolor line treatment as a minor brand detail.
- Keep the cover sparse. Do not preview the full agenda.

### Chapter divider

- Use a dark canvas with a centered or carefully left-aligned chapter title.
- Use large regular or medium-weight typography rather than excessive bold.
- No more than one short title and one optional subtitle.
- A thin top or bottom signal line may reinforce continuity.

### Executive summary

- Begin with one conclusion-led title.
- Use three to five evidence blocks, a clear decision or recommendation, and one unmistakable takeaway.
- Place the most important block in the upper-left or center-left reading path.
- Use a decision bar or next-step strip at the bottom only when it adds a clear action.

### Framework or operating model

- Use a dominant top-level outcome, several activation paths or pillars, and a clearly separated foundation layer.
- Use outline cards and thin connectors rather than heavy filled boxes.
- Encode categories with restrained accents.
- Keep the relationship between strategy, delivery paths, foundations, and impact visually explicit.
- If the model cannot be understood without narration, simplify it.

### Process slide

- Use numbered stages with a clear left-to-right or top-to-bottom reading order.
- Keep stage titles short and stage descriptions to one sentence.
- Use consistent card dimensions and connectors.
- Clearly distinguish current, future, completed, and exception states.
- Never allow a connector to pass through, touch, or visually merge with text.

### Timeline or cadence slide

- Use a single axis and a stable rhythm.
- Place duration, stage, activity, and evidence in consistent positions.
- Use accent colors to distinguish phases only when the distinctions matter.
- Keep time units explicit and do not imply precision that the content does not support.

### Comparison or two-path slide

- Use mirrored or balanced columns with a neutral center spine for dimensions or criteria.
- Apply one accent per path.
- Keep equivalent content at equivalent vertical positions.
- If one path is primary, indicate priority through scale, placement, or emphasis rather than by making the other unreadable.

### Evidence and chart slide

- Place the chart or evidence artifact as the dominant visual.
- Position interpretation, implications, or capability requirements adjacent to the evidence.
- Include a concise takeaway directly below or above the chart.
- Keep sources close to the evidence and inside the safe area.

### Screenshot or product slide

- Use one high-resolution screenshot as the main visual.
- Crop interface chrome that does not contribute to the point.
- Place the screenshot in a clean frame with a subtle border.
- Use short callouts outside the screenshot, connected by clean leaders.
- Do not place paragraphs over the screenshot.

### Question or discussion slide

- Use one central question or a short set of clearly ordered prompts.
- Use signal green to emphasize the key phrase, not necessarily the entire sentence.
- Keep the rest of the slide visually quiet to create a deliberate pause.

### Closing slide

- Use a sparse brand-led composition.
- Include only the closing message, brand mark, and essential contact or follow-up detail.
- Avoid adding new content or secondary conclusions.

## Data visualizations and tables

### Chart styling

- Use flat, native PowerPoint charts where practical.
- Remove chart border, background fill, unnecessary gridlines, and redundant legends.
- Use direct labels when they reduce eye movement.
- Highlight the decisive series or point in signal green.
- Show supporting series in cool grays or one restrained secondary accent.
- Use consistent axis, number, and date formats throughout the deck.
- Avoid 3D charts, gradients, bevels, pictorial bars, and decorative chart junk.
- Do not use smooth curves when they may imply values not present in the data.
- Always include the unit and time period.

### KPI treatment

- Use a large number, a short label, and one explanatory line.
- Keep currency, percentage, or unit logically attached to the number.
- If several KPIs appear, align baselines and use identical formatting.
- Color a KPI only when the color communicates category or status.
- Do not combine estimated and actual values without explicit labels.

### Table styling

- Use tables only when exact lookup or structured comparison is required.
- Prefer white or very light surfaces for dense tables, even in a dark-themed deck.
- Use dark graphite text on light table cells.
- Apply a strong header row with high contrast.
- Use thin internal rules and restrained row banding.
- Avoid vertical rules unless they materially improve scanning.
- Keep equivalent columns aligned and prevent text from touching cell edges.
- Use color sparingly for a selected column, key row, or status.
- If the table cannot be read at presentation distance, split it or move detail to an appendix.

## Imagery, screenshots, and illustrations

### Photography

- Use photography when it creates scale, context, human relevance, or a clear transition.
- Prefer one strong image over several small decorative images.
- Use purposeful crops with a visible focal point.
- Protect title and body text with a solid panel, gradient overlay, or sufficient negative space in the image.
- Avoid generic stock imagery that adds no evidence or narrative value.

### Screenshots and external clippings

- Use the highest-resolution authorized source available.
- Crop tightly and consistently.
- Preserve essential source identity and context.
- Add a source line where required.
- Do not enlarge a screenshot beyond a level where text and edges visibly pixelate.
- Never use screenshots as substitutes for editable charts when the underlying data is available.

### Vector imagery

- Use one coherent family of line icons or custom vectors.
- Match stroke weight, corner treatment, and geometry to the rest of the deck.
- Keep prominent illustrations editable where possible.
- Avoid mixing photorealistic renders, outline icons, flat illustrations, and emoji-like graphics on the same slide.

## Icons and symbols

- Use icons to identify concepts, stages, roles, or systems, not to decorate headings.
- Use one icon style per deck.
- Keep icon size consistent within a component family.
- Use white or cool gray as the default icon color on dark slides, with a small accent highlight where needed.
- Use deep graphite on light slides.
- Avoid detailed icons smaller than approximately **0.25 in**.
- Do not use more than one icon per small card unless each icon carries unique meaning.

## Interaction of dark and light slides

The reference demonstrates two complementary modes. Use them deliberately:

- **Dark mode:** strategic narrative, frameworks, decisions, process, executive discussion, section transitions, and high-impact statements.
- **Light mode:** detailed comparison, learning paths, matrices, analytical tables, and content requiring sustained reading.

A deck may use both modes, but transitions must be purposeful. Do not alternate backgrounds randomly. A practical rule is to keep a section internally consistent and switch modes when the content type changes.

## Footer, classification, branding, and sources

### Footer system

Create one master footer with dedicated positions for:

- Classification or confidentiality label.
- Slide number.
- Short source or document identifier where required.
- Brand mark.

Recommended treatment:

- 8–10 pt text.
- Cool gray on dark backgrounds and dark mid gray on light backgrounds.
- Low visual prominence.
- Fixed alignment and position on every applicable layout.

Do not stretch or recolor a brand mark outside approved brand rules. Reserve enough clear space around it.

### Source treatment

- Put short sources directly on the slide in 8–10 pt.
- Use a concise format: organization, publication or dataset, date, and link or identifier when required.
- Put long bibliographies, methodological detail, and access notes in speaker notes or a references slide.
- Keep source text readable and do not conceal it in low-contrast gray.

## Content-density standards

### Maximum practical density

Treat the following as quality thresholds, not rigid quotas:

- One dominant message per slide.
- One major visual or a tightly integrated visual system.
- Three to five peer cards or stages when each requires explanation.
- Six to eight items only when labels are short and the structure is obvious.
- One sentence per small card.
- No more than two levels of bullets on standard content slides.
- Avoid more than approximately 60–80 words of body copy unless the slide is intentionally a table, appendix, or reading artifact.

When content exceeds these thresholds, split the slide, move detail to notes or appendix, or replace prose with a meaningful visual structure.

## Animation and transition standard

- Use no transition or a simple fade as the default.
- Use animation only to control narrative reveal, explain a process, or prevent premature reading.
- Use one animation style per slide.
- Prefer appear, fade, or wipe with restrained duration.
- Avoid bounce, spin, fly-in from arbitrary directions, sound effects, and continuous motion.
- Ensure the slide remains understandable in exported PDF form.

## Agent Designer handoff specification

Every designed presentation should include or document:

- Slide size and master layouts.
- Theme font mapping and fallbacks.
- Theme color tokens and semantic meanings.
- Grid, margin, gutter, and footer dimensions.
- Title, subtitle, body, label, source, and KPI styles.
- Card, line, connector, table, and chart styles.
- Icon family and illustration rules.
- Approved dark and light background variants.
- Accessibility decisions, including contrast and reading order.
- Source and classification treatment.
- Any nonstandard fonts, linked data, embedded media, or required licenses.

Keep all recurring objects on the master where practical. Rename important objects in the Selection Pane so another agent designer can understand the construction.

## Quality assurance standard

### Visual inspection

Review each slide at:

1. **Fit-to-window:** validates overall hierarchy and balance.
2. **100% zoom:** validates type, line quality, image resolution, and spacing.
3. **Thumbnail view:** validates sequence, section rhythm, and consistency.
4. **Projected or presentation view:** validates distance readability and contrast.

### Technical inspection

Confirm that:

- Slide dimensions are correct.
- No objects extend outside the canvas unintentionally.
- No fonts are substituted unexpectedly.
- No linked images or data sources are broken.
- Images are sufficiently sharp for their placed size.
- Charts and tables remain editable unless an approved exception exists.
- Alt text and reading order are set where supported.
- Animations do not hide critical content in PDF exports.
- Speaker notes do not contradict slide content.
- Classification and source requirements are applied consistently.

### Craft inspection

Reject or correct slides containing:

- Misaligned edges or inconsistent baselines.
- Unequal padding among peer components.
- Near-duplicate font sizes that weaken hierarchy.
- Mixed icon families or inconsistent stroke weights.
- Decorative color with no semantic role.
- Text smaller than the defined minimum without an approved exception.
- Overfull text boxes, clipped glyphs, accidental line wraps, or widows.
- Low-contrast footer or source text.
- Connectors that cross labels, terminate ambiguously, or collide with hubs.
- Excessively busy backgrounds behind critical information.
- Multiple equally dominant messages.

## Final delivery checklist

Before release, the agent designer must be able to answer **yes** to all of the following:

- Is the storyline understandable from slide titles alone?
- Does each slide express one primary message or decision?
- Is the palette semantically consistent?
- Are dark and light slide modes used intentionally?
- Is the typography hierarchy consistent across all layouts?
- Can body text be read comfortably at presentation distance?
- Do all components align to a common grid?
- Are cards, strokes, corners, and connectors consistent?
- Are visuals, charts, and screenshots necessary and high quality?
- Are key numbers, units, assumptions, and sources explicit?
- Are status and meaning conveyed by more than color alone?
- Are classification, slide number, branding, and source placement correct?
- Are there no clipping, overflow, low-resolution, or substitution defects?
- Does the deck remain understandable when exported to PDF?
- Can another agent edit the file without rebuilding the visual system?

## Generic design brief for creating a new presentation

When handing this system to a agent, use the following brief:

> Create a 16:9 executive enterprise presentation using a disciplined graphite, white, cool-gray, and signal-green visual system. Use a message-led narrative, a shared 12-column grid, restrained line work, coherent vectors, and editable charts. Keep dark slides for strategic narrative and light slides for dense comparison or learning content. Apply accent colors only for semantic categories, statuses, risks, or stages. Use the approved organization font or Aptos fallback, with a repeatable hierarchy from 24–30 pt slide titles to 12–16 pt body text and 8–10 pt sources. Prioritize one dominant visual argument per slide, presentation-distance readability, precise alignment, clean connectors, consistent footers, accessible contrast, and defect-free delivery. Avoid generic SmartArt, decorative icon collections, dense bullet walls, excessive shadows, 3D effects, and low-resolution screenshots.
