# dienstantritt-content

Öffentliches Content-Repo für die App **Dienstantritt** (inoffizielles Informationsangebot).
Liefert signierte Inhalts-JSONs über GitHub Pages aus. Code/App liegen in einem separaten privaten Repo.

Auslieferung: `/v1/manifest.json` (+ `.sig`, `content_public_key.pem`, `modules/`). Integrität: Ed25519-Signatur + SHA-256.
