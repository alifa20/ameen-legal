# ameen-legal

Public Privacy Policy, Terms of Use and Support pages for the Ameen: Daily Quran Reflection iOS app, served with GitHub Pages.

- `privacy/` — Privacy Policy (App Store Connect "Privacy Policy URL", in-app paywall link)
- `terms/` — Terms of Use (paywall link, App Store description)
- `support/` — Support page (App Store Connect "Support URL")

Plain static HTML; no build step. The source drafts live in the private app repo under `docs/legal/`; keep both in sync.

Before publishing, every `<span class="todo">` placeholder must be replaced. Check with:

    grep -rn 'class="todo"' --include=*.html .

