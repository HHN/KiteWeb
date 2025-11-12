# Kite2Web

This repository contains the web build artifacts and supporting runtime data for the KITE project. Use the files in `Build/` to run the web player, and find runtime mappings, prompts and generated feedback in `StreamingAssets/`.

What is in this repo
- `Build/` — Web player build files (e.g. `Kite2Web.framework.js`, `Kite2Web.js`) and related assets for serving the project on the web.
- `StreamingAssets/` — Runtime mapping files, prompts, novels metadata and generated feedback used by the player (examples: `novels.json`, `Prompt.txt`, `feedbacks/`).
- `Images/` — Supplementary images used by the web build or documentation.
- `index.html` — Local entry page to load the web player (if present).
- `ChangeLog.txt`, `Readme.txt` — repo metadata and notes.

Quick local preview (static server)
1) From a shell in this repository root you can serve the files locally. Example using Python (if installed):

   python -m http.server 8000

Then open `http://localhost:8000/index.html` in a browser to load the web player.

Licenses
- If present in the repository root, see `LICENSE_SOFTWARE.txt` (code) and `LICENSE_ASSETS.txt` (content) for license details.

---

Dieses Repository enthält die Web-Build-Artefakte und unterstützende Laufzeitdaten für das KITE-Projekt. Verwenden Sie die Dateien in „Build/“, um den Webplayer auszuführen, und finden Sie Laufzeit-Mappings, Prompts und generierte Feedbacks in „StreamingAssets/“.

Was befindet sich in diesem Repository
- `Build/` — Web-Player-Build-Dateien (z. B. `Kite2Web.framework.js`, `Kite2Web.js`) und zugehörige Assets zum Hosten im Web.
- `StreamingAssets/` — Laufzeit-Mapping-Dateien, Prompts, Metadaten der Novels und generiertes Feedback (z. B. `novels.json`, `Prompt.txt`, `feedbacks/`).
- `Images/` — Zusätzliche Bilder.
- `index.html` — Lokale Einstiegsseite zum Laden des Webplayers (falls vorhanden).
- `ChangeLog.txt`, `Readme.txt` — Metadaten und Hinweise zum Repo.

Schnelle lokale Vorschau (statischer Server)
1) Über eine Shell im Repository-Root können Sie die Dateien lokal bereitstellen. Beispiel mit Python (sofern installiert):

   python -m http.server 8000

Öffnen Sie anschließend `http://localhost:8000/index.html` in einem Browser, um den Webplayer zu laden.

Lizenzen
- Sofern vorhanden, siehe `LICENSE_SOFTWARE.txt` (Code) und `LICENSE_ASSETS.txt` (Inhalte) im Repository-Root für Details.