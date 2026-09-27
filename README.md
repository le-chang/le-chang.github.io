# le-chang.github.io — Le Chang's academic website

Built on [al-folio](https://github.com/alshedivat/al-folio) (Jekyll, v1.x). Two tabs: **home** and **cv**. No profile photo.
Every push to `main` triggers `.github/workflows/deploy.yml`, which builds the site and publishes it through GitHub Pages
(Settings → Pages → Source must be **GitHub Actions**). Nothing needs to be installed locally.

## Editing

| What | File |
| --- | --- |
| Home page (bio, degrees, awards, research interests, publication links) | `_pages/about.md` |
| CV page (embeds the PDF) | `_pages/cv.md` — just replace `assets/pdf/Le_Chang_CV.pdf` to update the CV |
| Contact / social icons (email, ORCID, Google Scholar, GitHub) | `_data/socials.yml` |
| Site title, description, keywords | `_config.yml` |
| BibTeX (only used by the search box; the publication list links to Google Scholar) | `_bibliography/papers.bib` |

The stable public URL of the CV is `https://le-chang.github.io/assets/pdf/Le_Chang_CV.pdf`.

## History

The previous Hugo/PaperMod site (常乐乐博士) is preserved on the `hugo-brand-backup` branch.
