# PHEREKLIS Agent Entry Point

Vor jeder Buchaufgabe die freigegebene `docs/AGENTEN_CHARTA.md` und `docs/ROLE_MATRIX.md` von der **explizit festgelegten Commit-SHA** lesen. Keine automatische Übernahme beliebiger Änderungen an `main`.

Ausgabe-Metadaten: `agent_id`, `policy_repo`, `policy_commit`, `chapter_id`, `input_sha`, `output_sha`, `claim_ids`, `blockers`, `review_status`.

Wenn Policy oder Freigabe unklar ist: **fail closed**. Agenten dürfen Governance-Änderungen nur vorschlagen, nicht selbst verbindlich machen.