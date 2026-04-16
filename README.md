# p12-3d-workshop

Workshop @P12

This repository contains:

- A Markdown presentation in `/slides`
- 3D files in `/assets/3d`
- Pictures for the presentation in `/assets/images`
- A GitHub Actions workflow that builds a PDF presentation

## Build the presentation locally

```bash
npx @marp-team/marp-cli@latest slides/workshop.md --pdf --allow-local-files --output workshop.pdf
```

## CI workflow

The workflow file is located at:

- `.github/workflows/build-presentation.yml`
