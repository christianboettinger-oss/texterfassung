# AMZMANAGER Texterfassung

Erfassungsmaske für Amazon-Verkaufstexte. Läuft vollständig im Browser, es werden keine Daten hochgeladen.

**Maske öffnen:** https://christianboettinger-oss.github.io/texterfassung/

## Einmalig einrichten (nur Team)

1. Skill-Datei `amazon-verkaufstexte-web.skill` intern bei Christian anfordern (liegt nicht in diesem Repository).
2. In Claude installieren: Einstellungen → Skills → Skill hochladen → Datei auswählen.
3. Link oben als Lesezeichen speichern.

## Ablauf je Produkt (Ziel: unter 10 Minuten)

1. Maske öffnen, Marke, Kurzname und Produktart eintragen.
2. „Besteht bereits Amazon-Content?“ wählen und die Texte einfügen (Amazon-Listing bzw. Website).
3. Optional, aber empfohlen: Zielgruppe/USP, Rezensionen, Suchergebnisseite, Keyword-Export, Wettbewerber, Bilder.
4. „Paket erzeugen“ – das ZIP landet im Download-Ordner.
5. ZIP in Claude ziehen: „Hier ist das Texterfassungspaket, bitte die Verkaufstexte erstellen.“
6. Ergebnis: Word-Dokument mit Kurzbewertung, zwei Titelvarianten, Highlights, Bullets, Beschreibung, Backend, offenen Fragen und Prüfprotokoll.

## Hinweise

- Bei Lebensmitteln/NEM immer die Nährwerte je Tagesdosis (mg/µg) mitgeben – sonst keine gesundheitsbezogenen Angaben.
- Produktname als Kurzname, nicht den Amazon-Titel.
- Fragen und Änderungswünsche an Christian Böttinger.
