# thewyattbrocato.github.io

The GitHub Pages user-site root for `thewyattbrocato`. It exists so that crawlers and AI assistants can find the host-root files that the project Pages sites (`/ai-deal-finder/`, `/leverage-library-site/`, `/scamfirstaid-site/`, `/ai-leverage-field-guide-site/`) cannot carry themselves:

- `robots.txt`: allow all, with a `Sitemap` line.
- `sitemap.xml`: this host's root page and the project sites under it.
- `llms.txt`: a short plain-text index for AI assistants ([llmstxt.org](https://llmstxt.org/) shape).
- `index.html`: a small landing page that points to <https://wyattbrocato.site> and lists the project sites.

Plain static files, no build step, no scripts, no analytics, no external hosts. `.nojekyll` turns off Jekyll.

Keep it small. Project content belongs in the project repos, not here. When a project site is added, removed or moves, update `sitemap.xml`, `llms.txt` and `index.html` together, and only list a URL that returns 200.
