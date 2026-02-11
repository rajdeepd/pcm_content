# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

PCM Learning Hub is a Jekyll-based educational content website for Physics, Chemistry, and Mathematics for Classes 9-11. It uses the Just the Docs theme and is deployed via GitHub Pages.

## Common Commands

```bash
# Install dependencies
bundle install

# Run local development server (serves at localhost:4000)
bundle exec jekyll serve

# Build site (output to _site/)
bundle exec jekyll build
```

## Architecture

### Content Structure
- Content is organized by class level: `class9/`, `class10/`, `class11/`
- Within each class, content is organized by source/publisher:
  - `ncert_exemplar/`, `physics_ncert/`, `chem_ncert/` - NCERT content
  - `cengage_physics/`, `chem_cengage/` - Cengage content
  - `arihant_physics/`, `arihant_chem/` - Arihant content
  - `fiitjee/` - FIITJEE competitive exam content
  - `modulus/` - Modulus coaching content
- Root-level `index_*.md` files serve as index pages linking to chapter content

### Jekyll Configuration
- `_config.yml` - Main Jekyll config with Just the Docs theme settings
- `_includes/head_custom.html` - Custom CSS styles for content boxes (formula-box, example, definition, key-points, warning, etc.)
- `_includes/mathjax.html` - MathJax configuration for LaTeX math rendering
- `_sass/color_schemes/custom.scss` - Custom color scheme

### Math Notation
Content uses MathJax for mathematical formulas:
- Inline math: `$...$` or `\(...\)`
- Display math: `$$...$$` or `\[...\]`

### Custom CSS Classes
Use these classes in markdown content for styled boxes:
- `.formula-box` - Green-bordered box for formulas
- `.key-points` - Blue info box for key concepts
- `.definition` - Yellow-bordered definition box
- `.example` - Gray example box with "Example" header
- `.warning` - Red warning box
- `.info-card` - Gray info card
- `.tag-ncert`, `.tag-fiitjee`, `.tag-cengage` - Source label badges
- `.tag-easy`, `.tag-medium`, `.tag-hard` - Difficulty badges

### Frontmatter
Content pages use Jekyll frontmatter with Just the Docs navigation:
```yaml
---
title: Page Title
layout: default
parent: Parent Page Title
nav_order: 1
---
```
