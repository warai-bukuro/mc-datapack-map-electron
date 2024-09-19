[![](https://img.shields.io/github/actions/workflow/status/jacobsjo/mc-datapack-map/pages.yml)](https://github.com/jacobsjo/mc-datapack-map/actions)
[![map.jacobsjo.eu](https://img.shields.io/github/deployments/jacobsjo/mc-datapack-map/github-pages?label=map.jacobsjo.eu)](https://map.jacobsjo.eu)
[![](https://img.shields.io/github/issues-raw/jacobsjo/mc-datapack-map)](https://github.com/jacobsjo/mc-datapack-map/issues)
[![](https://img.shields.io/badge/sponsor-jacobsjo-blue)](https://github.com/sponsors/jacobsjo)
[![](https://weblate.catter.dev/widget/jacobsjo/mc-datapack-map/svg-badge.svg)](https://weblate.catter.dev/projects/jacobsjo/mc-datapack-map/)
</a>

## Use online at https://map.jacobsjo.eu 

--------

# MC Datapack Map

|   |   |
|---|---|
| [![](public/favicon.svg)](https://map.jacobsjo.eu) | A Leaflet based map to display Minecraft biome layouts and structures of vanilla and using worldgen datapacks.  |
|   |  |

![](docs/header.png)

# Translations
Translate at https://weblate.catter.dev/projects/jacobsjo/mc-datapack-map/

# Contributing
Contributions are welcome! For significant feature additions please ask beforehand by opening an issue or on discord.

## Setup dev environment:

1. Install python dependencies: `pip install -r requirements.txt`
2. Install node dependencies: `npm i`
3. Create vanilla datapack zip files: `npm run createZips`
4. Install electron and electron-vita: `npm install --save-dev electron electron-vite -D`
5. Install vite-plugin-electron: `npm install vite-plugin-electron -D`
6. Install electron-builder: `npm install electron-builder -D`
7. Start dev server: `npm run electron:dev`
8. Build final page: `npm run electron:build`
9. Run builded binary: ``
   - ** If you get a download error, you can continue the download by running the build as a administrator. **
