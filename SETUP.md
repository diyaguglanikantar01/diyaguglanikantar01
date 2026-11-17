# Setup (≈10 minutes)

1. Create a **public** repo named exactly `diyaguglanikantar01`. Upload everything in this folder (keep `assets/` and `.github/`).
2. **Metrics token:** GitHub → Settings → Developer settings → Personal access tokens (classic) → generate with `repo` + `read:user` scopes.
   In the profile repo: Settings → Secrets and variables → Actions → New secret → name `METRICS_TOKEN`.
   (This is what lets private-repo activity be counted, without exposing any private details.)
3. Repo → Actions tab → run **Contribution Snake** and **Metrics** once manually (`Run workflow`). Wait ~2 min.
   Until both finish, the snake and metrics images will show as broken.
4. Edit the text I inferred from your repo names:
   - `assets/terminal.svg` (stack line, principle line)
   - `assets/card-*.svg` (descriptions and tags): open in any editor and change the text.
   - `README.md` contact links, and the name "Diya" in `assets/banner.svg`.
5. Profile settings: enable **Include private contributions**, add a bio, location and link, and upload a real avatar.
