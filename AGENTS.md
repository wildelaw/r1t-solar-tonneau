# AGENTS.md

Documentation-only site published with Jekyll on GitHub Pages. No application code, tests, or lint config.

## Architecture

- **Site generator:** Jekyll 3.10 (the version GitHub Pages runs — NOT Jekyll 4). Theme: `minima`.
- **Pages source:** GitHub Actions (`.github/workflows/jekyll.yml`), *not* "Deploy from branch". The workflow uses `configure-pages@v5` with `enablement: true` so it auto-creates the Pages site on first run.
- **Site URL:** `https://wildelaw.github.io/r1t-solar-tonneau/` — `baseurl: "/r1t-solar-tonneau"` in `_config.yml` is mandatory (project Pages path).

## Critical Jekyll 3 gotcha

`{% link foo.md %}` does **not** auto-prepend `baseurl` in Jekyll 3. All inline links in markdown must be written as:

```
[Label]({{ site.baseurl }}{% link path/to/page.md %})
```

The `_includes/figure.html` include uses `relative_url` for image paths, so images work correctly without wrapping — do not "fix" image refs by adding `site.baseurl` manually inside the include call.

## Content layout

- `index.md` — project home (layout: home)
- `materials.md`, `pro-tips.md` — standalone pages
- `build/phase-1-*.md` … `phase-5-*.md` — build log, one page per phase
- `_includes/figure.html` — reusable captioned `<figure>` include; call with `image="/Images/..."` (absolute path, `relative_url` rewrites it) and `caption="..."`
- `Docs/Directions.md` — canonical source document, **excluded from the Jekyll build** via `_config.yml` `exclude:`. Preserve verbatim; do not split further.
- `Images/` — build photos, named `N.N-description.jpeg` matching the phase numbering. Never move or rename.

## Adding a new page

1. Create `<slug>.md` (or `build/<slug>.md`) with front matter: `layout: page`, `title: "..."`, `nav_order: N`.
2. Add the path to `header_pages:` in `_config.yml` to surface it in the minima header nav.
3. Link to it from other pages using `{{ site.baseurl }}{% link <path>.md %}`.

## Verification

- **No local build.** System Ruby on macOS is 2.6; Jekyll needs Ruby 3+. Do not attempt `bundle install` / `jekyll serve` — it will fail on `ffi`.
- To verify: commit, `git push origin main`, watch the **Actions** tab. The workflow builds with the same image GH Pages uses, so a green build == working site.
- After the build finishes, fetch the live page and grep `href=`/`src=` to confirm paths resolve under `/r1t-solar-tonneau/`.

## Commit style

Conventional commits, lowercase scope: `docs:`, `fix:`, `ci:`. See `git log` for examples.