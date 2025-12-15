# AI/ML Engineer Portfolio

This is a static portfolio website built with [MkDocs](https://www.mkdocs.org/) and the [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) theme. It is designed to be hosted on GitHub Pages.

## Features

- **Python-based**: No Node.js required. built entirely with Python tools.
- **Markdown Content**: Easy to write and maintain docs in `docs/`.
- **Responsive**: Mobile-friendly design.
- **Dark Mode**: Built-in toggle.
- **Math Support**: Renders LaTeX equations for your ML projects.

## Prerequisite

- Python 3.x

## Local Development

1.  **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

2.  **Run Dev Server**:
    ```bash
    python -m mkdocs serve
    ```
    Open [http://127.0.0.1:8000](http://127.0.0.1:8000) in your browser.

## Deployment

This repository is configured with GitHub Actions to automatically deploy to GitHub Pages.

1.  Push your changes to the `main` branch.
2.  The workflow in `.github/workflows/publish.yml` will run `mkdocs gh-deploy`.
3.  Your site will be live at `https://<username>.github.io/portfolio/`.

## File Structure

- `mkdocs.yml`: Main configuration file.
- `docs/index.md`: Homepage.
- `docs/projects.md`: Portfolio projects.
- `docs/resume.md`: Resume/CV.
