---
description: Follow project docs and look up one Godot API class page
alwaysApply: true
---

Before changing the project, read every docs/**/*.md except docs/godot-api.md, and follow them.
Write or edit docs only when the user asks. How: docs/writing.md.
If a request conflicts with a doc, stop and ask: update that doc, or follow it.

Never read docs/godot-api.md whole. It is the Godot Engine 4.7 class reference. A page starts at a heading `# class_<slug>` and ends at the next `# class_` heading.
A docs URL maps to that heading. Take the file name, drop `.html`, and use it as written in lowercase. `class_animation.html` is the heading `# class_animation`. `%40` in a URL is `@`, so `class_%40gdscript.html` is `# class_@gdscript`.
Search that exact heading line only, then read until the next `# class_` heading. Do not search a bare name. Other pages mention it and will flood context.
