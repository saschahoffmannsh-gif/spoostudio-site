# Spoo Studio

Öffentliche Studio-Website für [spoostudio.de](https://spoostudio.de).
Statische Seiten, bereitgestellt über GitHub Pages.

Diese Domain gehört nur diesem Repo. Andere Subdomains
(`ai-act-kompass.spoostudio.de`, `pflegekreis.spoostudio.de`) gehören zu
eigenen Repos und werden hier nicht angefasst.

Das Spiel Squish Attack bleibt unter
https://saschahoffmannsh-gif.github.io/squish-attack/game/
(nicht auf diese Domain umziehen, sonst geht der Spielstand im Browser verloren).

## Seiten

- `/` und `/en/` – Start
- `/squish-attack/datenschutz/` und `/en/privacy/` – Datenschutz
- `/squish-attack/support/` und `/en/support/` – Support
- `/impressum/` und `/en/imprint/` – Impressum (§ 5 DDG)

Im Impressum und in der Datenschutzerklärung stehen Platzhalter für Name,
Anschrift und E-Mail. Die nicht ausfüllen, solange die Angaben fehlen.

## DNS (Porkbun)

- Apex `spoostudio.de`: A-Records auf `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
- `www.spoostudio.de`: CNAME auf `saschahoffmannsh-gif.github.io`

Die Datei `CNAME` im Repo enthält nur `spoostudio.de`. GitHub behandelt `www` als Alias.
