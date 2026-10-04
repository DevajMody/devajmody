# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Personal website for Devaj Mody - a static HTML/CSS site with no build system or dependencies, served by GitHub Pages from `main` at devajmody.com.

## Structure

- `index.html` - Single page: a now/prev timeline, built projects, and links
- `styles.css` - Minimal dark-only design modeled on ustr.github.io
- `assets/logos/` - Organization logos shown at 1em next to each timeline line

## Development

Open `index.html` directly in a browser. No build step, server, or package manager required.

## Design Notes

- Dark only: black background, white text, `system-ui` at weight 300, 500px column
- Each section is a two-column grid: a small uppercase muted label, then the content
- `now` and `prev` sit tight inside `.timeline`; other sections get 3rem spacing
- Keep every line short and lowercase: organization link, then a few words of role
