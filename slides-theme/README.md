# Tiimo Slides Theme

This folder contains a Tiimo-flavored theme for the upstream `slides` HTML deck framework.

## Entry Point

Open `deck-tiimo.html` directly in a modern browser for the reusable theme deck.
Open `watchos-rebuild.html` for the short Tiimo watchOS Rebuild presentation.

- Present with arrow keys, space, or the on-screen controls.
- Add `?edit` to use the in-browser editor.
- Add `?embed` when embedding the deck in an iframe.
- Press `P` or use `Download PDF` to print/export.

## Theme Rules

- Keep the deck as one self-contained HTML file.
- Keep both upstream script blocks intact. They power navigation, PDF export, and edit mode.
- Keep one HTML comment line above every `<section class="slide">`. Edit mode uses those comments as save anchors.
- Put images and videos in `slides-theme/media/` and reference them as `media/name.ext`.
- Use hosted Recoleta font files from the Tiimo design-system site. Do not copy font binaries into this repo unless licensing is confirmed.
- Product media in this folder was pulled from the public Tiimo website and Webflow CDN for local deck use.

## Voice Notes

- Use supportive, practical language.
- Prefer concrete help over productivity jargon: visual plans, smaller steps, focus support, flexible routines.
- Keep pressure low. The plan should fit the person, not the other way around.
- Talk about executive-function support without making the deck feel clinical.

## Tiimo Tokens

- Background: `#fcfcfc`
- Card: `#ffffff`
- Text: `#111717`
- Strokes: `#f0efed`, `#e5e0da`
- Accents: `#ffb2da`, `#ffe5db`, `#fccfcf`, `#fbeee1`, `#e5eaf7`, `#dce9e0`

The upstream component reference remains in `../AGENTS.md`.
