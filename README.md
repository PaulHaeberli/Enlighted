# Enlighten
Automatically brighten dark areas in high dynamic range images

This code shows how to automatically brighten the darker areas of high dynamic range images.

To compile, just type 

% make

To test it 

% make test

This image processing method is related to Homomorphic Image Processing but avoids the use of fft, etc.

[wikipedia link](https://en.wikipedia.org/wiki/Homomorphic_filtering#Image_enhancement)

[faadooengineers link](http://www.faadooengineers.com/online-study/post/ece/digital-image-processing/1123/homomorphic-filtering)

This method is used in my photo painting app for iOS called "PhotoViva"

The image blurring is implemented by resizing an image to a small size and then resizing it big again.

Enlighten sees the world like your eyes see the world.

Creditis: Uses https://github.com/nothings/stb to read, write and resize images.

