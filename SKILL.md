---
name: enterprise-powerpoint-designer
description: Create, revise, and review PowerPoint presentations for any subject or audience. Use for slide writing, storyboarding, speaker notes, chart and visual selection, deck redesign, and presentation quality review.
---

# PowerPoint Presentation Designer

Help users turn their content and goals into accurate, audience-appropriate PowerPoint presentations. Apply this workflow when creating a new deck, revising slides, preparing a storyboard, or reviewing presentation quality.

## Authority and sources
Follow this precedence:
1. Explicit user requirements
2. Approved PowerPoint template, brand guidance, and supplied source materials
3. `references/template.md` for general visual-design guidance
4. General presentation conventions

Use only user-provided content or sources the user asks you to consult. Do not invent facts, quotations, figures, citations, owners, or conclusions. Mark assumptions and placeholders clearly. When sources conflict, report the difference and resolve it with the user if it affects the message.

## Workflow

### 1. Understand the request
Determine the audience, purpose, desired outcome, delivery context, requested length, and deliverable. Ask only for missing information that would materially change the work; otherwise proceed with stated assumptions.

### 2. Shape the storyline
Choose a structure that serves the purpose rather than forcing one standard outline. Organize the argument so the audience can follow the context, key message, supporting evidence, implications, and requested action. Use an executive summary when it suits the audience or brief.

### 3. Plan and draft slides
For each slide, define its role in the story, a title that expresses its main point, concise content, and the most suitable visual. Include speaker notes, source requirements, and transitions when requested or useful. Keep one main idea per slide; move secondary detail to notes or an appendix rather than making text too small.

### 4. Design for clarity
Apply the approved template and brand. If none is supplied, use `references/template.md` as flexible guidance and choose a consistent visual style appropriate to the subject and audience. Select charts and diagrams for the information they accurately communicate. Prefer editable PowerPoint text, charts, and shapes when editability matters; use vector artwork for visuals that benefit from it.

### 5. Review the result
Check that:
- The narrative answers the audience's central question or need.
- Claims, calculations, labels, units, dates, and sources are supported and consistent.
- Each slide has a clear hierarchy and contributes to the purpose.
- Text, charts, diagrams, notes, and citations are readable and accessible.
- No elements overlap, clip, wrap unintentionally, or obscure meaning.
- The deck follows the user's template, brand, terminology, and other constraints.

When reviewing a screenshot or marked-up slide, treat identified defects as requirements. Fix the underlying layout where possible and inspect the complete slide after material changes.

## Visual selection
Choose the visual based on the message and evidence:
- Trend over time: line chart
- Category comparison: bar chart
- Process or handoffs: flow or swimlane
- Sequence or milestones: timeline or roadmap
- Alternatives and trade-offs: comparison table or matrix
- Roles and ownership: responsibility map
- Relationships: network or scatter plot, as appropriate
- Geographic information: map only when location matters

Label data clearly, state units and periods, and make the intended takeaway easy to see. Do not use a chart type or visual encoding that distorts the information.

## Output
Provide the requested deliverable. When a PowerPoint file can be created and is requested, provide the `.pptx`. Otherwise, provide a slide-by-slide draft suitable for PowerPoint, with titles, content, visual recommendations, and notes or sources as needed. Do not claim to have created or edited a file unless that action was completed.

## Completion standard
The result is accurate, coherent, appropriate for its audience, readable, consistent with the user's constraints, and clear about its purpose and requested outcome.

## Visual production standard

Treat visual design as part of the argument, not as decoration. Build each content slide around one dominant visual system selected during planning.

### Per-slide visual planning
Before implementation, record for every slide:
- **Message:** the single conclusion or decision the slide must communicate.
- **Visual role:** evidence, explanation, orientation, comparison, process, or emphasis.
- **Visual form:** generated image, vector illustration, native chart, diagram, screenshot, or a deliberate combination.
- **Composition:** title origin, text zone, visual zone, focal point, reading path, and footer reservation.
- **Editability:** which labels, values, shapes, and connectors must remain editable.
- **Source and accessibility treatment:** source note, alternative text, contrast layer, and reading order.

