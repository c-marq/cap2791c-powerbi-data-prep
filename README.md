# Power BI: Data Preparation and Modeling

*From Raw Files to a Trusted Model*, a free online textbook by Professor Carlos Marquez for CAP2791C at Miami Dade College.

**Read it online:** https://c-marq.github.io/cap2791c-powerbi-data-prep/

The book follows one story, the Sabor Miami food trucks, from raw files and databases to a model you can trust, using Power BI Desktop on Windows. The chapters are a preview for now. Each page lists the purpose, objectives, sections, Try This ideas and Microsoft Learn resources, and the full text is coming.

## Repository Structure

| Folder or file | What's Inside | When to Use It |
|--------|--------------|----------------|
| [`chapters/`](chapters/) | The eight chapters and the appendix, one Markdown page each, with a `.meta.yml` file per page | Reading and editing the book |
| [`images/`](images/) | Figures and the book cover | Used by the chapters |
| [`instructor/`](instructor/) | Links to the private instructor folder (no files) | Instructor use only |
| [`index.md`](index.md) | The book's home page | Start here when editing |
| [`myst.yml`](myst.yml) | Book settings and table of contents | Adding or reordering pages |
| [`book.config.json`](book.config.json) | Settings for the book-writing checks | Validation and build tools |

The folders `exercises/`, `data/` and `resources/` will be added later.

## Building locally

```bash
npm install -g mystmd
myst build --html
```

The site is built and published to GitHub Pages by the workflow in `.github/workflows/deploy.yml`.

## License

CC-BY-4.0
