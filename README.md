# Tiger / EMED — NEPTS Sector Intelligence Packet (creditswan.ai)

Static, single-file site. `index.html` is self-contained (inline CSS/JS/SVG; Google Fonts loaded at runtime).

## Deploy on Vercel via GitHub
1. Create a new GitHub repository and add these files at the repository root (`index.html`, `README.md`).
2. In Vercel: **Add New → Project → Import** the repository.
3. Framework preset: **Other**. Build command: *(leave empty)*. Output directory: *(leave empty — root)*.
4. Deploy. The packet is served at `/`; sections are addressable by hash, e.g. `/#numbers`, `/#datalayer`.

No build step, no dependencies, no environment variables. Robots are set to `noindex, nofollow`.
