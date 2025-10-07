# Content Planner

A small single-file HTML/CSS/JS content planner dashboard.

Preview locally

```bash
# from the project folder
python3 -m http.server 8000
# then open http://localhost:8000/index.html
```

Notes
- The app uses localStorage to persist posts/ideas/settings.
- Themes are configured via `themes.css` and toggled by body classes.
- To update styles, edit `index.html` (inline styles) or `themes.css` (theme vars).

Contributing
- Make small PRs and keep inline edits minimal.
