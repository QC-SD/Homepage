# QCSA homepage

- Maintain `index.html` as a single static page for Quantum Computing at UC San Diego. Keep assets in `assets/` and use relative URLs so the page works under both the GitHub Pages repository path and `qcsd.us`.
- Preserve the dark palette, IBM Plex Sans typography, and simple section layout. Use native fragment links for navigation and respect reduced-motion preferences.
- Keep club information current. Confirm public contact details, leadership roles, and event dates with the club before publishing them. Keep time-sensitive event details in the linked event listing when possible.
- Preview with `python3 -m http.server 8000` from the repository root. Check mobile and desktop layouts, keyboard navigation, section links, and asset loading before handing off changes.
- See `DEPLOY.md` for hosting and DNS. Leave deployment, commits, and pushes to the maintainer unless explicitly requested.
