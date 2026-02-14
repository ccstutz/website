# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Personal website for Chris Stutz, a protein engineer. This is a static site with no build system, framework, or dependencies.

## Structure

- `website/` — The website: `index.html`, `style.css` (no JavaScript)
- `claude_code_install.sh` — Standalone Claude Code installer script (unrelated to the website)

## Development

No build step, package manager, or test suite. To preview the site, open `website/index.html` in a browser or use any static file server (e.g., `python3 -m http.server -d website`).

## Notes

- Publications are listed under the legal name "Charles Christopher Stutz" / "Charles C. Stutz" — maintain this distinction from the display name "Chris Stutz".