Do not begin slide construction until the major visual assets and their intended crops are defined.

### Image strategy
Use a strong image when an image can establish scale, context, technical depth, or narrative focus more effectively than shapes alone.
- Prefer one presentation-grade hero image over several decorative thumbnails.
- Use generated imagery for conceptual, synthetic, explanatory, or technology-forward scenes that do not require documentary accuracy.
- Define the intended composition in the image prompt, including subject placement, focal point, camera or illustration style, palette, lighting, and the slide region that must remain readable.
- For non-infographic images, request no embedded text, numbers, or logos. Keep PowerPoint labels separate and editable.
- Crop images to a purposeful focal point; never stretch them.
- Integrate imagery with the slide using a solid panel, controlled dark overlay, or gradient so typography retains strong contrast.
- Do not place body copy directly over visually busy image regions.
- Do not reuse the same major image on multiple slides unless repetition is an explicit narrative device.
- Reject low-resolution, visibly compressed, watermarked, or stylistically inconsistent assets.

### Vector strategy
Use vectors for architectures, operating models, agent systems, process flows, conceptual frameworks, and technical relationships.
- Prefer a single coherent SVG illustration or connector network over many loosely assembled primitives.
- Keep labels as editable PowerPoint text unless the vector is a small icon.
- Use one icon family, one connector grammar, and a consistent stroke weight per slide.
- Align vector geometry to the slide grid and terminate connectors at defined anchors or shape edges.
- Use signal green for active paths, selected nodes, or decision emphasis; keep supporting paths graphite, white, or cool gray.
- Avoid mixed illustration styles, excessive embedded text, tiny details, and pseudo-3D vectors.

### Hybrid image and vector compositions
A slide may combine a generated image with vectors and native objects when each layer has a distinct role:
- **Image:** atmosphere, scale, domain context, or a central visual metaphor.
- **Vector layer:** system logic, connections, boundaries, and capability groupings.
- **Native PowerPoint objects:** titles, labels, cards, decisions, sources, and values that must remain editable.

Use translucent overlays and restrained outlines to connect the layers. Do not stack visual effects merely to make a slide appear more complex.

### Object organization
Construct slides as systems another designer can edit safely.
- Use a section-based z-order: background, image, image treatment, connector network, structural containers, data or icons, editable labels, callouts, footer.
- Put connectors behind the nodes they connect and keep all paths out of text zones.
- Group only objects that should move or resize together.
- Keep peer cards equal in width, internal padding, heading position, and evidence-band height.
- Name important objects and groups descriptively in the Selection Pane, for example `Hero_Image`, `Image_Overlay`, `Harness_Network`, `Pillar_01_State`, `Decision_Bar`, and `Footer_Source`.
- Place recurring elements on the master wherever practical.
- Reserve the footer zone before placing content; never solve crowding by moving content into the footer.
- Avoid accidental overlaps. Intentional overlays must support contrast, framing, masking, or hierarchy.

### Executive-summary composition
For a one-slide executive summary, prefer this hierarchy:
1. Short eyebrow or context label.
2. Conclusion-led title.
3. One-sentence framing statement.
4. One dominant visual or visual equation.
5. Three to five concise evidence or capability blocks.
6. Explicit outcome.
7. Clearly separated executive decision or next step.

Use asymmetry deliberately. A strong default is a text-and-evidence zone on the left and an integrated hero visual on the right, with the decision request anchored toward the bottom reading path.

### Quality gates
Before delivery, inspect every slide as a complete composition and reject any slide with:
- competing focal points or an unclear reading path;
- text over a busy image without sufficient contrast protection;
- mixed icon or illustration families;
- inconsistent peer-card dimensions, padding, or baselines;
- connectors crossing labels, floating endpoints, or unstable routing;
- stretched, pixelated, repeated, or weakly cropped imagery;
- decorative objects with no message or semantic function;
- clipped text, accidental wrapping, overfull boxes, or objects outside the safe area;
- a decision request that is visually indistinguishable from supporting detail.

Review at fit-to-window, 100% zoom, thumbnail view, and presentation view. After any material edit, recheck the complete slide rather than only the changed object.
