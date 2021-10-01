# Texture Overview

Three small png files are controlling the vast majority of Townscaper's texturing:

* TownPalette.png (16 x 2 px) sets the house base colors
* TownMaterial.png (128 x 128 px)  controls certain aspects of the shaders, i.e. where the roof color is applied
* TownColor.png (128 x 128 px) is an overlay that is used as a base for the custom shader to texture pretty much everything from windows, roofs, and walls to butterflies

# TownPalette function and mapping

This chapter requires some basic understanding of UV mapping. Shortly said, UV mapping is about mapping a plane onto a model. Usually, the coordinates here are in the range of 0..1, exceeding values are wrapped.
![](../images/ExamplePalette)
