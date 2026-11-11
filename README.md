# bjmt.github.io

Personal academic website, built with [Quarto](https://quarto.org) and published to
GitHub Pages by `.github/workflows/publish.yml` on every push to `main`.

## Preview locally

```bash
quarto preview
```

## Updating the CV

`files/Tremblay_CV.pdf` is built from `cv/academic_cv.tex` in the job-search repository;
rebuild it there and copy the PDF here.

## Publishing

1. Create a public GitHub repository named `bjmt.github.io` and push this folder to it.
2. In the repository settings, under Pages, set the source to **GitHub Actions**.
3. The site appears at <https://bjmt.github.io> a minute or two after each push.
