# Project site (static, no build step)

Files: `index.html` (all HTML + inline CSS), `favicon.svg`. Open `index.html` in a browser to preview.

## Before publishing

1. **Project name: "Tessera" (model "Tessera-10B").** It appears only as plain text. To rename later:
   `sed -i 's/Tessera/NewName/g' index.html`
   (macOS: `sed -i '' 's/Tessera/NewName/g' index.html`)
   Note: other unrelated projects also use "Tessera" (e.g. Cambridge's TESSERA Earth-observation model and a few small Hugging Face models).
   When publishing weights, use the full name "Tessera-10B" under your own Hugging Face account to avoid confusion.
2. **About me**: the bio is filled in (first person). Optionally add links (GitHub, Hugging Face) there.
3. **Set up the contact mailbox** `hello@algebralearningmathonine.onl`. It does not exist yet.
   Porkbun's free email forwarding can receive mail, but replies come from your personal address.
   Google for Startups wants an application email on the same domain as the website, so a real hosted mailbox is safer.
   Note: the program's free Google Workspace perk requires the domain to have had no paid Workspace plan within 31 days of applying.
4. Optional: add a 1200x630 `og-image.png` and uncomment the `og:image` meta tag.
5. Keep every claim true. Mark anything not yet done as "planned".

`preview-desktop.png` / `preview-mobile.png` are local previews and do not need to be deployed.
