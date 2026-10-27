# Adrian Design Kit — component gallery

**[Open the live gallery →](https://adrianmcli.github.io/adrian-design-kit-gallery/)**

An interactive static gallery of typography, glowing wordmarks, a soft halo, rotating borders and cards. Switch between Kaiju and Stables specimens; pause motion, try restrained mode, inspect the original Kaiju mark or switch Stables to its light scheme.

This repository contains only compiled gallery assets and dependency notices. The [source design kit](https://github.com/adrianmcli/adrian-design-kit) remains private; access is required. Public JavaScript/CSS bundles are necessarily downloadable. There are no credentials, private source snapshots, analytics or backend services here.

The bespoke Global Stables globe is not included because its source was unavailable. The Stables rotating border is a starter component, not a globe.

## Publication

GitHub Pages serves the root of the `main` branch. `.nojekyll` disables Jekyll processing. This is a build snapshot, not an automatic sync from the private source kit.

To update, run tests and build the private source kit with `npx vite build --base=/adrian-design-kit-gallery/`, then replace the `index.html` and `assets/` output here. Keep this README, `.nojekyll`, `NOTICE.md` and the `licenses/` directory; refresh dependency notices if dependencies change.

## Rights

Public display does not grant a general reuse license for Adrian's designs or identity. See [NOTICE.md](NOTICE.md). Bundled React, React DOM, Next.js starter style fragments and self-hosted fonts retain their respective [MIT / SIL OFL notices](licenses/).
