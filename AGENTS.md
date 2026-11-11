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

## Profile and Publication Preferences
- Ningxin Su's publications page bolds Ningxin's name and underlines advised students' names. On September 25, 2026, Ningxin explicitly confirmed that Shuaijun Liu, Feiyang You, Chengyu Wu, Shuyang Hao, Chenglong Zhang, and Xingwei Chen are Ningxin's students.
- On September 25, 2026, Ningxin reported three accepted NeurIPS 2026 papers: “Beyond Appearance Shifts: Task-Semantic Action Calibration for VLA Models,” “Toward Efficient Reasoning of Large Language Models via Latent Concept-Pyramid Modeling,” and “Patch4Patch: Restoring Structural Connectivity in Patch-based Vision Encoders.” Titles and author order are recorded in `content/publications.md`; paper links are omitted for now as requested.
- Ningxin confirmed corresponding authorship for the NeurIPS 2026 papers “Beyond Appearance Shifts: Task-Semantic Action Calibration for VLA Models” and “Toward Efficient Reasoning of Large Language Models via Latent Concept-Pyramid Modeling”; mark Ningxin’s name with `<sup>*</sup>` in those entries. Ningxin is not a corresponding author of “Patch4Patch: Restoring Structural Connectivity in Patch-based Vision Encoders.”

## Profile and Professional Service Preferences
- On November 11, 2026, Ningxin requested that the conference service entries in `content/professional_services.md` be grouped by year and include conference locations. Use descending year headings and split entries covering multiple years into the relevant years.
- The existing professional service profile records Ningxin as General Co-Chairs of the INFOCOM EIN Workshop 2027 and Organizing Committee Member of the INFOCOM EIN Workshop 2026.
- In 2026, Ningxin is a panellist on “Agentic AI at the Wireless Edge” at IEEE MASS; a TPC member for ACM WWW, ACM MobiHoc, IEEE MASS, and IEEE ICPADS; and a Session Chair for IEEE/ACM IWQoS and IEEE MASS.
- Ningxin is a TPC member for IEEE ICPADS 2025, Web Chair for IEEE MetaCom 2024 and 2025, and an Artifacts Evaluation Committee Member for Middleware 2024. The page also lists reviewing for ICRL (as currently spelled on the page), ICML, NeurIPS, INFOCOM, ICRA, IROS, IEEE/ACM Transactions on Networking, IEEE Journal on Selected Areas in Communications, IEEE Transactions on Parallel and Distributed Systems, and IEEE Transactions on Dependable and Secure Computing.
