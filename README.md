# Dominykas Pavlijus — Portfolio

Personal portfolio for front-end engineering and UI design. Built with semantic HTML, CSS and vanilla JavaScript. No build step or package dependencies.

## Preview locally

Run `python3 -m http.server 8000` from the repository and open http://localhost:8000.

## Content

Selected projects: VRK, Orion, MESO Group, Devoro, Black Banx and FK Ekranas. Project covers are editorial graphics, not screenshots of the websites. The first five projects credit UI design and front-end contributions; FK Ekranas credits UI design.

Styles are in `style.css` and `mediaqueries.css`. `script.js` handles the accessible mobile navigation and footer year. Google Fonts is optional: system fallback fonts are included. Existing assets and CV remain in `assets/`.

## Restore the pre-refresh version

The complete version before the October 19, 2026 refresh is preserved on GitHub in branch `backup/pre-refresh-2026-10-19`, at commit `492d93fd7dc916996614c6775626fdd47f558310`.

To restore its tracked files without rewriting history, from a clean checkout of `main`:

```sh
git fetch origin
git restore --source=origin/backup/pre-refresh-2026-10-19 --staged --worktree .
git commit -m "Restore portfolio before October 2026 refresh"
git push origin main
```
