---
name: design-loop
description: Web- oder App-Design erstellen und mit Responsive-, UX- und QA-Checks verbessern.
argument-hint: "[Seite / Screen / Zielgruppe / Designziel]"
disable-model-invocation: true
---

Führe einen kontrollierten **Design-Loop** für **$ARGUMENTS** durch.

1. Prüfe Produktkontext und existierende Designkomponenten. Definiere Nutzerversprechen, Zielaktion, 3–6 visuelle/UX-Akzeptanzkriterien und Zielgrößen für mindestens Mobil + Desktop.
2. Delegiere Konzept und gegebenenfalls UI-Implementierung an `ui-ux-designer`.
3. Delegiere ein unabhängiges Review an `qa-reviewer`: Usability, Navigation, Responsive-Verhalten, Tastaturbedienung, Kontrast, Zustände und Regressionen.
4. Wenn Browser/Playwright oder visuelle Vorschau zur Verfügung stehen, echte Screenshots prüfen. Wenn nicht, den visuellen Teil als **nicht verifiziert** kennzeichnen und eine manuelle Checkliste liefern.
5. Gib konkrete Korrekturpunkte mit Severity und Fundort an Designer zurück. Maximal 3 Design/Review-Runden. Abbruch bei wiederholt identischem Befund.
6. Liefere Designentscheidungen, Dateien/Artefakte, geprüfte Ansichten, QA-Ergebnis und noch notwendige Freigabe. **Nicht selbst veröffentlichen.**
