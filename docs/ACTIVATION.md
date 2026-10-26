# GitHub Governance – Aktivierung und Tests

1. Alle Dateien auf `main` prüfen. Dies ist eine öffentliche Sammlung von Prozessregeln; niemals Geheimnisse/Privatdaten ergänzen.
2. `Settings → Rules → Rulesets`: für `main` PR erforderlich, keine Force Pushes oder Branch-Löschungen, verpflichtender Statuscheck `governance-owner-authorization`; kein Agenten-Bypass. Standardmäßig keine obligatorische Codeowner-Zustimmung, falls ausschließlich der Eigentümer PRs selbst eröffnet: GitHub erlaubt keine Eigen-PR-Approval-Reviews.
3. Test-PR ohne Kommentar: Check muss fehlschlagen. Danach **persönlich** als `wilfriedaigner` den Kommentar `/approve-phereklis-governance <HEAD_SHA>` schreiben und in GitHub Actions den Lauf manuell erneut starten (Kommentar löst bei diesem Workflow keinen automatischen Lauf aus). Test: Check grün. Zusätzlicher Commit: erneut rot.
4. Ein direkter `main`-Push und Force-Push muss GitHub-seitig zurückgewiesen werden; Admin-Bypass prüfen. Der Workflow allein ist keine technische Sperre.
5. **Sicherheitsgrenze:** Wenn Agenten den Eigentümer-Connector oder ein persönliches PAT mit Schreib-/Adminrechten nutzen, kann GitHub die Agentenaktion nicht als fremd erkennen. Für belastbare Separation Agentenzugang aus Governance-Repository entfernen oder auf rein lesende GitHub-App begrenzen. Owner-2FA/Passkey und Secrets nie in Agentenumgebungen.
6. `holistic-movement` bleibt privat. Die Arbeits-Pipeline sollte die öffentlich ratifizierte Governance-Commit-SHA pinnen, aber die Auswahl dieser SHA darf nicht von Agenten eigenmächtig geändert werden.

Bis die Ruleset-Aktivierung und Negativtests erfolgt sind, ist **keine technische Exklusivfreigabe** nachgewiesen.
