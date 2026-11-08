# Romain Fernandez — personal research website

A lightweight English-language website for GitHub Pages. Plain HTML and CSS,
with no build step, JavaScript, external fonts, or tracking.

## Local preview

From this directory:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Open <http://127.0.0.1:8000>. Stop the server with Ctrl+C when finished.

## Editing

- `index.html`: biography, research themes, project descriptions, roles and links.
- `styles.css`: layout, colours and responsive styles.
- The inline SVG is an original conceptual illustration, not scientific data.
  Replace or complement it with research visuals only when cleared for publication.
- `profile/README.md`: companion text to copy into the separate `Rocsg/Rocsg`
  repository as its root `README.md`. It is not the Pages website.

Affiliation, current interests, project roles and the Arize research goal were
supplied by Romain.
Fijiyama and PhenoTrack3D descriptions were checked against their public
repository READMEs; the PhenoTrack3D DOI comes from its README.

Before publication, confirm the Scholar profile, the VITIMAGE project link,
the English role wording, and the project descriptions. The institutional
profile is an existing recruitment article, not a current contact directory.
Add a preferred public contact address and the Arize project link,
and selected publications / approved research images when available.
No email address or unverified publication details have been invented.

## Publication

This working directory was cloned from `Rocsg/Rocsg.github.io`.
No changes are published merely by editing these local files.

After reviewing the content, commit and push to that repository. In its GitHub
settings, select **Pages → Build and deployment → Deploy from a branch**,
choose the branch containing these files and the **/ (root)** folder.
The `.nojekyll` file disables Jekyll processing.

The expected user-site address is <https://rocsg.github.io/>.
Verify the Pages deployment and live website after pushing.
