# Repository Guidelines

## Project Structure & Module Organization
- `config.toml` defines site settings, menus, and theme configuration.
- `content/` holds site pages written in Markdown with TOML front matter (`+++`).
  - `content/_index.md` is the homepage and uses the `rawhtml` shortcode for custom HTML/CSS.
  - `content/assets/` stores PDFs and images referenced by pages.
- `layouts/shortcodes/` contains custom shortcodes such as `rawhtml.html`.
- `themes/` contains the Hugo theme (`hello-friend`).

## Build, Test, and Development Commands
- `hugo server` — runs the local development server (default at `http://localhost:1313/`).
- `hugo` — builds the static site into `public/` (generated output; not tracked here).

## Coding Style & Naming Conventions
- Content uses Markdown with TOML front matter (`+++` blocks).
- Keep filenames lowercase with underscores for multiword pages (e.g., `professional_services.md`).
- Use the `rawhtml` shortcode sparingly for custom layout and keep CSS scoped to avoid global clashes.
- Maintain 2-space indentation for inline HTML/CSS blocks inside content files.

## Testing Guidelines
- No automated test framework is configured.
- Validate changes by running `hugo server` and reviewing affected pages in the browser.

## Commit & Pull Request Guidelines
- Commit messages are short, sentence-case updates (e.g., “Updated index by adding recruiting info.”).
- Prefer one logical change per commit; mention the page or asset updated.
- Pull requests should describe the change, list affected pages, and include screenshots for visual updates.

## Security & Configuration Tips
- Avoid committing generated output (`public/`) or local editor artifacts.
- Keep large assets (PDFs/images) in `content/assets/` and reference them from content.
