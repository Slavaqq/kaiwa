[Otevřít web – 日本語の会話](https://slavaqq.github.io/kaiwa/)

# 日本語の会話

Statický web sestavovaný z Markdownu pomocí Jekyllu na GitHub Pages.

## Úprava zápisu

Otevři `posts/2026-11-02.md` a klikni na tužku (Edit).

- `title`: japonský nadpis stránky, odkaz v přehledu i název záložky.
- `conversation_date`: datum konverzace ve formátu RRRR-MM-DD.
- `note`: nepovinná poznámka pod nadpisem; prázdný řetězec ji skryje.
- `permalink`: stálá adresa zápisu; bez důvodu ji neměň.
- Pod druhým `---` je obsah v Markdownu. `##` označuje kategorii a `###` podskupinu.

Nový zápis lze přidat zkopírováním souboru a úpravou data, titulku a permalinku. Přehled na úvodní stránce se vytváří automaticky podle data konverzace.

Po uložení do větve `main` GitHub Pages automaticky přegeneruje web. V repozitáři se neukládá vygenerované HTML; `_layouts/` obsahuje pouze společné šablony a `assets/style.css` vzhled. Web nepoužívá JavaScript.

Současný zápis je testovací obsah. Původní osobní web není tímto repozitářem upravován.
