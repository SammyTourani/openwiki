---
"openwiki": patch
---

Fix concurrent tool calls on the same wiki page corrupting it, which could leave stale trailing text, drop an edit, or leave a page with only front matter.
