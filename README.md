# About icons

**Spreadsheet icons** are designed to accompany data grids, spreadsheets and other dynamic data views. They are clean, consistent and lightweight. You can use them to create toolbars, menu bars and context menus. They look great on any scale and screen resolution.

- It contains 160+ SVG icons. 
- Recommended size is 24px or scaled accordingly - 18, 24 or 36px.
- Recommended color on light background is black at 75% opacity - rgba(0, 0, 0, 0.75). For disabled icon style reduce the opacity to 35%.
- Recommended color on dark background is white at 80% opacity - rgba(255, 255, 255, 0.8). For disabled icon style reduce the opacity to 30%.

## What's inside?

This repository contains the following folders and files:

| Path               	| Contents                                                                      |
|--------------------	|------------------------------------------------------------------------------	|
| /svg/compressed    	| The optimized versions of all SVG files.The compression rate is ~40%.	|
| /svg/original      	| The original, uncompressed version of all SVG files.                          |
| /LICENSE.txt       	| The terms and conditions of the license.                                      |
| /README.md         	| The description of this repository.                                           |

## How to use it?

Install the icons with a package manager.

    npm i --save-dev @handsontable/spreadsheet-icons

or

    yarn add --dev @handsontable/spreadsheet-icons

#### Use SVG as an `<img>` element

```
<img src="/path/exclamation-mark.svg" alt="Exclamation mark">
```

#### Use SVG inline with HTML

```
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M13.42,9.7l-.65,5.18H11.23L10.58,9.7V5.25h2.84Zm0,9.05H10.58V15.92h2.84Z"/></svg>
```

## Documentation

The documentation of the icon set is available on
[Handsontable docs](https://handsontable.com/docs/demo-spreadsheet-icons.html).

## License

This icon set is a part of Handsontable Pro that is a commercial software distributed by Handsoncode sp. z o. o.
By installing, copying, or otherwise using this icon set, you agree to be bound by the terms
of its General Software License Terms ("Terms") available in the main directory
of the Handsontable Pro software repository.

Copyright (c) Handsoncode sp. z o.o.
