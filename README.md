# BlackStar

**Cyber risk, in financial terms.** BlackStar helps organisations plan security investment and allocate resources during cyberattacks.

🌐 **Live site:** https://projectblackstar.github.io/

## About this repository

This repository hosts the BlackStar website, a single-page site with:

- **Home:** the interactive architecture map and flowchart (Collect → Model → Quantify → Optimize → Report)
- **What we do:** a step-by-step scroll infographic
- **How it works:** why BlackStar is needed, and the published research behind each stage
- **Pricing:** proposed pilot plans, with an enquiry form
- **Trust and About:** data handling, sources, team and contact
- **Nova:** a built-in guide that answers from a fixed library (no external AI service)

Everything lives in `index.html`. There is no build step and no dependencies.

Website designed and built by **Padmesh G**, for Team Project BLACKSTAR:
Samarth R Anegundi, Mohit Musturi, Padmesh G, Veda Sai Manasa, Gopa Parthiv and Ronak B.

## Settings

Open `index.html`, search for `SITE_CONFIG`, and fill in what you have:

| Setting | Effect |
|---|---|
| `prototypeUrl` | "Launch prototype" buttons open the live prototype |
| `youtubeChannelUrl` / `youtubeVideoId` | Adds the walkthrough video and channel link |
| `formEndpoint` | Contact and enquiry forms are sent here (for example, a free Formspree form) |
| `contactEmail` | Shown on the About and Pricing pages |

## Updating the site

Upload the new `index.html` (Add file → Upload files → Commit changes). GitHub Pages republishes within about a minute.

## Contact

projectblackstar57@gmail.com
