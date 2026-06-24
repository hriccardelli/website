# Academic Website — Hunter [LastName]

Built with [Quarto](https://quarto.org) and deployed via GitHub Pages.

## Local development

1. Install [Quarto](https://quarto.org/docs/get-started/)
2. Clone this repo
3. Run `quarto preview` to see live changes

## File structure

```
.
├── _quarto.yml        # Site config, navbar, theme
├── index.qmd          # Homepage / About
├── research.qmd       # Papers page
├── teaching.qmd       # Teaching page
├── custom.scss        # All styling
└── files/
    ├── cv.pdf         # ← drop your CV here
    ├── paper1.pdf     # ← JMP
    ├── paper2.pdf     # ← PNAS paper
    ├── paper3.pdf     # ← land use paper
    └── headshot.jpg   # ← your photo
```

## Deploying to GitHub Pages

1. Create a new GitHub repo (e.g. `yourusername.github.io` or `website`)
2. Push this folder to `main`
3. Go to repo Settings → Pages → set Source to **GitHub Actions**
4. The `.github/workflows/deploy.yml` handles the rest on every push

## Customizing

- Update `_quarto.yml`: replace name, email, GitHub username
- Fill in `index.qmd`: bio, research interests
- Fill in `research.qmd`: paste your abstracts, update links
- Drop files into `/files/`: CV PDF, paper PDFs, headshot
