# System for AI Website

Static homepage inspired by the KAIST School of Computing design, featuring faculty links and research highlights for the System for AI initiative.

## Local preview
1. Start a simple web server from the repository root:
   ```bash
   python3 -m http.server 8000
   ```
2. Open http://localhost:8000 in your browser to view the homepage.

## Assets
- `assets/professor.png` is gitignored so you can manage portrait imagery locally. Add your own image with that filename in the `assets/` folder; the page falls back to an inline placeholder if the file is absent.
