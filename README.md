# PHEREKLIS Governance

**Öffentliches Regelrepository** für das wissenschaftlich fundierte PHEREKLIS-Buch und den PHEREKLIS Science Hub. Die privaten Manuskripte und internen Forschungsdaten verbleiben ausschließlich im privaten Repository `wilfriedaigner/holistic-movement`.

## Governance-Regeln
- [Agenten-Charta V3.1](docs/AGENTEN_CHARTA.md)
- [Rollenmatrix](docs/ROLE_MATRIX.md)
- [Einstiegspunkt für Agenten](AGENTS.md)
- [Schutz aktivieren und testen](docs/ACTIVATION.md)

## Änderungsautorität
Nur `wilfriedaigner` soll Governance-Revisionen freigeben. Technisches Konzept: GitHub-PR und exakter Kommentar `/approve-phereklis-governance <HEAD_SHA>`, danach ein **verpflichtender** Actions-Statuscheck und manueller Merge. Wichtig: Der Check wird erst mit aktivierten GitHub-Branchregeln verbindlich. Ein Agent, der über das Eigentümerkonto dieselben Schreib-/Adminrechte besitzt, ist davon nicht sicher getrennt; Agententokens müssen eingeschränkt werden.

## Arbeitsablauf
G0 Kapitelkonzept → G1 Evidenz und Fachbeiträge → 17 Synthese → G2 Redaktion einschließlich **Science Box** und optionalem **Mythos Check** → G3 unabhängige Science/Legal-Audits → menschliche Freigabe → G4 Buch und **PHEREKLIS Science Hub** → G5 internationale Editionen.

**Keine Secrets, persönlichen Gesundheitsdaten, unveröffentlichten Manuskripte oder vertraulichen Unterlagen in dieses öffentliche Repository hochladen.**
