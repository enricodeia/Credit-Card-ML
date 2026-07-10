# Credit Card Studio

A 3D / WebGL studio for designing and animating credit cards, right in the browser.

## Features

- **Multi-card scene** — add, duplicate, rename and select cards by clicking them.
- **Free-axis rotation** — spin each card around any azimuth axis, with mirrored / opposite directions.
- **After Effects–style timeline** — keyframe any value on per-property tracks, with GSAP-driven playback and selectable eases (including custom eases).
- **Soft-touch matte finish** — material-level micro-grain, micro-relief and satin sheen.
- **Post-processing pipeline** — bloom, god rays, radial light, vignette, chromatic aberration, film grain and color grading.
- **Canvas format & export** — aspect-ratio control (16:9, 9:16, 1:1, custom) and high-resolution PNG export.

## Usage

Single self-contained file — just open `index.html` in a modern browser. three.js and GSAP are loaded from a CDN, so an internet connection is required.

## Tech

- **three.js** (WebGL) — 3D card, materials and post-processing.
- **GSAP** (+ CustomEase) — the keyframe timeline.
- Vanilla JavaScript, no build step.

## Deploy

Static project — no build required. Point Vercel (or any static host) at this repository; `index.html` is served from the root.
