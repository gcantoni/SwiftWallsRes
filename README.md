# Swift Walls Theming
Swift Walls resources files available for creating third party overlays.

## About
In this repo you can find all the files you need to be able to create third-party overlays, taking advantage of the resources of Swift Walls, to change the graphical aspect of the application. Note that all resources for customization are made "non-hardcoded" and are very easy to override.
For the creation and application of third party overlays see the <a href="https://github.com/substratum/template">official Substratum documentation.</a>

## What can I theme?
Basically anything in the app. Swift Walls has a proprietary theme engine that you can leverage at your leisure.
Please, remember that you can simply override the resources here and do not add any more as you like as on Android the resources are generated in run-time and once created they cannot be modified anymore.

## Accents
You can change all the attributes of the styles in this file but not change the name of the style nor the parent.

## Colors & night colors
In these files you can find all the colors of the app. The default main color is called "colorAccentX" and at line 105 you can find all the colors used by the theme engine to modify.

## Dimensions
Here you find the dimensions of the app's graphics.

## Themes
The various themes that are applied by the theme engine when you select a color.

## Future usage?
Implement, if possible and at the lowest time cost, a different proprietary theme engine based on overlays created directly by users.
