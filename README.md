# Café Da Noi – Website

## Status
Erste Version live auf GitHub Pages (siehe unten). Speisekarte, Fotos und Öffnungszeiten fehlen noch.

## Quelle für Kontaktdaten
Telefon, E-Mail und Service-Infos wurden aus der bestehenden temporären Seite übernommen: https://da-noi-tino-e-toni.eatbu.com (Öffnungszeiten und Speisekarte dort leider nur dynamisch geladen und nicht auslesbar).

## Entscheidungen
- **Pflege:** Statische Seite, Inhalte werden vom Entwickler gepflegt (kein CMS)
- **Sprache:** Erstmal nur Deutsch
- **Funktionen:** Info-Seite (Speisekarte, Standort, Öffnungszeiten, Kontakt) + Online-Tischreservierung
- **Reservierungs-Workflow:**
  1. Kunde sendet Reservierungsanfrage über Formular (Name, Personenzahl, Datum/Uhrzeit, Anmerkungen)
  2. Anfrage landet beim Besitzer
  3. Besitzer bestätigt die Reservierung
  4. Kunde erhält automatisch eine Bestätigungsmail
- **Hosting/Domain:** Noch offen, wird zu einem späteren Zeitpunkt festgelegt
- **Versionierung:** Wird später auf GitHub gepusht, sobald ein erstes Mockup steht

## Offene Punkte
- [x] Logo abgelegt in `public/assets/logo/`
- [ ] Speisekarte ablegen in `public/assets/speisekarte/`
- [ ] Fotos ablegen in `public/assets/fotos/`
- [x] Adresse (Glißmannweg 5, 22457 Hamburg)
- [x] Telefonnummer, E-Mail (aus temporärer Seite übernommen)
- [ ] Öffnungszeiten (auf temporärer Seite nicht auslesbar, bitte von Tino/Toni erfragen)
- [ ] Technischer Unterbau für Reservierung (Formular + Backend für Bestätigungs-Workflow + E-Mail-Versand)

## Hosting
- Repository: public auf GitHub, damit GitHub Pages kostenlos genutzt werden kann
- Live-Vorschau: GitHub Pages aus Branch `main`, Ordner `/ (root)` — URL folgt nach Aktivierung in den Repo-Settings

## Ordnerstruktur
```
public/assets/logo/         Logo-Dateien
public/assets/fotos/        Fotos vom Restaurant/Gerichten
public/assets/speisekarte/  Speisekarte (PDF/Fotos/Text)
```
