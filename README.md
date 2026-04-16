# p12-3d-workshop

Workshop @P12

This repository contains:

- A Markdown presentation in `/slides`
- 3D files in `/assets/3d`
- Pictures for the presentation in `/assets/images`
- A GitHub Actions workflow that builds a PDF presentation

## Build the presentation locally

```bash
npx @marp-team/marp-cli@latest /home/runner/work/p12-3d-workshop/p12-3d-workshop/slides/workshop.md --pdf --allow-local-files --output /tmp/workshop.pdf
```

## CI workflow

The workflow file is located at:

- `/home/runner/work/p12-3d-workshop/p12-3d-workshop/.github/workflows/build-presentation.yml`
