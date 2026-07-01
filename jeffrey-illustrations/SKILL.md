---
name: jeffrey-illustrations
description: Create consistent Jeffrey & Byte personal IP illustrations for Chinese technical articles, README pages, blogs, social covers, avatars, stickers, PKM notes, AI / DevOps diagrams and warm hand-drawn visual metaphors. Use when generating, refining, QA-checking or prompt-writing images that must follow the Jeffrey Original or Jeffrey Q character system, Byte assistant mascot, blue-yellow brand palette, crayon texture, and anti-drift character constraints.
---

# Jeffrey Illustrations Skill

Use this skill to create warm hand-drawn illustrations for Chinese technical articles, blogs, README pages, PKM notes and AI / DevOps content using the Jeffrey & Byte character system.

## Default output

- 16:9 horizontal illustration
- Warm hand-drawn style with subtle crayon / colored pencil texture on characters, props and outlines
- Cream background `#FFF9EE`
- Jeffrey Blue Hoodie `#5379E8`
- Yellow J logo `#FFD84A`
- Round glasses
- Deep blue headphones `#2F56C5` with yellow inner ring `#FFD84A`
- Byte AI robot assistant when useful
- Short Chinese handwritten labels only when necessary
- Use the appropriate Jeffrey variant reference when available

## Palette lock

Assume the image model may not receive reference images. Always include this palette in the final prompt, especially when generating locally:

- Hoodie main blue: `#5379E8`
- Headphone / outline accent blue: `#2F56C5`
- Warm yellow accent: `#FFD84A`
- Cream background: `#FFF9EE`
- Denim jeans: `#88A8F5`
- Hair / line dark: `#2B2F36`

Use these as visual anchors, not decorative swatches. Avoid drifting into purple-blue hoodies, cyan headphones, orange yellow, brown hair, gray backgrounds or high-saturation rainbow colors.

## Texture lock

Use hand-drawn texture selectively:

- Jeffrey, Byte, clothing, hair, props and thick outlines: subtle crayon / colored pencil grain is welcome.
- Cream background: keep mostly flat, clean and quiet, with only minimal paper warmth.
- Chinese labels, cards, UI-like panels and small diagrams: keep clean and readable; use light hand-drawn outlines, not heavy grain.
- Shadows: use soft, sparse pencil hatching only under objects.

Avoid full-image crayon noise, dirty paper texture, grainy text, smudged labels, rough UI panels or a background that looks fully colored over.

## Character lock

Jeffrey must remain consistent:

- young male AI builder / DevOps engineer
- no beard, no mustache
- black or deep navy-black hair; never brown hair
- short rounded choppy hair, compact cap-like silhouette, small uneven hair clumps, soft off-center flow without a visible hard part line, slightly messy short bangs above the eyebrows
- bangs should fall forward in small short clumps across the forehead; do not expose a large forehead or sweep the hair into one side mass
- top hair stays low and rounded, close to the head; no raised crown, spikes or big fluffy hair volume
- round glasses
- deep blue over-ear headphones
- Jeffrey Blue hoodie with small yellow J logo
- jeans and white sneakers
- calm, focused, warm, lightly playful
- keep the head and face softly rounded, simple, cute and hand-drawn; avoid long face, narrow chin, semi-realistic adult portrait features or oval adult eyes

Supported visual variants:

- Jeffrey Original: slightly more mature and elongated than Q, but still soft and rounded; default for article illustrations, README banners and technical scenes.
- Jeffrey Q: rounder and more approachable; default for avatars, expressions, stickers, social covers and lightweight IP assets.
- Do not invent a third version. If the result looks like an adult semi-realistic portrait, a teen idol avatar, or a generic anime boy, reject it.

Both variants share the same identity, hair, outfit, colors and Byte assistant.

Byte must remain consistent:

- small round AI robot assistant
- blue, yellow and cream palette
- simple dot eyes
- helpful, curious, slightly goofy
- compact mascot body with tiny arms / legs or stable side pods; do not turn Byte into a large floating orb or generic drone
- do not write a large "Byte" word on Byte's body unless the user explicitly asks for a labeled character sheet

## Workflow

1. Read the user's topic, article, screenshot or Markdown.
2. Identify visualizable cognitive anchors: a turning point, workflow, structure, tension, state or metaphor.
3. Propose a shot list first when the user asks for planning.
4. For each image, pick one clear metaphor.
5. Make Jeffrey or Byte perform the core action.
6. Keep the composition clean; avoid PPT diagrams.
7. Choose a composition mode before writing the final prompt.
8. Choose Jeffrey Original or Jeffrey Q based on the use case.
9. Generate each image separately.
10. QA against references/qa-checklist.md.
11. Save and report output paths.

If a generation drifts, regenerate instead of accepting it. Common drift signs: Jeffrey looks older or semi-realistic, hair becomes brown, bangs sweep sideways into an adult hairstyle, the top hair becomes tall or spiky, Byte becomes a ball-shaped drone, the scene becomes a character design board, or the image contains many faded sketch thumbnails around the main subject.

For abstract topics such as style rules, visual guidelines, systems, standards or principles, convert the topic into one physical action metaphor first. Do not draw a whiteboard full of UI cards, text modules, charts or specification panels unless the user explicitly asks for an infographic.

## Composition modes

Use one of these modes explicitly:

- Warm Article Mode: for WeChat articles, blogs and narrative article body illustrations. Allows a few creator-context props such as notebook, coffee mug, plant, pencil cup or desk tools, but each prop must support the warm creator scene and must not distract from the core metaphor.
- Clean Skill Mode: for README, GitHub docs, Skill examples, Notion / Obsidian notes and method diagrams. Keep only the objects required by the metaphor; avoid decorative desk props.

Default mode:

- WeChat / blog / article body illustration: Warm Article Mode.
- README / GitHub / Skill example / technical documentation: Clean Skill Mode.

## Avoid

- cyberpunk hacker style
- business elite style
- anime style
- 3D render
- semi-realistic portrait style
- brown hair
- visible 4:6 / center part, curtain bangs, tall wavy quiff, spiky crown, salon-styled adult hair
- large exposed forehead, side-swept adult bangs, long oval eyes, narrow adult face
- adult handsome avatar proportions
- character-design presentation boards unless explicitly requested
- multiple faded alternative Jeffrey sketches around the main image unless explicitly requested
- Byte as a large labeled orb, drone or floating toy
- crowded UI screenshots
- whiteboards full of text cards or UI panels
- long Chinese text
- complex architecture diagrams
- decorative props that distract from the metaphor
- changing Jeffrey's outfit color unless the user explicitly asks for color exploration
- purple / violet hoodie, cyan headphones, orange logo, gray background, brown hair
