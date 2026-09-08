# Apple-Kurzbefehl - Essenswochenplan und Einkaufsliste erstellen
Per Apple Kurzbefehl Erinnerungen mit Rezept .pngs erstellen

# Projektname
Wochenplan erstellen mit Einkaufsliste

# Projektziel
Automatische Erstellung eines Essensplans als Erinnerungen aus vorhandenen Rezept-PNGs, inklusive optionaler konsolidierter Einkaufsliste.

# Kurze Beschreibung des Problems
Rezepte liegen als PNG-Dateien mit definiertem Dateinamen vor. Das manuelle Anlegen von Erinnerungen für den Wochenplan sowie das Zusammenstellen einer Einkaufsliste aus mehreren Rezepten ist mit Aufwand verbunden.

# Verwendete Tools
- Apple Kurzbefehle
- Dateien-App (Ordnerauswahl)
- Erinnerungen-App
- OpenAI integriert in Kurzbefehle

# Workflow
Beschreibung der einzelnen Schritte:

1. Daten empfangen
   Nutzer wählt einen Ordner mit Rezept-PNGs aus.

2. Verarbeitung
   Der Kurzbefehl liest die Dateinamen der PNGs im gewählten Ordner aus.

3. KI-Auswertung
   Entfällt bzw. nicht zutreffend, da kein KI-Modell verwendet wird.

4. Speicherung
   Für jede Datei wird eine Erinnerung erstellt, das jeweilige Rezept-PNG wird als Anhang hinterlegt.

5. Einkaufsliste
   Optional erstellt der Kurzbefehl zusätzlich eine konsolidierte Einkaufsliste aus den ausgewählten Rezepten.

# Screenshots
Dateien in einem Ordner. Alle Mahlzeiten müssen als png Datei mit Zutatenliste in einem Ordner abgelegt werden.

<img width="660" height="352" alt="Bildschirmfoto 2026-09-08 um 10 49 33" src="https://github.com/user-attachments/assets/7f9adc6f-7667-4ca5-8a53-8a5634191620" />

Angestrebtes Rezeptformat:
<img width="282" height="739" alt="Bildschirmfoto 2026-09-08 um 11 22 56" src="https://github.com/user-attachments/assets/92947af5-f3ee-4a76-a6d6-e68e447d1a29" />

# Herausforderungen
Dateien müssen richtig benannt sein:
Wochentag in Zahl.Mahlzeit in Zahl Wochentag in Kurzform Mahlzeit in Kurzform
"1...7"."1 2 3" "Mo-Fr" "F-M-A"
Montag Frühstück - Dateiname: 1.1. MO F
Dienstag Mittag - Dateiname: 2.2 Di M
Mittwoch Abendessen - Dateiname: 3.3 Mi A

# Lernerfahrungen
Was wurde gelernt?
