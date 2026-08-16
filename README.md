# ARA Board Resource Hub

A public, static link hub for Association of Rice Alumni board members. The site
routes visitors to resources maintained in Google Drive and on Rice University
websites; it does not host or control access to those materials.

**Live site:** https://carlincherry.github.io/ara-board-hub/

## Local preview

No build step or package installation is required.

```sh
python3 -m http.server 8000
```

Open http://localhost:8000/ in a browser.

## Maintaining content

- Edit resource names, descriptions, and destinations in `index.html`.
- Keep destination links external with `target="_blank"` and
  `rel="noopener noreferrer"`.
- Update shared presentation rules in `styles.css`.
- Keep `404.html` aligned with the main site's visual identity.
- Push changes to `main`. The workflow in `.github/workflows/pages.yml`
  publishes the repository through GitHub Pages.

## Design sources

The site uses Rice Blue (`#00205B`) and Rice Gray (`#7C7E7F`) from the
[official Rice University color guide](https://brand.rice.edu/colors). The
friendly abstract owl, arch, and line motifs are original SVG/CSS artwork
created for this project. No official Rice logo, photography, remote fonts,
icon libraries, or third-party artwork is included.

## Repository

https://github.com/carlincherry/ara-board-hub
