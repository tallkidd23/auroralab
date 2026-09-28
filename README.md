# Aurora Lab

Aurora Lab is a standalone full-page interactive reduced-order solar-weather simulator for `auroralab.tallkidd.com`.

## Included

- Configurable solar flare and CME event.
- Interplanetary CME transit animation.
- Magnetosphere compression based on solar-wind pressure.
- Simplified magnetic coupling using IMF Bz.
- Polar precipitation and aurora response.
- Observatory and Research display modes.
- Optional subtle solar and nighttime Earth ambience using Web Audio, muted until enabled.
- Responsive GitHub Pages-ready layout.

## Model note

This is an educational visual model, not a forecast or research-grade MHD solver. It uses reduced-order relationships including dynamic pressure, approximate dipole field lines, simplified coupling, and stylized atmospheric emissions.

## Deployment

Enable GitHub Pages for the `main` branch and point `auroralab.tallkidd.com` at the Pages domain using the included CNAME configuration when DNS is ready.
