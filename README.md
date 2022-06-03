# HyperLoot-Card-Back-Art-Contest

My submission for HyperLoot Card Back Art Contest

## Finished artwork

![Finished artwork](1050x750_300dpi_002_mergeExportedFrames.png)

## Workflow

1. Draw with [Krita](https://www.krita.org)
   1. Use Line tool on vector layer
2. Export as .svg
   1. Parse svg with [Bash](https://www.gnu.org/software/bash/), and shape values with [Julia](https://julialang.org)
3. Animate svg with [SMIL](https://developer.mozilla.org/en-US/docs/Web/SVG/SVG_animation_with_SMIL)
   1. Generate .svg with Julia
   2. Render each frames as .png with [svg2movie](https://github.com/edi2004/svg2movie)
4. Merge some frames with Krita
   1. And place it on template

## Reference links

HyperLoot Card - Decentralized Card Game
<https://hyperlootproject.com/hyperloot-card/>

HyperLoot Card Back Template
<https://hyperlootproject.com/hyperloot-card/hyperloot-card-back-white-template.png>

HyperLoot logo image
<https://hyperlootproject.com/hyperloot-logo@2x.png>

## License

This work is licensed under the terms of [CC0](LICENSE).

To the extent possible under law, [SAITO Takashi (tksh)](https://github.com/tksh) has waived all copyright and related or neighboring rights to this work. This work is published from: Japan.

[![CC0 1.0](https://licensebuttons.net/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)
