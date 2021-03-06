---
title: Material Design Icon
tags: [android, material design]
---

# Material Design Icon

## Tints and shades

### Tint 
1. Copy object
2. Paste in Front twice
3. Move top object vertically 1 px down
4. Minus Front with the top and middle object selected
5. Change color to white, transparency to 20% as per guidelines

### Shade
1. Copy object
2. Paste in Front twice
3. Move top object vertically 1 px up
4. Minus Front with the top and middle object selected
5. Change color to shading color, transparency to 20% as per guidelines

## Background

Apply tint and shade

### Drop shadow

1. Copy background object, paste in front twice
2. Apply drop shadow to front object
	* Mode: Multiply 
    * Opacity: 12%
    * X Offset: 0 px
    * Y Offsset: 0 px
    * Blur: 2 px
    * Color: Black #000000
3. Apply drop shadow to bottom object:
	* Mode: Multiply 
    * Opacity: 24%
    * X Offset: 0 px
    * Y Offsset: 4 px
    * Blur: 2 px
    * Color: Black #000000

## Shapes

### Tint
1. Copy object
2. Paste in Front twice
3. Move top object vertically 1 px down
4. Minus Front with the top and middle object selected
5. Change color to white, transparency to 20% as per guidelines

### Long shadow
1. Copy object
2. Paste in Front twice
3. Move top object diagonally down and right (45 degrees) out of background shape
4. Set blend options to specified distance 1 px
5. Select moved object and top object
6. Object > Blend > Make, then Object > Blend > Expand 
8. Expand objects
8. Unite in pathfinder
9. Apply gradient
	* Type: Linear 
    * Angle: -45°
    * Left slider
    	* Opacity: 20% (10% if background is Grey 100--Grey 300)
        * Shade color
    * Midpoint location: 50% 
    * Right slider
    	* Opacity: 0%
        * Shade color
    * Color: 
10. Copy background layer, lock background layer, select shape layer and paste in front
11. Crop long shadow object and background object
12. Delete bottom path from the group that was created
13. Clean up long shadow layer
	1. Select all anchor points except end points
    2. Remove
14. Arrange long shadown below shape

### Drop shadow

1. Effect > Stylize > Drop shadow
	* Mode: Multiply
    * Opacity: 20%
    * X Offset: 4 px
    * Y Offset: 4 px 
    * Blur: 4px
    * Color: shade color
   
### Shade

#### Alternative 1

1. Copy shape, paste in front
2. Change drop shadow on top object to:
	* Mode: Multiply
    * Opacity: 20%
    * X Offset: 0 px
    * Y Offset: 1 px
    * Blur: 0 px
    * Color: shade color
3. Shade should be on top of drop shadow

#### Alternative 2

Apply shade as in 
   
### Finish

1. Copy background object to finish layer
2. Apply gradient
   * Type: Radial
   * Angle: 45
   * Left slider
     * Color: white
     * Opacity: 10%
   * Midpoint slider location: 33%
   * Right slider
     * Color: white
     * Opacity: 0%
3. Gradient tool: drag from top left corner of grid to bottom right of background


## Specifications

Corners: 12px

## Tips

* Use Grey 200+ as brighter colors will make tinted edges invisible
* Use Grey 800- as darker colors will make shaded edges invisible

## Resources

* Material Palette
* [Icons - Style - Material design guidelines](https://material.google.com/style/icons.html#icons-product-icons)

### Guides

* [Material Design Icon Tutorial - YouTube](https://www.youtube.com/watch?v=ZoRE9bv1mcc)
* [What Google missed in their guidelines for Material Design iconography](https://stories.uplabs.com/what-google-missed-in-their-guidelines-for-material-design-iconography-daf9f88000ec#.dnifjeudf)

