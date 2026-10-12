# Projektkontext und Arbeitsregeln

## Geschäftskontext
Abgeleitet aus `README.md` und `index.html`; mit (Annahme) markierte Punkte sind nicht belegt und bitte prüfen.
- Angebot: „911.exe", eine Single-Page-Memeseite rund um die Zahl 911 (Porsche 911, Notruf, Aviation-Memes). Satire/Fanprojekt, kein kommerzielles Produkt.
- ICP / Zielgruppe: Meme-affine Auto- und Luftfahrt-Fans, die humorvolle Inhalte teilen (Annahme).
- Region und Sprache: Deutsch (`lang="de"`), Fokus DACH (Annahme).
- Markenstil: Maximalismus – Neon-Gradients (hot/cyan/acid/grape), Marquees, rotierende Karten, Emoji-Konfetti, Impact- und Comic-Sans-Captions. `prefers-reduced-motion` muss respektiert bleiben.
- Produktziel: Unterhaltung und Teilbarkeit der Seite; kein Verkaufsziel (Annahme).
- KPIs: Besuche, Shares, Verweildauer (Annahme; derzeit kein Tracking vorhanden).
- Technik: Statisches `index.html` ohne Build und ohne Dependencies; so beibehalten.
- Inhaltsgrenzen: kein Bezug auf die Anschläge vom 11. September; keine Verbindung zu Porsche AG, Fluglinien oder Notrufzentralen behaupten; Hinweis auf echte Notrufnummern (112 EU / 911 US) beibehalten.

## Arbeitsprinzipien
- Beachte vorhandene Architektur, Konventionen, Designsysteme und Verträge; erfinde keinen Stack und wechsle ihn nicht ohne Begründung.
- Bei größeren Aufgaben: kurze Planung, dann ausführbare kleine Schritte mit testbaren Akzeptanzkriterien.
- Setze passende Subagents gezielt ein; der Hauptdialog verantwortet Übergaben, Freigaben und das Gesamtergebnis.
- Annahmen und unbestätigte externe Fakten ausdrücklich markieren; echte Quellen mit URL/Datum festhalten, soweit verfügbar.
- Ergebnisse müssen reproduzierbar sein: geänderte Dateien, Befehle, Tests und Einschränkungen nennen.
- Keine falschen PASS-Meldungen: fehlende Tools/Zugänge als BLOCKIERT kennzeichnen.
- Für Loops maximal 3 Iterationen bei Code/Design bzw. 2 Iterationen bei Sales/Marketing. Bei wiederholtem gleichen Fehler abbrechen und Hindernis melden.

## Sicherheits- und Freigabegrenzen
- Keine Nachrichten an Dritte, Kampagnenstarts, Zahlungsvorgänge, Produktivdeployments, Veröffentlichungen, Löschaktionen oder Massenänderungen in externen Diensten ohne explizite Freigabe.
- `.env`, Tokens, Zugangsdaten und private Kundeninformationen niemals ins Antwortprotokoll, in Commits oder in öffentliche Tools schreiben.
- Vertrauliche Informationen auf das Minimum begrenzen. Bei Outreach lokale Datenschutz- und Wettbewerbsregeln berücksichtigen.
- Ausführbare Hooks, CI-Prüfungen und Zugriffsrechte sind echte technische Schutzmechanismen; Anweisungen in diesem Dokument allein sind keine sichere Zugriffssperre.

## Softwarequalität
- Vor Änderungen relevante Dateien lesen und den Git-Status prüfen; fremde, uncommittete Änderungen nicht überschreiben.
- Ergänze angemessene Tests. Prüfe bei UI-Arbeit mobile/desktop, Fehlerzustände, Ladezustände und Tastaturbedienung.
- Nach Änderungen nur verfügbare und passende Prüfungen ausführen; Befehle und Ergebnisse dokumentieren.
- Keine überflüssigen Dependencies oder Refactorings ohne konkreten Nutzen.
