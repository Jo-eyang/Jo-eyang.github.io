# jo-eyang.github.io

Personal academic website of **Jiayi Yang**, built on [al-folio](https://github.com/alshedivat/al-folio) with a customized home layout and NYU-purple theme.

## Where to edit

| What | File |
| --- | --- |
| Bio, research interests, photo caption | `_pages/about.md` |
| Profile photo | `assets/img/prof_pic.jpg` (square image) |
| News items | `_news/*.md` (one file per item) |
| Publications | `_bibliography/papers.bib` (`selected={true}` shows it on the home page) |
| Research / course projects | `_projects/*.md` |
| HTML CV page | `_data/cv.yml` |
| CV PDF | `assets/pdf/Jiayi_Yang_CV.pdf` |
| Social links | `_data/socials.yml` |
| Site-wide settings | `_config.yml` |
| Custom styles | `_sass/_custom.scss` (colors are set in `assets/css/main.scss`) |
| Home page layout | `_layouts/about.liquid` (local override of the al-folio theme layout) |

## Deploy

Every push to `main` triggers `.github/workflows/deploy.yml`, which builds the site and pushes it to the `gh-pages` branch.
In the repo's **Settings → Pages**, set *Source* to **Deploy from a branch** → `gh-pages` / `(root)`.
In **Settings → Actions → General → Workflow permissions**, choose **Read and write permissions**.

## Local preview (optional)

```bash
bundle install
bundle exec jekyll serve   # http://localhost:4000
```
