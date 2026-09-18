# Raster Quality Gate

Inspect the actual generated raster, not only the prompt. Judge success against the corresponding source photograph and the canonical production prompt.

## 1. Canvas and split

Success: a strict 3:4 vertical canvas divided horizontally into exactly equal top and bottom sections. The top occupies exactly 50% of the height and the bottom occupies exactly 50%.

The boundary reads as one clean, precise horizontal division. The two halves still feel like one refined editorial page.

Typical drift: unequal halves, an ambiguous split, a decorative divider, accidental overlap, a different aspect ratio, or a collage layout that no longer reads as one 3:4 folio page.

## 2. Top photograph fidelity

Success: the top half still reads unmistakably as the uploaded photograph. Preserve the main composition, subject count, identity, facial features when visible, body proportions, pose, expression, clothing, objects, spatial relationships, natural light, shadows, atmosphere, and source color mood.

Only subtle editorial grading and faint film grain are allowed.

If environmental extension is necessary to fit 3:4, extend only sky, ground, walls, or surrounding background seamlessly and photographically.

Typical drift: stretched or warped subjects, changed identity, altered pose, redesigned objects, artificial stylization, or background extension that changes the main subject.

## 3. Bottom illustration scale and composition

Success: the most recognizable source subject is reinterpreted as a minimalist handmade paper illustration. The main illustrated subject remains small, centered, and carefully composed, occupying approximately 10–20% of the bottom half, exactly as required by the canonical prompt.

Generous negative space must remain the dominant spatial condition of the lower half.

Typical drift: oversized illustration, crowded lower half, subject pushed to the edge without reason, full-scene redraw, or illustration so tiny or vague that recognition is lost.

## 4. Source fidelity in the illustration

Success: preserve the essential silhouette, proportions, key pose or gesture, important objects, and core narrative relationships needed for immediate recognition.

Simplification removes unnecessary detail without changing the identity of the subject or inventing a different scene.

Typical drift: generic substitute subject, wrong count, changed pose, missing defining object, altered person/animal identity, or invented scene relationship.

## 5. Paper illustration language

Success: the lower image visibly uses delicate slightly imperfect hand-drawn lines, a small number of acrylic-like flat color shapes, rough paper texture, visible handmade brush marks, slightly irregular organic edges, and subtle imperfections.

The palette is derived from the source and compressed to no more than 4 main colors.

Use only a few lines or color shapes for the surrounding environment.

Typical drift: glossy digital vector art, generic watercolor wash, photorealistic redraw, dense painterly rendering, too many colors, smooth synthetic gradients, or excessive detail.

## 6. Typography

Success: typography is optional. Do not force text into every output.

When text naturally belongs, keep it short, readable, understated, and editorial. It may be a short title, keyword, object name, location, year, number, or short phrase.

Typical drift: mandatory text in every result, long copy, garbled lettering, pseudo-text, advertising slogans, logos, QR codes, watermarks, or typography that dominates the lower half.

## 7. Overall mood

Success: the page feels quiet, poetic, refined, minimal, relaxed, artistic, thoughtful, recognizable, and premium. It should resemble a carefully designed independent art publication cover rather than a commercial advertisement.

Typical drift: busy commercial poster, loud branding, overly decorative layout, excessive color, visual clutter, or a generic filter treatment.

## 8. Multi-photo isolation

Success: input photo count equals output folio count, and every output can be traced only to its corresponding source.

Typical drift: multiple photos combined into one page or subject, palette, person, object, location, or scene leakage between different uploaded photos.

## Decision and retry

Central requirements are: strict 3:4 format, exact 50/50 horizontal split, faithful top photograph, recognizable lower illustration, 10–20% lower-half subject scale, generous negative space, restrained handmade-paper visual language, optional rather than forced typography, and multi-photo isolation.

If any central requirement clearly fails, refine the generation instruction only around the observed failure and regenerate that source image once. Do not touch successful jobs. After the second attempt, return the candidate that better satisfies the production contract. Never enter a further regeneration loop.
