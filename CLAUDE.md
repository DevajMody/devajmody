# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Personal portfolio website for Devaj Mody - a static HTML/CSS site with no build system or dependencies.

## Structure

- `index.html` - Single-page portfolio with hero, experience timeline, bio, projects (with category filtering), and writing sections
- `styles.css` - Karpathy-inspired minimal design with responsive breakpoints at 768px and 480px
- `assets/` - Images including profile photo, company logos, and social icons (SVG)

## Development

Open `index.html` directly in a browser. No build step, server, or package manager required.

## Design Notes

- Timeline layout uses CSS Grid with 4 columns: year, line, logo, content
- Project filtering implemented with vanilla JS data attributes (`data-categories`)
- Mobile responsive: timeline collapses to stacked layout, hero centers
