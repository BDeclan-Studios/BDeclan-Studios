# BDStudios: support & privacy pages

Support and privacy pages for every BDStudios app, published with GitHub Pages from `main`.

**Site:** https://bdeclan-studios.github.io/BDeclan-Studios/

## App links

Paste these into App Store Connect: **Support URL** under App Information, and **Privacy Policy URL** under App Privacy.

| App | Support URL | Privacy Policy URL |
| --- | --- | --- |
| Cookie Bakery | https://bdeclan-studios.github.io/BDeclan-Studios/cookie-bakery/ | https://bdeclan-studios.github.io/BDeclan-Studios/cookie-bakery/#privacy |
| Game Den | https://bdeclan-studios.github.io/BDeclan-Studios/game-den/ | https://bdeclan-studios.github.io/BDeclan-Studios/game-den/#privacy |
| Mind Age | https://bdeclan-studios.github.io/BDeclan-Studios/mind-age/ | https://bdeclan-studios.github.io/BDeclan-Studios/mind-age/#privacy |
| Save Point | https://bdeclan-studios.github.io/BDeclan-Studios/savepoint/ | https://bdeclan-studios.github.io/BDeclan-Studios/savepoint/#privacy |
| Stack Café | https://bdeclan-studios.github.io/BDeclan-Studios/stack-cafe/ | https://bdeclan-studios.github.io/BDeclan-Studios/stack-cafe/#privacy |
| Vault Duo | https://bdeclan-studios.github.io/BDeclan-Studios/vault-duo/ | https://bdeclan-studios.github.io/BDeclan-Studios/vault-duo/#privacy |

Studio-wide contact and privacy: https://bdeclan-studios.github.io/BDeclan-Studios/

## Studio home page and app-ads.txt

The studio home page and `app-ads.txt` live in a separate repo, [bdeclan-studios.github.io](https://github.com/BDeclan-Studios/bdeclan-studios.github.io), because AdMob only reads `app-ads.txt` from the root of the domain:

- Home page: https://bdeclan-studios.github.io/
- app-ads.txt: https://bdeclan-studios.github.io/app-ads.txt

Keep the file there; a copy in this repo would sit under `/BDeclan-Studios/` and AdMob wouldn't find it.

## Adding a new app

1. Copy an existing app's folder, e.g. `mind-age/`, to a new folder named after the app (lowercase, hyphens).
2. Update the page text, and the colours and fonts in its `<style>` block to match the app's `Theme.swift`.
3. Add a card for it on the home page (`index.html`) and a row in the table above.

Changes go live a minute or two after they reach `main`.
