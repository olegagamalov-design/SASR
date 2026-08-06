# SASR — project site

Two self-contained HTML pages. No build step, no dependencies, no external requests.
Each page carries its own CSS inline and renders correctly with the network off.

    index.html           project site (concept, operating point, status, publications)
    reaudit-paper.html   companion page for the closure-hierarchy re-audit manuscript

The two pages link to each other with relative paths, so keep them in the same folder.

## Publishing to GitHub Pages

1. Create a new public repository.
2. Upload both `.html` files to the repository root.
3. Settings → Pages → Source: "Deploy from a branch" → `main` / `root` → Save.
4. The site appears at `https://<username>.github.io/<repo>/` within a minute or two.

## Editing

Open either file in a text editor. All styling lives in the single `<style>` block at
the top; content is plain HTML below it. Search for a phrase to find where it lives.

## Known open items

- The re-audit manuscript is labelled "Under review". Add the journal name once confirmed
  (search for `Under review` in both files).
- The Zenodo entry lists 10.5281/zenodo.21437772 as current and 10.5281/zenodo.21412076
  as the earlier version. The submitted manuscript cites the earlier DOI.
- The stability section states beta = 0.57 against a Mercier limit of ~0.035. This is taken
  from the re-audit manuscript's operating point.

Oleg Agamalov · ORCID 0000-0002-0330-8268
