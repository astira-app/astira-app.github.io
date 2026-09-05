# Astira – Website

Die öffentliche Website der Android-App **Astira** (interaktive
Echtzeit-Sternenkarte), ausgeliefert über GitHub Pages.

- 🌐 Startseite: https://astira-app.github.io/
- 🌘 Nächste Finsternis: https://astira-app.github.io/eclipse/
- 🧭 Hilfe: https://astira-app.github.io/help/
- 📄 Datenschutzerklärung: https://astira-app.github.io/privacy/
- ⚖️ Impressum: https://astira-app.github.io/legal/
- 📱 App: https://play.google.com/store/apps/details?id=dev.astira.astira
- ✉️ Kontakt: astira.info@gmail.com

Alle Seiten gibt es in sieben Sprachen: Deutsch, English, Español, Français,
Italiano, Português (Brasil), 日本語.

This repository hosts the website for the Astira Android app.

## Nicht von Hand bearbeiten

Der Inhalt dieses Repos wird **erzeugt**. Quellen sind die Dateien der App im
Code-Repo — die Sprachdateien (`lib/l10n/app_*.arb`), die Bedien-Legende
(`lib/ui/controls_guide.dart`) und die Store-Texte
(`docs/store/play_listing.md`). Daraus baut `tools/build_website.py` die
Seiten, und `tools/publish_site.py` schiebt sie hierher. Damit kann die
veröffentlichte Fassung nicht mehr vom Text in der App abweichen.

Änderungen deshalb immer im Code-Repo vornehmen — was hier direkt bearbeitet
wird, geht bei der nächsten Veröffentlichung verloren.
