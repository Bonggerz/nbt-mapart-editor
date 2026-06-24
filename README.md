# NBT Mapart Editor

NBT Mapart Editor is a browser-based editor for Minecraft mapart structure NBT files. It can import MapArtCraft-style exports, edit the visible map pixels, preserve full-block and staircased layouts, and export the edited result back to NBT.

## Features

- Import one or more `.nbt` structure files.
- Edit mapart with brush and line tools.
- Supports carpet-only, full-block, and staircased mapart workflows.
- Preserves hidden MapArtCraft noobline rows during export.
- Adds support blocks for blocks that need them.
- Imports and saves palette profiles.
- Exports edited maps as individual files, a ZIP folder, or one combined NBT.
- Provides a zoomable and pannable canvas preview.

## Usage

Open `nbt_mapart_editor.html` in a browser.

1. Click the NBT file picker and import one or more `.nbt` files.
2. Optionally import a palette profile.
3. Select a color/block from the palette.
4. Paint with the brush or line tool.
5. Export the edited result using one of the download buttons.

## Notes

- The editor hides MapArtCraft noobline rows in the preview, but preserves them during export.
- Staircased maps preserve block heights and shading behavior.
- Palette profile import is intended for MapArtCraft-style palette files.

## License

This project is licensed under the GNU General Public License v3.0.

The block/color database is adapted from MapArtCraft:
https://github.com/mike2b2t/mapartcraft
