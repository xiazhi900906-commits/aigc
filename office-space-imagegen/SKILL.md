---
name: office-space-imagegen
description: Create six-image office interior sets using the user’s 67-sample visual language, varied layouts, randomly selected style branches, restrained greenery, and Steelcase furniture. Use whenever generating or planning images of offices, workspaces, or workplace interiors.
---

# Office Space Image Generation

Generate office interiors using the user’s established reference language, while making every set and every scene feel deliberately designed rather than template-repeated. Read [visual-language.md](references/visual-language.md) and [steelcase-products.md](references/steelcase-products.md) before creating prompts.

## Standing requirements

- Produce exactly six separate image files per set, unless the user explicitly asks to change the count. Do not make a six-panel collage.
- Any plausible office-space type is allowed: open work areas, individual or executive offices, meeting rooms, lounges, collaboration areas, informal conversation zones, cafés/pantries, reception, training, focus rooms, libraries, project rooms, and others. The six images need not cover six different types. Repeating a type is fine, but give each instance a visibly different layout, furniture arrangement, spatial relationship, or composition.
- Randomize the style for each new set. Draw from the five visual branches in the reference; do not default to the same light palette every time. A set may share a randomly selected main direction or vary branches across images. Keep the references’ design quality and spatial realism, not a uniform palette or a single repeated furniture recipe.
- Greenery is a restrained accent: usually one or two localized plant moments, with clear pots/planters and generous negative space. Avoid plant walls, dense hanging vines, continuous lush borders, or plants as the dominant subject.
- Use Steelcase-family products as the principal workplace furniture. Match product category and range to use: ergonomic task chairs and workstations for desk areas, conference tables and chairs for meeting rooms, collaborative tables for teamwork, lounge products for social settings, and storage where useful. Rotate products appropriately rather than repeating the same chair/table in every image.
- Keep furniture ergonomically and spatially plausible, circulation clear, and one main visual focal point per image. Keep each image distinct while preserving a coherent, polished set.
- Honor explicit user choices for palette, style, aspect ratio, room types, continuity, and other constraints. Randomize only unspecified choices.
- Do not place UI, captions, labels, readable logos, watermarks, or screenshot chrome inside generated images. If the user asks for a specific exact Steelcase model, verify its current official appearance first; otherwise describe and render the right product category without claiming an exact SKU match.

## Workflow

1. **Resolve the brief.** Capture any specified image count (default six), aspect ratio, palette, functional needs, and whether the scenes belong to one connected office or separate projects. If the brief is open-ended, choose six complementary office settings; repeat types only when layout differences will be clear. Do not ask about details that can be reasonably randomized.
2. **Plan six distinct scenes.** For each image, note the function, architectural layout, furniture arrangement, camera position, main visual anchor, and Steelcase product family. Check that repeated functions differ structurally, not only in color or accessories.
3. **Randomize style.** Select one of the five branches in visual-language.md for the set or each image. Vary the palette, ceiling, lighting family, accent materials, and composition between new sets. Avoid reusing the previous set’s dominant combination when that history is available. A user-specified style always overrides the draw.
4. **Match Steelcase products.** Use the product mappings in steelcase-products.md. Browse Steelcase’s official product pages when exact model references or current product visuals matter. Include the actual product family/category in each prompt and place it naturally in the room; do not turn the space into a furniture showroom.
5. **Write image-specific prompts.** Describe scene/function first, then layout and circulation, product family, furniture arrangement, sparing plant accents, style branch, materials/palette, lighting, camera/framing, aspect ratio, and exclusions. Use the same chosen visual branch and continuity constraints only where the scenes truly form one office.
6. **Generate six images separately.** Use the image generation capability available in the current host, one distinct prompt per scene. Never substitute n=6 variants of one generic prompt for six different scenes. Ask for separate full-frame images, not a grid. Respect the requested aspect ratio.
7. **Inspect and refine.** Check exactly six outputs; confirm each reads as its intended office function, shows appropriate Steelcase-category furniture, has limited greenery, distinct composition, plausible furniture geometry, clear circulation, and no unwanted text/UI. If a specific defect is present, regenerate or edit only the affected image with a targeted correction.
8. **Deliver the set.** Save the six final image files with clear scene-based filenames in the designated output location. Present all six for review and state the chosen style branches and product families briefly. Do not imply photoreal images are exact catalog renders unless they were specifically verified as such.

## Prompt skeleton

> Create one standalone 3:4 portrait architectural interior image of [office function]. [Distinct spatial plan and circulation.] Furnish it primarily with Steelcase [verified family/category] selected for [use], arranged as [specific layout]; show a natural in-context workplace, not a product showroom. Randomized style branch: [branch and palette]. [Ceiling and one defining light feature.] Add only [one or two restrained plant accents]. [Materials and daylight.] Eye-level architectural photography, moderate wide angle, straight verticals, clear foreground/midground/background, realistic furniture scale and connections. No people, readable text, logos, watermarks, interface elements or collage.

Adjust the aspect ratio and scene details to the actual request. The skeleton is a starting structure, not a fixed furniture template.
