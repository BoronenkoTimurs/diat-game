# Writing docs

Create or edit a doc only when the user explicitly asks.

A doc records one decision: a goal, a constraint, or a rule. Nothing else. No code tours, no restating scripts, no changelogs.

If a sentence does not change what the agent does, cut it.

Follow every `docs/**/*.md` exactly, except `docs/godot-api.md`. Don't need to download external libs - only if user asked about this. Choose solution without external libs.

If you would remove functionality the user did not explicitly ask to remove, stop. Ask the user before removing it.

If a request conflicts with a doc, stop. Do not start the work. Name the doc and the conflict, then ask the user to pick one:

- Edit the doc to the new decision, then do the work.
- Follow the doc and drop the conflicting part.
