# practical-classic-guitar-app-public

The public pages for **Practical Classic Guitar**, a daily practice companion for classical
guitar on iPad and iPhone: the marketing page, the support page and the privacy policy that the App Store
listing links to, in English and in Portuguese.

| Page | English | Português |
|---|---|---|
| Marketing | [`index.html`](index.html) | [`pt-br/index.html`](pt-br/index.html) |
| Support | [`support.html`](support.html) | [`pt-br/support.html`](pt-br/support.html) |
| Privacy policy | [`privacy.html`](privacy.html) | [`pt-br/privacy.html`](pt-br/privacy.html) |

The app itself is developed in a separate, private repository. This one exists only so those
URLs can be served publicly without the source being public with them.

## How it is served

GitHub Pages, deployed by `.github/workflows/static.yml` on every push to `main`. Plain HTML and
one stylesheet: no Jekyll (hence `.nojekyll`), no build step, no framework, and nothing fetched
from anywhere else.

The URLs for App Store Connect:

| Field | English (U.S.) | Portuguese (Brazil) |
|---|---|---|
| Marketing URL | `https://unnustudios.github.io/practical-classic-guitar-app-public/` | `https://unnustudios.github.io/practical-classic-guitar-app-public/pt-br/` |
| Support URL | `https://unnustudios.github.io/practical-classic-guitar-app-public/support.html` | `https://unnustudios.github.io/practical-classic-guitar-app-public/pt-br/support.html` |
| Privacy Policy URL | `https://unnustudios.github.io/practical-classic-guitar-app-public/privacy.html` | `https://unnustudios.github.io/practical-classic-guitar-app-public/pt-br/privacy.html` |

## Changing the policy

The privacy policy says what the app does, and the App Store privacy label says the same facts
in another place. **They have to agree.** The text comes from `docs/store/privacy-policy.md` and
`docs/store/support.md` in the app's repository, which follow `docs/APP-PRIVACY.md` there. The
policy is not edited here on its own: it changes when the app's handling of data changes, and
the date at the top of the page changes with it.
