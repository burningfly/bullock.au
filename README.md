# bullock.au

A plain static HTML/CSS website. There is no Node.js, npm, framework, build command, database, or application server required.

## Deploy with Cloudflare Pages

- Connect this GitHub repository to Cloudflare Pages.
- Framework preset: **None**
- Production branch: **main**
- Build command: leave blank
- Build output directory: **/** (repository root; enter `/` or `.` if the dashboard requires a value)

The site is served directly from the repository root. Every push to `main` will trigger a deployment.

## Local preview

Run `python3 -m http.server 8080` in this directory and open http://localhost:8080.

## Before launch

- Confirm that `hello@bullock.au` is the preferred contact email.
- Review the wording of role descriptions and project summaries.
- Add real project photographs when ready. No project photographs or unprovided specifications are included.
- The page currently loads Google Fonts remotely; the fallback fonts work if that service is unavailable.
