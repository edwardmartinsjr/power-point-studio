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
