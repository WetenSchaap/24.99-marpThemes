# Marp Themes

A repo containing my personal themes for Marp. Feel free to use them :)

## Available themes

- ``monterosa``: compact theme for scientific presentations
- ``monorosa``: Same as ``monterosa``, but with monospace fonts
- ``jgu``: Theme as used at JGU. Includes a default frontslide, which is just an ``.svg`` image, that will need to be adapted if names and small image are changed.

## How to use: notes for myself

If you use VSCode, you need to add a direct link to the raw themes to the ``markdown.marp.themes`` setting (so something like ``https://raw.githubusercontent.com/WetenSchaap/24.99-marpThemes/main/themes/jgu.css``). Otherwise, things should work out of the box.

To design a new theme, just pase everything in the css file between the ``style`` tags at the beginning of ``example.md``, and start adding stuff.
