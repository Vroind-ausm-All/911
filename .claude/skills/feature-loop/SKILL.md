---
name: feature-loop
description: Feature implementieren, unabhängig prüfen und bis maximal drei Durchläufe korrigieren.
argument-hint: "[Feature / Issue / Akzeptanzkriterien]"
disable-model-invocation: true
---

Führe einen kontrollierten **Development-Loop** für diese Aufgabe durch: **$ARGUMENTS**.

1. Erstelle 3–7 überprüfbare Akzeptanzkriterien, prüfe Repository-Kontext und Git-Status. Bei unklarer Produktabsicht höchstens eine notwendige Rückfrage; sonst Annahmen kennzeichnen.
2. Delegiere Implementierung an `fullstack-developer` mit Dateibereichen, Testanforderungen und Verbot von Push/Deployment.
3. Delegiere unabhängiges Read-only-Review an `qa-reviewer`. Gib ihm ursprüngliche Akzeptanzkriterien und Änderungen, ohne das Ergebnis des Entwicklers als Wahrheit zu behandeln.
4. Bei P0/P1-Fehlern: gib konkrete reproduzierbare Befunde an den Developer zurück, lasse nur betroffene Teile korrigieren und prüfe erneut. **Maximal 3 Implementierung/Review-Durchläufe insgesamt.**
5. Schleife abbrechen bei demselben Fehler nach 2 Korrekturversuchen, ungültigen Tools, fehlenden Rechten oder außergewöhnlichen Risiken. Niemals Tests durch Abschalten „reparieren“.
6. Abschließend: Dateien, ausgeführte Befehle mit Resultat, PASS/TEILWEISE/BLOCKIERT, offene Risiken und explizite Freigabeschritte nennen. **Keine Produktionsaktion.**
