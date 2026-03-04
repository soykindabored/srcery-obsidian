<p align="center">
  <img src="https://raw.githubusercontent.com/srcery-colors/srcery-assets/master/src/logo_border.svg">
</p>

<p align="center">
  <a href="https://srcery.sh">
    <img src="https://img.shields.io/static/v1?label=&message=Website&style=flat&color=5B5B5B&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAYAAAAf8/9hAAAACXBIWXMAAA7MAAAOzAGxoQZ+AAAAGXRFWHRTb2Z0d2FyZQB3d3cuaW5rc2NhcGUub3Jnm+48GgAAAdJJREFUOI1jDAgIYMAFTp8+EcrIyMRqYmK2DJcaJlwS548fV2RjYJnNxsg87fzx44okGbBhwwaWvyyMSzM4dfgrlGz5/7IwLt2wYQML0QZIS0s2mLFIWIZxqDKkyJowuAirWkpLSzYQZcDZsyfthJnYK2p4TBkYGRgYGBkYGXo0PBjE2XgqT58+7oTXgHPnzgky/GNYXMFlwizEyAEXF2bjYujX9GJiYmBedPr0aWGcBvz793teOIeanBWrJIZT7YQUGFJkTaQZGf4v3LBhAyOGAWdPn8hUZxYIyODUweZVBgYGBoYqZXsGQz5Jb1lpiQycYUAqgBtgbGox/ebfDxtmfL+CU3Hb3YMM5z893/r46YsZWF3AxMSatPLHrUfHfj/H0Hzo3QOGOY/PPP3PwBgfEBDwH6sBRkZG7xmYGGI7vp35++7/D7j421/fGAqvb/v3j+FvnKmp6VusXoB7xdj80Nt/Pztavpxm+M/AwPCf4T9DyY0dDC9/fWk3NbXchzMMkMHTp88bTv15cXzVj9sMcx6fYdjz9vbxp0+fN2BTy4grN54/flyRiYX1PCMTI8PfX78MDS0t72NThzMaDS0t7//5/y/z99+/mbg0MzAwMAAAVbWgDHTwVjUAAAAASUVORK5CYII=">
  </a>
  <a href="https://discord.gg/G6vBMmZ">
    <img src="https://img.shields.io/discord/714101903377694741?color=%232C78BF&label=Discord&logo=discord">
  </a>
  <a href="https://www.npmjs.com/package/@srcery-colors/srcery-palette">
    <img src="https://img.shields.io/npm/v/@srcery-colors/srcery-palette?color=%23FBB829&label=Palette%20version&logo=npm">
  </a>
</p>

<h2 align="center">Srcery</h2>

<p align="center">
	Srcery is a color scheme with clearly defined contrasting colors and a slightly earthy tone.
</p>


## Requirements
- [Obsidian](https://obsidian.md/) v1.1.9 or above

## Installation

### Manual

1. Clone the repo:
   ```sh
   git clone git@github.com:soykindabored/srcery-obsidian.git
   ```
   Or from the [srcery-colors](https://github.com/srcery-colors/srcery-obsidian) community managed repo:
   ```sh
   git clone git@github.com:srcery-colors/srcery-obsidian.git
   ```

2. Copy `manifest.json` and `theme.css` into your vault's theme directory:
   ```sh
   mkdir -p /path/to/vault/.obsidian/themes/Srcery
   cp manifest.json theme.css /path/to/vault/.obsidian/themes/Srcery/
   ```

   **Or** symlink the files if you want to stay up to date with `git pull`:
   ```sh
   mkdir -p /path/to/vault/.obsidian/themes/Srcery
   ln -s /path/to/srcery-obsidian/{manifest.json,theme.css} /path/to/vault/.obsidian/themes/Srcery/
   ```
   Note that you have to create the `themes/` directory in each vault's `.obsidian/` unless you've already installed a theme from the marketplace.

3. In Obsidian, go to **Settings → Appearance → Themes** and select **Srcery**.

## Palette

All colors sourced from the official [srcery-palette](https://www.npmjs.com/package/@srcery-colors/srcery-palette).

### Primary

| Name | Hex |
|------|-----|
| Black | `#1C1B19` |
| Red | `#EF2F27` |
| Green | `#519F50` |
| Yellow | `#FBB829` |
| Blue | `#2C78BF` |
| Magenta | `#E02C6D` |
| Cyan | `#0AAEB3` |
| White | `#BAA67F` |
| Bright Black | `#918175` |
| Bright Red | `#F75341` |
| Bright Green | `#98BC37` |
| Bright Yellow | `#FED06E` |
| Bright Blue | `#68A8E4` |
| Bright Magenta | `#FF5C8F` |
| Bright Cyan | `#2BE4D0` |
| Bright White | `#FCE8C3` |

### Secondary

| Name | Hex |
|------|-----|
| Orange | `#FF5F00` |
| Bright Orange | `#FF8700` |
| Hard Black | `#121212` |
| Teal | `#008080` |
| XGray1 | `#262626` |
| XGray2 | `#303030` |
| XGray3 | `#3A3A3A` |
| XGray4 | `#444444` |
| XGray5 | `#4E4E4E` |
| XGray6 | `#585858` |
| XGray7 | `#626262` |
| XGray8 | `#6C6C6C` |
| XGray9 | `#767676` |
| XGray10 | `#808080` |
| XGray11 | `#8A8A8A` |
| XGray12 | `#949494` |

## Screenshots

![srcery-obsidian](assets/srcery-screenshot-1.png)
