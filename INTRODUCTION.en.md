# I built an AI writing workspace for long-form fiction creators

**Lambfolio** is the English name for 小羊成卷, a macOS writing tool for long-form fiction creators.

It is not a “one prompt writes the whole book” generator, and it is not a traditional text editor. It is closer to a workflow workspace: project brief, worldbuilding, characters, outlines, chapters, and prose revision are split into steps that can be reviewed, confirmed, revised, or regenerated.

## Why it exists

The hardest part of writing long-form fiction is often not producing a paragraph. It is keeping the whole work coherent over time.

Common problems include:

- Character motivations drift.
- World rules become inconsistent.
- Outlines stay vague and fail to guide actual chapters.
- AI-generated prose reads smoothly but ignores earlier settings.
- Revisions accidentally damage plot facts, character facts, or pacing.

Lambfolio is designed to help with these workflow problems.

## How it works

The app breaks novel creation into stages. Each stage has inputs, generated artifacts, and human confirmation.

You can start with a project brief, then build the world, characters, and story outline, and later use that context for prose generation or focused revision. After each important output, you review it before moving forward. If it does not work, you can revise or regenerate.

The goal is not to hand control to AI. The goal is to let AI help organize, expand, and move the work forward while the author keeps final judgment.

## Who it is for

Lambfolio may be useful for:

- Writers working on novels, web fiction, or series fiction.
- Creators who already use AI but struggle with context and continuity.
- Writers who want project notes, characters, worldbuilding, outline, and prose workflow in one place.
- Early users who are willing to try the tool and share feedback.

It is probably not the right tool if you only need a plain text editor, or if you expect one-click generation of a complete finished book.

## What it can do now

- Project brief: genre, core appeal, reader expectations, and creative boundaries.
- Worldbuilding: rules, factions, geography, culture, and foundational settings.
- Character design: protagonists, supporting cast, relationships, motivations, and arcs.
- Story outline: volume plans, chapter structures, and key turning points.
- Prose revision: local refinement, rewrite, and review based on existing context.
- Human confirmation: important outputs are reviewed before the workflow advances.

## Current status

This is an early release. It is available to download and try, but it is still being improved.

If you try it, feedback is welcome. Please share where you got stuck, which model provider and model you used, what you expected, and any crash logs or screenshots that could help.

## Why GitHub first

I originally considered releasing Lambfolio through the Mac App Store, but this kind of tool is built around users bringing their own model provider and API key. After looking at the distribution and in-app purchase requirements, that model would need extra product and infrastructure work to fit the store flow.

Building an in-app service layer only for distribution would also add service costs and platform fees. I would rather not pass those costs on to users, so GitHub is the simpler place to make the app available for now.

I hope it helps people write.
