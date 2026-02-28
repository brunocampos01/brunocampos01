# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is Bruno Campos's GitHub profile repository (`brunocampos01/brunocampos01`). It contains only a `README.md` rendered as the GitHub profile page and an `images/` folder with icons and images referenced in the README.

There is no build system, test suite, or application code. There are no commands to run.

## Structure

- `README.md` — GitHub profile page written in HTML-flavored Markdown. Uses `<details>`/`<summary>` collapsible sections to organize project categories (Academic, DevOps, Data Engineering, Data Science).
- `images/` — PNG/GIF assets referenced inline in the README via absolute GitHub URLs.

## Working with This Repo

- All content changes are edits to `README.md`.
- Images are referenced via absolute GitHub raw URLs (e.g., `https://github.com/brunocampos01/brunocampos01/blob/main/images/...`). New images should be added to `images/` and referenced the same way.
- GitHub Stats cards use the `github-readme-stats.vercel.app` API with consistent theming: `theme=react`, `bg_color=151515`, `icon_color=79ff97`, `text_color=9f9f9f`.
- Project entries follow a two-column table pattern: left column is a bold linked project name, right column is a `github-readme-stats` pin card.
