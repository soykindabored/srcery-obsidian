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

4. Obsidian Community [Download](https://community.obsidian.md/themes/srcery) 

## Srcery Palette

This is the canonical colors for Srcery, a syntax highlighting theme for
various editors and GUIs.

Created using colors that logically adheres to the 16 color base palette of a
terminal, while trying to retain its own identity. The colors are designed to
be easy on the eyes, yet contrast well with the background for long sessions
using an editor or terminal emulator.

Check out [🌐 srcery.sh](https://srcery.sh) and [Github](https://github.com/srcery-colors) for more.


| IMG | NAME | INDEX | HEX | RGB | HSL |
|------|-------|-------|------|-------|------|
| ![black](https://raw.githubusercontent.com/srcery-colors/srcery-assets/master/swatch/black_24.jpg) | black | 0 | `#121110` | `rgb(18, 17, 16)` | `hsl(30, 6%, 7%)` |
| ![red](https://raw.githubusercontent.com/srcery-colors/srcery-assets/master/swatch/red_24.jpg) | red | 1 | `#EF2F27` | `rgb(239, 47, 39)` | `hsl(2, 86%, 55%)` |
| ![green](https://raw.githubusercontent.com/srcery-colors/srcery-assets/master/swatch/green_24.jpg) | green | 2 | `#519F50` | `rgb(81, 159, 80)` | `hsl(119, 33%, 47%)` |
| ![yellow](https://raw.githubusercontent.com/srcery-colors/srcery-assets/master/swatch/yellow_24.jpg) | yellow | 3 | `#FBB829` | `rgb(251, 184, 41)` | `hsl(41, 96%, 57%)` |
| ![blue](https://raw.githubusercontent.com/srcery-colors/srcery-assets/master/swatch/blue_24.jpg) | blue | 4 | `#2C78BF` | `rgb(44, 120, 191)` | `hsl(209, 63%, 46%)` |
| ![magenta](https://raw.githubusercontent.com/srcery-colors/srcery-assets/master/swatch/magenta_24.jpg) | magenta | 5 | `#E02C6D` | `rgb(224, 44, 109)` | `hsl(338, 74%, 53%)` |
| ![cyan](https://raw.githubusercontent.com/srcery-colors/srcery-assets/master/swatch/cyan_24.jpg) | cyan | 6 | `#0AAEB3` | `rgb(10, 174, 179)` | `hsl(182, 89%, 37%)` |
| ![white](https://raw.githubusercontent.com/srcery-colors/srcery-assets/master/swatch/white_24.jpg) | white | 7 | `#C5B088` | `rgb(197, 176, 136)` | `hsl(39, 34%, 65%)` |
| ![bright_black](https://raw.githubusercontent.com/srcery-colors/srcery-assets/master/swatch/bright_black_24.jpg) | bright_black | 8 | `#917E6B` | `rgb(145, 126, 107)` | `hsl(30, 15%, 49%)` |
| ![bright_red](https://raw.githubusercontent.com/srcery-colors/srcery-assets/master/swatch/bright_red_24.jpg) | bright_red | 9 | `#F75341` | `rgb(247, 83, 65)` | `hsl(6, 92%, 61%)` |
| ![bright_green](https://raw.githubusercontent.com/srcery-colors/srcery-assets/master/swatch/bright_green_24.jpg) | bright_green | 10 | `#98BC37` | `rgb(152, 188, 55)` | `hsl(76, 55%, 48%)` |
| ![bright_yellow](https://raw.githubusercontent.com/srcery-colors/srcery-assets/master/swatch/bright_yellow_24.jpg) | bright_yellow | 11 | `#FED06E` | `rgb(254, 208, 110)` | `hsl(41, 99%, 71%)` |
| ![bright_blue](https://raw.githubusercontent.com/srcery-colors/srcery-assets/master/swatch/bright_blue_24.jpg) | bright_blue | 12 | `#68A8E4` | `rgb(104, 168, 228)` | `hsl(209, 70%, 65%)` |
| ![bright_magenta](https://raw.githubusercontent.com/srcery-colors/srcery-assets/master/swatch/bright_magenta_24.jpg) | bright_magenta | 13 | `#FF5C8F` | `rgb(255, 92, 143)` | `hsl(341, 100%, 68%)` |
| ![bright_cyan](https://raw.githubusercontent.com/srcery-colors/srcery-assets/master/swatch/bright_cyan_24.jpg) | bright_cyan | 14 | `#2BE4D0` | `rgb(43, 228, 208)` | `hsl(174, 77%, 53%)` |
| ![bright_white](https://raw.githubusercontent.com/srcery-colors/srcery-assets/master/swatch/bright_white_24.jpg) | bright_white | 15 | `#FCE8C3` | `rgb(252, 232, 195)` | `hsl(39, 90%, 88%)` |
| ![dark_green](https://raw.githubusercontent.com/srcery-colors/srcery-assets/master/swatch/dark_green_24.jpg) | dark_green | 22 | `#294229` | `rgb(41, 66, 41)` | `hsl(120, 23%, 21%)` |
| ![dark_red](https://raw.githubusercontent.com/srcery-colors/srcery-assets/master/swatch/dark_red_24.jpg) | dark_red | 88 | `#4F2321` | `rgb(79, 35, 33)` | `hsl(3, 41%, 22%)` |
| ![dark_blue](https://raw.githubusercontent.com/srcery-colors/srcery-assets/master/swatch/dark_blue_24.jpg) | dark_blue | 24 | `#1E5181` | `rgb(30, 81, 129)` | `hsl(209, 62%, 31%)` |
| ![dim_green](https://raw.githubusercontent.com/srcery-colors/srcery-assets/master/swatch/dim_green_24.jpg) | dim_green | n/a | `#2E5C2E` | `rgb(46, 92, 46)` | `hsl(119, 33%, 27%)` |
| ![orange](https://raw.githubusercontent.com/srcery-colors/srcery-assets/master/swatch/orange_24.jpg) | orange | 202 | `#FF5F00` | `rgb(255, 95, 0)` | `hsl(22, 100%, 50%)` |
| ![bright_orange](https://raw.githubusercontent.com/srcery-colors/srcery-assets/master/swatch/bright_orange_24.jpg) | bright_orange | 208 | `#FF8700` | `rgb(255, 135, 0)` | `hsl(32, 100%, 50%)` |
| ![teal](https://raw.githubusercontent.com/srcery-colors/srcery-assets/master/swatch/teal_24.jpg) | teal | 30 | `#008080` | `rgb(0, 128, 128)` | `hsl(180, 100%, 25%)` |
| ![gray1](https://raw.githubusercontent.com/srcery-colors/srcery-assets/master/swatch/gray1_24.jpg) | gray1 | n/a | `#1C1B19` | `rgb(28, 27, 25)` | `hsl(40, 6%, 10%)` |
| ![gray2](https://raw.githubusercontent.com/srcery-colors/srcery-assets/master/swatch/gray2_24.jpg) | gray2 | n/a | `#262522` | `rgb(38, 37, 34)` | `hsl(45, 6%, 14%)` |
| ![gray3](https://raw.githubusercontent.com/srcery-colors/srcery-assets/master/swatch/gray3_24.jpg) | gray3 | n/a | `#312F2C` | `rgb(49, 47, 44)` | `hsl(36, 5%, 18%)` |
| ![gray4](https://raw.githubusercontent.com/srcery-colors/srcery-assets/master/swatch/gray4_24.jpg) | gray4 | n/a | `#3B3935` | `rgb(59, 57, 53)` | `hsl(40, 5%, 22%)` |
| ![gray5](https://raw.githubusercontent.com/srcery-colors/srcery-assets/master/swatch/gray5_24.jpg) | gray5 | n/a | `#45433E` | `rgb(69, 67, 62)` | `hsl(43, 5%, 26%)` |
| ![gray6](https://raw.githubusercontent.com/srcery-colors/srcery-assets/master/swatch/gray6_24.jpg) | gray6 | n/a | `#504D47` | `rgb(80, 77, 71)` | `hsl(40, 6%, 30%)` |

## Screenshots

![srcery-obsidian](assets/srcery-screenshot-1.png)
