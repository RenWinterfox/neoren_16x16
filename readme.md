# NeoRen
A 16x16 Dwarf Fortress tileset.

## Instructions
Place the .png files in the `<dwarf fortress>/data/art` folder. Make sure to update your init file!
If you're using the TWBT files, make sure you also copy overrides.txt into `<dwarf fortress>/data/init/`.  

## Vanilla Files
- neoren-16x16-font.png - ASCII only
- neoren-16x16-vgfx.png - ASCII w/ Basic graphics

### TWBT Files
#### Required
- neoren-16x16.png - TWBT graphics (Use with any font you like, or the one included)
- neoren-16x16-extras.png - additional TWBT graphics.
- overrides.txt - place in `/data/init/`

#### Optional
- neoren-16x16-bg.png - for seeing the floor under items
- neoren-16x16-top.png - for getting some extra colors on some tiles
- neoren-16x16-extras-bg.png

## Known Issues
- Night Creatures (`Ñ`) all share the same tile, so they all look like ghosts.
 - This cannot be fixed without editing raws, which is beyond the scope of this project.
