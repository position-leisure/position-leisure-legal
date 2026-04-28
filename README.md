# position-leisure-legal

Legal documents for **Position: Leisure**, an AI-powered job search and application tracking platform operated by **AlgoAxiom LLC**.

This repository serves as the public source of truth for Position: Leisure's compliance documents. The documents are published as a [Jekyll](https://jekyllrb.com/) site via GitHub Pages.

## Documents

- **[Privacy Policy](https://position-leisure.github.io/position-leisure-legal/privacy-policy.html)** — what data we collect, how we use it, the third-party services involved (Anthropic, RapidAPI/JSearch, SendGrid, Microsoft Azure, Google OAuth, Chrome extension data handling), and user rights regarding their data.
- **[Terms of Service](https://position-leisure.github.io/position-leisure-legal/terms-of-service.html)** — usage terms, account responsibilities, prohibited conduct, disclaimers, and limitations of liability.

## Hosted at

The live site lives at **<https://position-leisure.github.io/position-leisure-legal/>** — served from this repo's `main` branch root via GitHub Pages with the [`jekyll-theme-cayman`](https://github.com/pages-themes/cayman) theme.

The Privacy Policy URL is also referenced in:
- The Position: Leisure Chrome extension's listing (Chrome Web Store)
- The application UI (Settings page footer / signup flow)
- Outbound email footers (SendGrid templates)

## Updating

To update a document:

1. Edit the relevant `.md` file (`privacy-policy.md` or `terms-of-service.md`).
2. Update the **Effective Date** at the top of the modified document.
3. Keep the YAML frontmatter (the `---` block at the very top of each file) — it's required for Jekyll to render the file with the theme.
4. Commit and push to `main`.
5. GitHub Pages auto-rebuilds within 1-3 minutes. Confirm the deploy via the **Actions** tab on GitHub.

## Local preview (optional)

```bash
gem install bundler jekyll
bundle init
bundle add jekyll-theme-cayman
bundle exec jekyll serve
# → http://localhost:4000
```

## Contact

For questions about these documents or data handling:

**AlgoAxiom LLC**
Steven Cantwell
4601 E. Douglas Ave. STE 150
Wichita, KS 67218
<algoaxiom.steve@gmail.com>
