# Architecture Reading List

A simple static reading-list website designed for GitHub Pages.

## Publish with GitHub Pages

1. Create a GitHub repository, e.g. `architecture-reading-list`.
2. Upload all files in this folder to the repository root.
3. Commit the files to the `main` branch.
4. Open repository **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select **main** and **/(root)**, then Save.
7. GitHub will provide the public Pages URL after deployment.

## Updating

The reading data lives in `books.json`.
Ask Codex to add/edit readings there. The site reads the JSON automatically.

Example:
> Add "Complexity and Contradiction in Architecture" by Robert Venturi to books.json under Architectural Theory. Mark it Supplementary, priority 4, status Not started. Do not redesign the site.

See `AGENTS.md` for maintenance rules.

## Course cross-references

[课程知识库中的重合书籍与章节](COURSE-READING-OVERLAPS.md)

Matching entries in `books.json` include course references, topics, related chapters and additional source links; existing reading status, priority and category are preserved.
