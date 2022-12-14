# iosevka-retro-styles
Iosevka private style configurations for retrocomputing folks

The concept behind these font style sets is to replicate the *feel* of some system fonts with Iosveka, a modern, completely readable (with antialiasing) western-ish unicode-ready and feature-rich font; not to provide every character used in the Amiga Topaz or C128 fonts. For example, the C128 PETSCII graphics set is not included. It accomplished elsewhere and pretty much needs pixel-accurate representation to look right, or just the right use cases if not.

In contrast, this is just my favorite mono(+more) font with style bits set to look like a retro font, but with more modern capabilities and many more character points than existed in the originals.

Currently there are style configurations for a AmigaOS 1.3 Topaz lookalike, the C128 VDC (80-column) style and the C128 VIC (40-column) style. The 40 column set will require some font width specifications to actually accomplish double-wide (compared to the normal VDC font) spacing, but the original was not quite double the width of the 80 column font either on most monitors.

## Building

The private-build-plans.toml file is a build plan for the custom style selections for the Iosevka font, you can use the instructions [here](https://github.com/be5invis/Iosevka/blob/main/doc/custom-build.md#customized-build) to build the fonts from scratch with these options set as default.

Plus, you can use this as a starting point to make your own changes to this look if it is *closer* to what you want but not **quite** right.

The fonts to chose to build are:
- iosevka-topaz: A font that is kind of close to the AmigaOS 1.3 Topaz font
- iosevka-c128-vdc: A font that mimics the look of the C128's 80 column display output
- iosevka-c128-vic: A font that less closely mimics the look of the C128's 40 column display output

## Example Font Usage:

Topaz:

![example-iosevka-topaz](https://user-images.githubusercontent.com/16455837/150656271-9e836a5c-5422-4326-951d-eea46cd8758f.png)

C128 VDC regular:

![example-iosevka-c128-vdc](https://user-images.githubusercontent.com/16455837/200505654-f5fb8d03-8850-4a9f-9caa-9b23ce7a362c.png)

Note: this has some character width and height adjustments applied in the font settings for iTerm 2 used here.

C128 VIC bold extended:

![example-iosevka-c128-vic](https://user-images.githubusercontent.com/16455837/200450546-b0f030ee-bacc-4df1-91a6-ecc1383e17aa.png)

Note: this has some character width and height adjustments applied in the font settings for iTerm 2 used here.
