# Contributing to Dot Documentation

We welcome corrections, clearer explanations, examples, and translations. Issues and pull requests may be written in English, Simplified Chinese, or Japanese. Use the repository templates and keep each contribution focused on one topic.

## Find the right place

- `zh-Hans-CN/`, `en-US/`, and `ja-JP/` contain the corresponding language editions.
- Pages use MDX with `title` and `description` frontmatter. A section's introduction belongs in `index.mdx`.
- `meta.json` controls navigation. Update it when adding or moving pages, and preserve existing URLs where possible.
- Product listings follow release order: Quote/0, Rand/0, Read/0. Follow the surrounding page's product naming.

## Write and edit

Read the closest existing page before creating a new one. Describe what the reader can do, then give the instructions or technical details they need. Support specifications, compatibility statements, and API behavior with public sources or a clearly described observation. Do not invent features or promises.

Reuse existing MDX components such as `Cards`, `Card`, `Callout`, `CustomCloudImage`, and `GithubInfo`. Use `GithubInfo` for a repository entry instead of creating a new card style. Use public assets you have permission to share, include meaningful image descriptions, and avoid oversized images. Do not publish local filesystem paths or private asset URLs.

Update corresponding languages when practical. Single-language contributions are welcome: identify which translations still need attention in the PR. Keep paths and navigation consistent across the editions you change.

## Before opening a pull request

1. Review the diff for unrelated changes, broken links, and accidental formatting changes.
2. Check the affected MDX and navigation. If you have access to the website preview, inspect the page and include a screenshot for layout changes.
3. Describe your sources, changed languages, and checks actually performed. If you could not preview the page, say so. Text-only changes do not require a test run.
4. Remove credentials, device identifiers, private links, and personal information from examples and screenshots.

This repository contains documentation content, not a standalone Next.js application. Do not add build scaffolding just to preview a text change.

## Rights and attribution

Submit material you have the right to share under the repository's [CC BY-NC-SA 4.0 license](LICENSE). Preserve source attribution and identify third-party material and its applicable license. Do not copy proprietary manuals or images without permission.

## Questions and security

Use [Support](SUPPORT.md) for documentation and product-help routes. Report vulnerabilities privately through [Security](SECURITY.md), not in a public issue. Keep discussions respectful, specific, and focused on the contribution.
