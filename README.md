# Glyph Construction for VSCode

**This VS Code extension provides syntax-highlighting and snippets for [Glyph Construction](https://github.com/typemytype/GlyphConstruction#readme) files, used in RoboFont for example.**

> _"Glyph Construction is a simple, powerful, human-readable language for describing how glyph shapes are built."_

![screenshot](https://raw.githubusercontent.com/adbac/GlyphConstruction-Language-Extension/refs/heads/main/images/screenshot.png)

## Features

- **Syntax-highlighting** for `*.glyphConstruction` and `*.gc` files
- **Snippets**
    - Font dimension attributes: `descender`, `xHeight`, `capHeight`, `ascender`
    - Calculated reference positions: `top`, `bottom`, `innerTop`, `innerBottom`, `left`, `right`, `innerLeft`, `innerRight`, `center`, `origin`, `width`
    - Color mark syntax (prefix: _color-mark_ or _cm_): `! 0, 0, 0, 1`
    - Transformation matrix syntax (prefix: _matrix_): `1, 0, 0, 1, 0, 0`
    - Comment variables: `OverwriteExistingGlyphs`, `AutoUnicodes`, `MarkGlyphs`
