# SEO Blog Strategy — Ahrefs and MicroConf

A Codex skill for auditing existing blogs and planning the structure of new posts or a new blog, based on the SEO and AI-search guidance in these videos:

- [Ahrefs AEO course — Sam Oh](https://www.youtube.com/watch?v=uza9GX0E2mw)
- [MicroConf lightning talk — Jesse of DropInBlog](https://www.youtube.com/watch?v=Nyq38GvRm44)

The skill combines the overlapping lessons into a practical workflow for customer-relevant topics, search intent, answer-first writing, clear headings, useful evidence, brand clarity, content updates, and AI-search visibility.

## What it does

- **Audit existing content:** Review an individual article or a blog, identify important gaps, and prioritize specific improvements.
- **Structure new posts:** Develop content briefs, answer-first openings, headings, evidence requirements, internal-link suggestions, and appropriate product next steps.
- **Plan a new blog:** Organize useful topic families and prioritize articles connected to the intended audience and product.

It distinguishes observed facts from assumptions, avoids invented keyword metrics and ranking promises, and works without an Ahrefs subscription. It is particularly suited to software and app founders with waitlist or self-serve signup journeys.

## Use

Place the repository contents in a personal Codex skill folder named `seo-blog-strategy`, then invoke it explicitly:

```text
Use $seo-blog-strategy to audit my blog: [URL]
```

```text
Use $seo-blog-strategy to create a brief and outline for a new article
about [topic] for [audience].
```

## Included files

- [SKILL.md](SKILL.md) — Audit, research, and content-planning workflows.
- [references/seo-aeo-playbook.md](references/seo-aeo-playbook.md) — Combined October 2026 playbook with source links and labeled technical updates.
- [references/audit-and-brief.md](references/audit-and-brief.md) — Audit criteria and reusable content-brief templates.
- [agents/openai.yaml](agents/openai.yaml) — Skill display and invocation settings.

This is an independent synthesis of the supplied video transcripts, with editorial templates and separately labeled technical checks. It is not affiliated with or endorsed by Ahrefs, MicroConf, or the speakers. The original videos are credited above.
