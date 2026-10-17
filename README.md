# Fawz legal (GitHub Pages)

Public privacy policy and contact information for **[Fawz](https://github.com/M-Albasti/Fawz)** — Islamic companion app (iOS, Android, desktop).

## Live site

| Page | URL |
|------|-----|
| Privacy policy | https://m-albasti.github.io/fawz-legal/privacy-policy.html |
| Home | https://m-albasti.github.io/fawz-legal/ |
| Support (App Store / Play) | https://m-albasti.github.io/fawz-legal/privacy-policy.html#contact |

Referenced from the app via `FAWZ_PRIVACY_POLICY_URL` in the main repo (`src/constants/appLegal.ts`). **Settings → Privacy policy** opens the policy; **Settings → Contact us** uses the same channels listed under `#contact` on this page.

## Contents

- **`privacy-policy.html`** — English and Arabic policy; light/dark styling via `prefers-color-scheme`
- **`index.html`** — redirects to the privacy policy

## Deployment

GitHub Pages is enabled on this repository:

- **Source:** branch `main`, folder `/` (root)
- **URL:** https://m-albasti.github.io/fawz-legal/

Push to `main` to update the live site (allow a few minutes for propagation).

## Editing

Policy changes are usually made in the main app repo under `legal/privacy-policy.html`, then copied here and pushed to `main`. Keep both copies aligned.

See also:

- [Fawz — docs/STORE_PUBLISHING.md](https://github.com/M-Albasti/Fawz/blob/develop/docs/STORE_PUBLISHING.md) (mobile stores)
- [Fawz — docs/DESKTOP_PUBLISHING.md](https://github.com/M-Albasti/Fawz/blob/develop/docs/DESKTOP_PUBLISHING.md) (desktop)

## Operator

Mahmoud Al-Basti · Fawz app · `com.albasti.fawz` (mobile) · `com.fawz.desktop` (desktop)
