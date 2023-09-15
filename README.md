# Trivial example of removing background from an image

Removing the background signal from an image will enhance noise in the picture. Based on the scale of the background blurring the algorithm can be made more specific to the amount of background signal that should be removed (this is a variant of band-pass filtering).

If you use such a correction as preprocessing in another model be aware that the background can contain information that you are removing now. What remains should be an image with more texture information.

The image used as an example has a resolution of 144x144 pixel, the blurring filter has a size of sigma=27. You may need to adjust the filter size based on yuor own images.
