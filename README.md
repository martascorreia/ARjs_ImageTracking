Test application of AR.js, in the scope of my thesis "Web Augmented Reality Applied to Cultural Heritage". 
This project tests the use of natural makers as the tracking method for the Augmented Reality experience. Consult AR.js at "[https://ar-js-org.github.io/AR.js-Docs/marker-based/](https://ar-js-org.github.io/AR.js-Docs/image-tracking/)" for documentation.

Natural Markers are a camera-based tracking technique that uses computer vision algorithms to detect easily recognizable markers associated with the tracking image. These markers differ from Passive Markers (like QRCodes) because they use specific geometric shapes or colors that naturally belong to the existing environment. The disadvantages of this technique include a larger processing time, recognition challenges due to differences in luminosity, and changes in scenery. Its major advantage is that it is non-intrusive as it takes advantage of the natural state of the environment.

To see this project working:
  1. access "https://martascorreia.github.io/ARjs_ImageTracking/";
  2. point the camera to this image of the Colosseum "https://github.com/martascorreia/ARjs_ImageTracking/blob/main/assets/coliseu.png";
The statue of Venus de Milo should appear on top of the image.

The file https://github.com/martascorreia/ARjs_ImageTracking/blob/main/arjs_naturalMarkers.gif shows a working example.
