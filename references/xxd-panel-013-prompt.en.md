# XXD Panel 013 | Healing Watercolour Collectible-Ticket Production Prompt

## Runtime complete-canvas contract — highest priority

- `TOP_BOTTOM` and `LEFT_RIGHT` default to one complete finished generation using the current source as a high-fidelity edit/reference input. Do not pre-split the job into photographic and design halves.
- Top-bottom keeps the faithful source in approximately the upper 50% and performs this style transformation below; left-right uses the faithful source in approximately the left 50% and the transformation on the right. Unify both regions through colour, light, rhythm, typography, and meaning.
- `DESIGN_ONLY` and `WALLPAPER_PACK` use the complete canvas while the source remains an invisible identity/content reference. Recompose every wallpaper separately for its device.
- `FINAL CANVAS` means the ratio/pixels of the whole finished artwork and must be explicitly resolved before generation; never apply source dimensions silently. `DESIGN FRAME` is used only if a failed complete-canvas retry triggers deterministic composition fallback.
- Retry a failed complete canvas once against the failed constraint only. Scripted composition is allowed only after that retry still fails, when pixel-identical source preservation is explicitly required, when the active route cannot realise the canvas, or for lossless pixel calibration.

### Model priority and credentials

- **Prefer GPT Image 2.** When GPT Image 2 is available through the current built-in image tool or a configured compatible route, use it first for the high-fidelity reference/edit and complete-canvas generation required by this prompt.
- Also support Seedance 5.0 Pro, Nano Banana Pro (Gemini Image Pro), Nano Banana 2 (Gemini Image Flash), or another compatible bitmap model only when the actual route can preserve the source, realise the whole finished canvas, render the target-language text, and accept the multiple references needed by a linked wallpaper pack.
- An alternative model changes only the generation route. It must not change this prompt's modes, canvas, source visibility, copy, locale, wallpaper relationship, or complete-canvas-first / composition-fallback-only logic. Do not silently downgrade a hard requirement.
- If no suitable route is available, ask the user to enable an image-generation tool or provide an API key. User-provided credentials may be used for the current task, but never echo, display, log, or expose their value in chat, prompts, or diagnostics. Do not persist them or modify global route configuration unless explicitly requested.
- Judge availability by actual image capability, not by a provider name or one missing environment variable.

Process only the one source photograph explicitly supplied for this current task. Lock the subject, necessary environment, silhouette, pose, structure, placement, scale, and narrative relation. Preserve at least three source-specific recognition cues. Never borrow a place, subject, palette, ticket data, copy, or composition from old outputs, samples, or another input.

## Subject and necessary environment

Find the source's most memorable subject–environment relation and summarise it inside one horizontal watercolour ticket. People retain pose, orientation, clothing mass, and relational distance; animals retain body rhythm and setting; plants retain growth gesture and light; architecture retains skyline and defining openings; objects and vehicles retain functional silhouette, scale, and placement; landscapes retain the source-specific horizon, terrain, path, water, or atmosphere.

Never isolate the subject from an environment required for identity or meaning. Secondary detail may soften, but preserve the minimum setting and spatial relation needed for immediate correspondence with the photograph. Add no generic landmark, airport code, route, tourism story, or unsupported prop.

## One ticket and 74/26 geometry

Suspend exactly one horizontal ticket inside generous ivory or warm-white space. Keep it as the only focus; do not repeat cards, build a collage, or enlarge the ticket to fill the canvas. Use thick matte watercolour stock, a fine deckled or micro-serrated edge, and only a very light natural contact shadow. Reject stains, burnt edges, cracks, and theatrical ageing.

The ticket is strictly large-left/small-right: about 74% watercolour scene and 26% information stub. Divide them with one precise vertical dashed perforation, tooth line, or tear line. Never drift toward equal halves, a diagonal split, or irregular scrapbook layers. Keep consistent top and bottom margins; image, type, stamp, number, short rules, and dot rows obey one implicit grid and baseline family.

## High-value healing watercolour

Choose the freshest and most vital source colours, translating them into two to four neighbouring high-value, low-to-medium-saturation natural tones. Sage, mist blue, pale blue-grey, cream yellow, warm sand, and light terracotta are possible directions, never a fixed palette. Use only a tiny warm contrast when supported by the source.

Brushwork is clear and light, preserving paper white, soft blooms, transparent layering, wet/dry variation, and a little pigment grain. Keep the subject slightly clearer while distance and secondary environment soften. Build hierarchy through watercolour concentration and edge control rather than realistic lighting, complex detail, digital gradients, or heavy opaque fill.

Reject muddy haze, yellow cast, heavy brown, loud colour collision, cheap vintage filters, cinematic glow, thick oil impasto, photoreal rendering, plastic texture, and 3D.

## Information stub and copy

Obey the resolved automatic, exact-user, or text-free copy mode and target language or locale. Preserve exact user wording verbatim. In text-free mode render no field, number, stamp lettering, text, or pseudo-text.

Automatic copy creates one extremely short source-bound title or moment phrase and only a minimal useful field set. Native equivalents of DATE, PLACE, SUBJECT, MOMENT, FIELD, and NO. may be used, but both labels and values must be localised rather than silently left in English.

Dates, places, coordinates, routes, ticket numbers, provenance, and travel events must be user-supplied, visibly established, or reliably confirmed. Never fabricate them. For non-city or non-travel subjects, replace irrelevant place fields with object, state, project, chapter, season, relation, or emotion records grounded in the image. Compositional indexes must visibly read as indexes rather than facts.

Align all fields to one left edge, baseline family, and interval system with clear hierarchy and ample whitespace. Use only one restrained circular stamp; it may overlap the divider or lower grid slightly without obscuring valid information. Reject floating data, a wall of decorative postmarks, tourism slogans, oversized headlines, and software-UI styling.

## Mode and acceptance


Hard gate: exactly one centred horizontal ticket in generous ivory space; at least three source cues and the necessary subject–environment relation; thick matte watercolour stock, fine edge, and very light contact shadow; approximately 74/26 large-left/small-right geometry with one precise vertical perforation; two to four neighbouring healing colours, light transparent watercolour, a slightly clearer subject, and softened environment; locale-native right-stub fields on common left edges and baselines, one circular stamp, and no fabricated facts; no isolated-object vignette, full-bleed generic watercolour, dirty ageing, yellow-brown cast, loud collision, loose type, excessive ornament, photoreal illustration, ecommerce template, photo fragment, or pseudo-text.

If any hard condition fails, correct the generated asset. Never fake the artwork with programmatic drawing, SVG, HTML, Canvas, or a post-composited type overlay.
