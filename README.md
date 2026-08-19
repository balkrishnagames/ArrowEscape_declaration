# Arrow Escape — Legal & Support

Public legal and support pages for **Arrow Escape** (`com.balkrishnaenterprise.arrowescape`),
published by Balkrishna Enterprise.

| Page | File |
|---|---|
| Landing | `index.html` |
| Privacy Policy | `privacy-policy.html` |
| Terms of Service | `terms-of-service.html` |
| Support / FAQ | `support.html` |

## Publishing these pages

These are plain HTML files intended to be served by **GitHub Pages**.

1. Push this repository to `https://github.com/balkrishnagames/ArrowEscape_declaration`.
2. Make the repository **Public** (Settings → General → Danger Zone → Change visibility).
3. Enable Pages: **Settings → Pages → Source: Deploy from a branch → Branch: `main` / root → Save**.
4. Wait for the first deploy, then confirm these URLs load in a browser:

   - `https://balkrishnagames.github.io/ArrowEscape_declaration/`
   - `https://balkrishnagames.github.io/ArrowEscape_declaration/privacy-policy.html`
   - `https://balkrishnagames.github.io/ArrowEscape_declaration/terms-of-service.html`
   - `https://balkrishnagames.github.io/ArrowEscape_declaration/support.html`

The privacy policy URL must be reachable publicly (no login) before Google Play will approve the app.
The same URL is also linked from the game's **Settings → Privacy Policy** row.

`.nojekyll` is present so GitHub Pages serves these files as-is rather than processing them through
Jekyll.

## Keeping the policy accurate

The privacy policy describes the SDKs actually shipped in the app (Google AdMob, Google Play Billing
via Unity IAP, and Firebase). **If you add or remove a data-collecting SDK, update
`privacy-policy.html` to match** — a policy that does not reflect the app's real behaviour is itself a
Play Store policy violation, and it must also stay consistent with the Data Safety form you fill in on
the Play Console.

These documents were prepared as a practical starting point and are not legal advice. If you operate
at scale or in regulated markets, have a professional review them.
