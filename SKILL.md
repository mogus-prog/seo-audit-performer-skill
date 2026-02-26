---
name: seo-audit-performer
description: SEO Audit Performer workflow automation skill. Use when a user needs SEO Audit Performer tasks planned, generated, analyzed, or reported with repeatable outputs, templates, and lightweight local scripts.
---

# SEO Audit Performer

Follow this workflow:

1. Read relevant input files from       .
2. Run  with a short task prompt and output directory.
3. Verify output artifacts in the chosen output folder.
4. Iterate prompt parameters for improved quality.

## Command

```bash
bash scripts/run.sh --task "example task" --outdir ../../tmp/seo-audit-performer
```

## Notes

- Keep runs deterministic and timestamped.
- Save generated artifacts to the target outdir.
- Use  as a starter template.
