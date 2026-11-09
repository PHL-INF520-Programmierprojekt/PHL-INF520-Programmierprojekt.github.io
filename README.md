# Pages-Spiegel für Classroom 50

Dieses Repo stellt nur die Seite `https://phl-inf520-programmierprojekt.github.io/classroom50/` bereit.
Von dort lädt der Bewertungslauf jedes Studi-Repos das Steuerskript, die Aufgabenliste und die Autograder.

Warum: Seit dem 07.11.2026 ist die Organisation im Tarif Free. Dort darf das private Repo `classroom50` keine Pages-Seite mehr veröffentlichen.
Der Inhalt ist derselbe, den `classroom50` vorher selbst veröffentlicht hat (allow-list aus `publish-pages.yaml`). Roster, Punkte und Teams gehören nicht dazu.

- Quelle: `classroom50`, Ordner `_site` nach den Schritten von `.github/workflows/publish-pages.yaml`, Stand im Commit-Text.
- Nicht von Hand bearbeiten. Nach Änderungen in `classroom50` (z. B. neue Aufgaben oder Autograder) neu aufbauen und hierher übertragen.
- Rückbau, sobald die Org wieder Team hat: Pages hier abschalten oder das Repo löschen, Pages in `classroom50` wieder auf „GitHub Actions“ stellen und `publish-pages.yaml` einmal starten.
