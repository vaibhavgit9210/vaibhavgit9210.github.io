# portfolio-site

Git repo → `git@github-personal:vaibhavgit9210/vaibhavgit9210.github.io.git` (user site — GitHub Pages serves from `main`). Live at https://vaibhavkumar.is-a.dev/ — custom domain via `CNAME`; all vaibhavgit9210.github.io URLs 301 there, so **curl the is-a.dev URL when verifying deploys**.

- Single-file portfolio (`index.html`).
- The old weather app is preserved at `weather/` and linked from the site's "Glow-Up" timeline.
- `backrooms/` and `simulation-cam/` in here are deployed **copies** — their sources of truth live at the workspace root (`../backrooms/`, `../simulation-cam/`); re-copy after editing the originals, don't edit the copies.
- Every page carries the site-analytics beacon (see `../site-analytics/README.md`) — paste the same beacon block into any new page before deploying.
