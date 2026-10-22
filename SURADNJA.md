# SURADNJA — napomena za agente (Kimi + Claude) i vlasnika

**Vlasnik:** zg2000fs. Na projektima rade dva AI agenta: **Claude** (TechPuls) i **Kimi** (Osobni Finvest). Ovaj dokument je zajednička točka komunikacije — ako nešto mijenjaš izvan svog područja, ostavi zapis ovdje (datum + potpis + kratko što i zašto).

## Arhitektura (provjereno 22.10.2026, Kimi)

| URL | Izvor | Vlasnik sadržaja |
|---|---|---|
| `https://zg2000fs.github.io/` (root hub) | ovaj repozitorij, `index.html` u rootu | **Kimi** (uz dogovor) |
| `https://zg2000fs.github.io/techpuls/` | **zaseban repozitorij `zg2000fs/techpuls`** (GitHub Pages project site) | **Claude** |
| `https://zg2000fs.github.io/osobnifinvest/` | **zaseban repozitorij `zg2000fs/osobnifinvest`** (GitHub Pages project site) | **Kimi** |
| `robots.txt`, `yandex_*.html`, Google/Bing meta oznake u root `index.html` | ovaj repozitorij | **zajedničko — NE DIRATI bez dogovora** (verifikacije ovise o tome) |

## Pravila

1. **Svoje mape slobodno, tuđe nikako.** Oba projekta imaju vlastiti repozitorij — Kimi radi isključivo u `zg2000fs/osobnifinvest`, Claude isključivo u `zg2000fs/techpuls`.
2. **Root `index.html`** (hub s dvije kartice) mijenja se samo uz zapis u ovoj datoteci. Google/Bing meta oznake u `<head>` moraju ostati netaknute.
3. **Uvijek `git pull` prije rada i prije `push`** — moguće su promjene iz drugog klona (vlasnik ima više lokalnih kopija na računalu).
4. Mali, jasno imenovani commiti; ništa destruktivno (force push, brisanje tuđih datoteka) bez izričitog odobrenja vlasnika.
5. Ako ti treba promjena na tuđem teritoriju — zapiši zahtjev ovdje pod „Zahtjevi", ne radi sam.

## Zahtjevi / bilješke

- **22.10.2026 (Kimi):** MIGRACIJA — Osobni Finvest je iz mape `osobnifinvest/` u ovom repozitoriju preseljen u vlastiti repozitorij `zg2000fs/osobnifinvest` (isti obrazac kao TechPuls). URL ostaje isti. Mapa u ovom repozitoriju uklonjena; root hub i poveznice nepromijenjeni.
- **22.10.2026 (Kimi):** root je sada hub s dvije kartice (TechPuls / Osobni Finvest). Prethodno je bio instant-redirect na /techpuls/ — vlasnik je odobrio hub. Meta oznake i robots.txt netaknuti. Ako TechPuls želi dodatni link ili promjenu opisa na hubu, slobodno zapisati ovdje.
- **22.10.2026 (Kimi):** za Osobni Finvest kanal planira se YouTube lansiranje 2.11.2026. Ako TechPuls želi cross-promociju, kontakt preko vlasnika.
