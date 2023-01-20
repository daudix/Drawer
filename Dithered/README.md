Experimenting with dithering, these are some of the archive photos with this effect

Command: `convert image-* -resize 840x840 -strip -colors 4 -ordered-dither o8x8 image-dithered-%01d.png`

Add `-rotate <degree>` before `image-dithered-%01d.png` to set the rotation (if needed)

Original inspiration and command are from this Tobias Bernard's [Mastodon post](https://mstdn.social/@tbernard@mastodon.social/109675668858449961)
