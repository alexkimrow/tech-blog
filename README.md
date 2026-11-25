# Alex's Tech Notes

Keep working drafts locally in `_drafts/`. Git ignores this folder. GitHub source is public, including approved posts with future dates.

To publish, review your Markdown, then put it in `_posts/YYYY-MM-DD-your-title.md` and merge or push it to `main`.

```markdown
---
title: "What I learned about …"
description: "One sentence about the lesson."
---

Describe what you tried, what happened, and what you would do next time.
```

A push deploys posts whose dates have arrived. To schedule an approved post, give it a future date. The workflow rebuilds daily around 7:17 a.m. Chicago time. GitHub may delay scheduled runs. Use **Actions → Publish blog → Run workflow** for an on-demand rebuild.
