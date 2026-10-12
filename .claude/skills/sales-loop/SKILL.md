---
name: sales-loop
description: Zielkunden recherchieren, nachvollziehbar priorisieren und Outreach-Entwürfe vorbereiten.
argument-hint: "[Angebot / Zielgruppe / Region / Anzahl Leads]"
disable-model-invocation: true
---

Führe einen **Sales-Opportunity-Loop** für **$ARGUMENTS** aus.

1. Leite ein Ideal Customer Profile inklusive Ausschlusskriterien und relevantem Bedarf ab.
2. Delegiere Marktrecherche an `market-researcher`. Fordere überprüfbare Quellen, konkretes Datum/Stand und Beschreibung echter Kaufsignale, keine erfundenen Leads.
3. Delegiere Qualifikation an `sales-agent`. Bevorzugt weniger, gut belegte Unternehmen statt Masse. Bewertungsraster: Fit 0–5, Bedarf 0–5, Timing 0–5, Erreichbarkeit 0–5 plus Unsicherheitsflag.
4. Verifiziere als Orchestrator für die Top-Kandidaten die Ausgangsbehauptungen. Schicke maximal einmal für gezielte Nachrecherche zurück: **höchstens 2 Durchläufe**.
5. Lass individuelle Nachrichtenvorschläge und einen nächsten Schritt erstellen, aber **keine E-Mails/Nachrichten versenden, keine personenbezogenen Daten unzulässig sammeln und keine Kontakte ungeprüft ins CRM übernehmen**. Rechtliche Kanal-/Einwilligungsfragen klären lassen.
6. Liefere eine priorisierte Lead-Tabelle mit Quellen und Zeitpunkt, Outreach-Entwürfe, Confidence und Freigabepunkte.
