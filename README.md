# gdt-calc

Static Game Dev Tycoon score calculator.

## What this project is

This repository preserves a fan-made calculator for estimating:

- game score
- review score
- target score for the next release
- recommended slider positions

The original project was recovered from archived static pages. This version has been cleaned up to run as a simpler standalone site without Wayback-specific assets.

## What changed in this cleanup

- removed archived analytics and broken asset references
- removed the Bootstrap dependency that was only used for layout
- switched game history persistence from cookies to `localStorage`
- refreshed the page structure and improved mobile behavior
- kept the existing formulas and calculator data intact

## Run locally

Because this is a static site, you can open [index.html](/home/lenin/Downloads/gdt-calc-master/index.html) directly in a browser or serve the folder with any basic HTTP server.

Example:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000/`.

## Data source and credit

Credit for the formulas and reference data belongs to the Game Dev Tycoon community research around the original calculator and related strategy guides.

Useful reference:

- https://gamedevtycoon.fandom.com/wiki/Success_Guide
