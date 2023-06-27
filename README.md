# ImageRevealApp
## Here your image will slowly reveal itself by randomly shown and generated polygons.
`index.html` - the main complete app, pause/unpause animations (press space) and change images (CTRL+ArrowLeft to go to the previous one and CTRL+ArrowRight to go to the next one). Upload your images to the `images` folder.
Adjust the number of polygons in line 98 `const numParts = 5;` and the speed of them coming to view at line 192. More parts require more compute power.
These apps only have the "view" portion of the functionality
`randomPolygons.html` - Completly random polygons (will not cover entire image and will not connect with themselves)
`randomPolygonsAdhering.html` - Completly random polygons (will not cover entire image **BUT WILL CONNECT** with themselves)
`randomTiles.html` - 4x4 tiles that are scrambled in random and are animatied in in random
