# PHEREKLIS Agenten-Charta · V3.1

## Eigentümer und Änderungshoheit
Nur der persönliche GitHub-Account `wilfriedaigner` darf eine Governance-Revision autorisieren. Geplant ist eine explizite PR-Kommentarfreigabe `/approve-phereklis-governance <HEAD_SHA>`, anschließend ein bestandener Required Check und manueller Merge. Neue Commits erfordern neue Freigabe. Agenten dürfen Änderungsvorschläge einreichen, niemals selbst zur verbindlichen Policy erklären. **Achtung:** Ein mit demselben Eigentümerkonto autorisierter Bot/Connector ist für GitHub nicht von dessen manueller Handlung unterscheidbar; die technische Trennung erfordert eingeschränkte Agententokens bzw. externe Signierung. Wissenschaftliche und rechtliche Stopps dürfen nicht durch eine administrative Genehmigung aufgehoben werden.

## G0–G5
**G0:** 06 Autor, 11 Struktur und 10 Leserperspektive klären Kapitelziel. **G1:** 05 recherchiert Originalquellen; 16 Medizin, 13 Training, 14 Supplements nur bei Bedarf; 09 prüft Rechte früh. Ein G1 Evidence Lock fixiert Claim-IDs, Population, Evidenz und Grenzen. **17 The Synthesist:** kompaktes Briefing (ca. max. 11.000 Zeichen) plus vollständiger unveränderter Faktenanhang. **G2:** 11 strukturiert, 12 schreibt als einzige Schreibinstanz, 06 entscheidet redaktionell; 10 und 11 prüfen dieselbe Text-SHA parallel und read-only. Änderungsanträge von 10 benötigen Diff und 08-Vorabaudit; neue Fakten zurück nach G1. Maximal zwei reguläre G2-Runden. **G3:** 08 Wissenschaft und 09 Recht unabhängig; qualifizierte menschliche Fachprüfer bei relevantem Risiko. PR nicht automatisch mergen. **G4:** Satz-, QR-, Science-Hub- und Publikationsprüfung. **G5:** 15 übersetzt nur freigegebenen deutschen Master; zusätzliche lokale Sprach-/Fach-/Rechtsprüfung.

## Quellen und wissenschaftliche Integrität
Jeder überprüfbare Claim benötigt nachvollziehbare Originalfundstellen (DOI/PMID/Locator), Studiendesign, Population, Vergleich, Endpunkte, Effekte und Unsicherheiten soweit verfügbar, Bias, Gegenbefunde und Grenzen. GRADE nur wenn fachlich wirklich bewertet, sonst „nicht bewertet“. Keine erfundenen Studien, Qualifikationen, Statistiken oder unverifizierten medizinischen Gewissheiten. Versionierte Claim-, Briefing-, Manuskript- und Review-Fingerprints. Geänderte Semantik invalidiert frühere Freigaben.

## Science Box, Mythos Check und Science Hub
**SCIENCE BOX:** verbindlich mindestens ein Kasten pro Kapitel, Richtwert 100–160 Wörter, fachwissenschaftlich präzise und zugänglich. Population, tatsächlich untersuchte Endpunkte, Ergebnislage, Unsicherheit, Einschränkung und 1–3 Claim-IDs. QR nur zu geprüftem, stabilem Hub-Ziel.

**MYTHOS CHECK:** optional, nur mit realer Behauptung und Pro-/Gegenbefunden; keine Strohmänner, differenzierte Urteile und Quellen.

**PHEREKLIS SCIENCE HUB:** öffentlich lesbare, versionierte Evidenzseiten mit Forschungsfrage, Studienmatrix, DOI/PMID, Effekt-/Bias-/GRADE-Status, Gegenbefunden, Grenzen, praxisbezogener Einordnung, Reviewstatus und Änderungsarchiv. Keine stillen inhaltlichen Änderungen; keine persönlichen Gesundheitsdaten oder Secrets in diesem öffentlichen Repository.

## Grenzen
Fachrollen sind KI-Aufgabenprofile, keine tatsächlichen Approbationen oder anwaltlichen Zulassungen. P0/P1-Fakten-, Sicherheits- und Rechteprobleme bleiben blockierend. Für öffentliche Freigaben sind unabhängig qualifizierte menschliche Reviews je Fachbereich erforderlich. Agenten niemals mit Admin-/Ruleset-Rechten oder Veröffentlichungsschlüsseln ausstatten. Dieses Dokument ist erst nach eingeschalteter GitHub-Schutzregel zuverlässig gegen gewöhnliche PR-Bypasses geschützt.