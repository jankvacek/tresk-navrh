# Stavebniny Tresk — náhled nového webu

Zdrojové soubory pro náhled modernější verze webu [tresk.eu](https://www.tresk.eu/stavebniny-258/), se zachovanou původní barevnou paletou (`#009c9e`, `#006061`, `#f7941e`).

## Struktura

- `build_tresk.py` — generátor: obsahuje sdílené CSS a obsah všech stránek, vygeneruje 5 hotových HTML souborů do `pages/`
- `pages/tresk-domu.html` — Domů
- `pages/tresk-sortiment.html` — Sortiment
- `pages/tresk-reference.html` — Reference
- `pages/tresk-ke-stazeni.html` — Ke stažení
- `pages/tresk-kontakt.html` — Kontakt

Každý HTML soubor je samostatný (inline CSS/JS), takže jde otevřít přímo v prohlížeči bez buildu.

## Živé náhledy

- [Domů](https://claude.ai/code/artifact/1379dba2-f445-4ca3-9229-2a50f70ef1e0)
- [Sortiment](https://claude.ai/code/artifact/427cf426-0f5a-4c02-b898-4fcac4287515)
- [Reference](https://claude.ai/code/artifact/439da750-a748-4ae8-ae62-19156b16e2c1)
- [Ke stažení](https://claude.ai/code/artifact/78bd708f-d789-4d1b-919a-80f3db8c94f4)
- [Kontakt](https://claude.ai/code/artifact/49734b7d-6d98-40c8-989e-ae01d1c7a808)

## Co chybí pro ostrou verzi

- Skutečné fotky (hero, galerie referencí)
- Reálné PDF na stránce Ke stažení
- Napojení poptávkového formuláře na e-mail
- Vložená mapa na Kontaktu
