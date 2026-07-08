# CLAUDE.md

This file provides guidance to Claude Code when working in this repository.

## What this is

Maple & Bean — an **agency demo** (fictional coffee shop), used as a portfolio piece.
Static HTML/CSS/JS, no build step. See the root `../CLAUDE.md` for shared conventions
(preview/deploy commands, SEO expectations, image guidelines).

## Structure

`index.html` at root, `css/style.css`, `js/main.js`, real photos in `images/` (see
`images/README.md`). Deployed via GitHub Pages at `maplenbean.caiomsi.com`
(Cloudflare DNS, see `CNAME`).

## Design language

Warm, cozy coffee-shop palette — cream/sand background (`--color-bg #fdf3e4`),
espresso-brown ink text, terracotta/clay accent (`--color-accent #c75d3c`), honey and
caramel highlights, a single cool sage-green pop used sparingly. Design tokens are
defined at the top of `css/style.css` — edit those rather than hardcoding colors.

## No lead capture

This site has **no contact form or booking flow** — it's a pure showcase/portfolio
page, not a functioning business site. If a contact section is ever added, wire it to
the shared `MSI-Forms` backend (see root `CLAUDE.md`) to match the other agency demos.
