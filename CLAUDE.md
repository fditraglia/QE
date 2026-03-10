# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a Quarto website for the "Quantitative Economics at LMH" (Lady Margaret Hall, Oxford) course page. It contains class schedules, assignments, revision materials, and links to blog posts for an econometrics/quantitative economics course.

## Build Commands

- **Render site:** `quarto render`
- **Preview locally:** `quarto preview`

Output is generated to the `docs/` directory (configured in `_quarto.yml`).

## Architecture

- `_quarto.yml` — Quarto project config (website type, cosmo theme, output to `docs/`)
- `index.qmd` — Single-page site with all course content (classes, revision classes, logistics)
- `styles.css` — Custom CSS (currently minimal)
- `docs/` — Rendered output (committed to repo for GitHub Pages hosting)
- `QE.Rproj` — RStudio project file
