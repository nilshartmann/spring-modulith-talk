# Spring Modulith Talk

## PPTX bearbeiten

- Werkzeug: `python-pptx` im venv des Nachbar-Repos:
  `../huetly-beispiel-app/huetly/.venv/bin/python <script>`.
- **Vor jeder Änderung ein Backup** der `.pptx` anlegen.
- **Grenze:** Animations-Builds (Klick-Animationen) und das **Zusammenlegen** von
  Folien macht Nils selbst in PowerPoint — `python-pptx` zerschießt die Animationen.
  Claude schreibt Inhalte/TODOs, legt/löscht ganze Folien, hängt Notizen an.
- Arbeitskopien (`…copy*.pptx`, `…backup.pptx`) aufräumen, sobald der Stand sitzt.

## TODO-Marker auf den Folien

- 🔧 **rot** — inhaltliche TODOs
- ✂️ **blau** — Straffungs-Hinweise (Folien zusammenlegen / kürzen)
- 💡 **grün** — Nachschärfungen / Feinschliff

## Rückfragen

- Bei Rückfragen **niemals** das Tool `AskUserQuestion` verwenden — auch nicht für
  Auswahl-/Entscheidungsfragen. Rückfragen **immer** als Freitext stellen, eine
  Frage pro Turn mit deiner Empfehlung + Begründung.
- Wenn eine Antwort von mir ebenfalls eine Frage enthält, beantworte die Frage und lass dir bestätigen, dass die Antwort ausreichend war. Erst dann mit der nächsten Frage weiter machen.
- Wissenslücken: nachfragen, nicht annehmen. Was sich aus Code/Docs klären lässt → dort nachlesen statt fragen.

## Commits

- Ich committe **immer** selbst. Wenn ich dich **explizit** bitte zu committen: einzeilige deutschsprachige Commit-Message. **Ohne** Co-Authored-by (oder andere) Angaben.
