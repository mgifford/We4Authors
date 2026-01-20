# AGENTS – We4Authors Jekyll Rebuild

## Purpose
Operating notes for anyone migrating the archived accessibilitycluster.com snapshot into this Jekyll site while preserving the original mirror under `/archive/`.

## Source of truth
- Primary content: `/archive/accessibilitycluster.com_20220601/` (static Gatsby export from 2022-06-01).
- If a page is incomplete or a link is broken in the Jekyll version, inspect the matching HTML in the archive and, if needed, the Wayback Machine captures (2020–2025 range) to recover missing text or targets.

## Migration rules
- Do not delete or overwrite anything in `/archive/`.
- Archives are read-only. Do not edit, move, or regenerate files under `/archive/` unless a task explicitly calls for updating an archived copy.
- When using AI-assisted changes, ensure edits apply only to live Jekyll content; never apply automated changes to `/archive/` unless specifically requested.
- Recreate each top-level page as Markdown under the site root using `layout: default` and keep slugs stable (e.g., `/main-results/`, `/about-cluster/`, `/invitation/`).
- For subpages (e.g., `/main-results/user-needs/`), add either Markdown pages or temporary stubs that link to the archive until transcription is complete.
- Maintain navigation entries in `_data/navigation.yml`; keep the archive entry visible.
- Preserve original image alt text when present; avoid inventing alt text. If alt is empty in the source, leave it empty.

## Broken links
- When a link target 404s in the rebuilt site, first map it to the archived HTML (same path under `/archive/accessibilitycluster.com_20220601/`).
- If the target is also missing in the archive, search the Wayback Machine and update the link to the best available archived URL. Document any substitutions inline (e.g., “Recovered via web.archive.org, snapshot yyyy-mm-dd”).

## Assets
- Prefer hotlinking to existing CDN assets (Sanity URLs) as in the archive. If a CDN asset is gone, pull the file from the archive or Wayback and place it under `assets/`, updating the reference.

## Writing style
- Keep factual, neutral tone; avoid adding new claims. Note explicitly when text is reconstructed or incomplete.
- Include short callouts when content is partial or awaiting transcription.

## Accessibility
- Keep headings hierarchical (one H1 per page). Ensure link text is descriptive. Preserve meaningful alt attributes.

## QA checklist per page
- Does the slug match the archived path?
- Do nav links highlight correctly via `aria-current`? (Check `_includes/nav.html`.)
- Do internal links resolve locally? If not, add temporary archive links and a TODO marker in the page body.
- Images: working source and intentional alt text.
- Footer still references the archive and EC funding note.

## Helpful paths
- Layout: `_layouts/default.html`
- Nav include: `_includes/nav.html`
- Footer include: `_includes/footer.html`
- Styles: `assets/css/main.css`
- Nav data: `_data/navigation.yml`
- Archive root: `archive/accessibilitycluster.com_20220601/`
