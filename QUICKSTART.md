# Quick Start Guide

Get started with `md-viewport` in 30 seconds!

## Installation

```bash
npm install -g md-viewport
```

Or use without installing:

```bash
npx md-viewport README.md
```

## Basic Usage

```bash
# Render any markdown file
mdvp README.md

# That's it! Your browser will open with a beautifully styled version
```

## Common Commands

```bash
# Dark theme
mdvp docs.md --theme dark

# Disable table of contents
mdvp notes.md --no-toc

# Keep the HTML file (don't auto-delete)
mdvp article.md --no-auto-cleanup
```

## Configuration

Create `.mdvprc.json` in your project:

```json
{
  "theme": "dark",
  "toc": true,
  "copyButton": true
}
```

## What Gets Rendered?

- ✅ GitHub Flavored Markdown
- ✅ Syntax-highlighted code blocks
- ✅ Math equations ($...$, $$...$$)
- ✅ Mermaid diagrams
- ✅ Tables, task lists, and more
- ✅ Auto-generated table of contents

## Example

Try it with the included example:

```bash
mdvp example.md
```

## Need Help?

```bash
mdvp --help
```

Visit [GitHub](https://github.com/Showwaiyan/md-viewport) for full documentation.
