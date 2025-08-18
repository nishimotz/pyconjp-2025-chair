# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a Jekyll-based blog site for PyCon JP 2025 Chair's daily reports. The site generates both Japanese and English content, with the main purpose being to document the chair's activities and thoughts during PyCon JP 2025 organization.

## Development Commands

### Initial Setup
```bash
bundle install
npm install
```

### Development Server
```bash
bundle exec jekyll serve --host 0.0.0.0 --incremental
```

### Alternative Setup (for Devin/Linux environments)
```bash
sudo apt install -y ruby-full build-essential ruby-dev
sudo gem install bundler
bundle install --path vendor/bundle
npm install
```

## Architecture and Structure

### Content Organization
- `_posts/`: All blog posts using Jekyll naming convention `YYYY-MM-DD-title.md`
- Bilingual content with `-ja` (Japanese) and `-en` (English) suffixes
- `assets/images/`: All image assets
- `_layouts/default.html`: Main layout template
- `_includes/`: Template partials for English content handling

### Technology Stack
- Jekyll static site generator
- TailwindCSS for styling
- PostCSS for CSS processing
- Ruby/Bundler for Jekyll dependencies
- Node.js/npm for frontend tooling

### Content Guidelines (from .clinerules)
- Japanese posts start with standard introduction mentioning the chair's role
- Include PyCon JP 2025 event information (September 26-27, Hiroshima)
- Include ticket sales information (conference tickets and party tickets are on sale)
- Include organizer recruitment information when appropriate
- Use `<div class="image-center">` for centered images
- End posts with update history section
- Theme: "pieces of python, coming together" (unreleased slogan)

### Writing Style Guidelines
- DO NOT use `**text**` for bold formatting in Markdown content
- Use clear hierarchical headings (## ### ####) for emphasis instead
- Keep formatting simple and readable
- Focus on clear, natural language without excessive formatting

### Frontmatter Requirements
Japanese posts:
```yaml
---
title: [Japanese title]
layout: default
permalink: /[slug]-ja.html
---
```

English posts:
```yaml
---
lang: en
title: [English title]  
layout: default
permalink: /[slug]-en.html
---
```

### File Naming and Content Creation
- Follow Jekyll convention: `YYYY-MM-DD-title.md`
- Create paired content with `-ja` and `-en` suffixes
- Images use `![alt]({{ site.baseurl }}/assets/images/image.webp)` format
- Test both language versions when making changes

## Important Notes
- All content guidelines and rules are detailed in `.clinerules`
- The site serves as personal documentation from the PyCon JP 2025 chair
- Content should maintain consistency between language versions while adapting for cultural context