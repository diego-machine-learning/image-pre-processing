## Computer vision pipeline

https://towardsdatascience.com/computer-vision-for-beginners-part-2-29b3f9151874

Considerations

Improve image quality for a given identification context ( text, objects, patterns )

Remove noise - control pixel intensity ( generalization )

Kernels are used to apply specific rules in a given range

## Blurring - perform noise reduction 
* high resolution images - non desired information ( too many  data )
* so blurry images - non suficient information ( lost data )

- average blurring | use average as center of the given area
- median blurring | use median as center of the given area
- gaussian blurring | (study more)
- bilateral filtering | (study more)


## Thresholding - transform images into binary
### set value and max value

- binary
- inverse of binary
- threshold to zero
- inverse of threshold to zero
- threshold truncation

## Gradient
* the image gradient represents directional changes in the intensity or color mode

- sobel | (study more)
- laplacian | (study more)

Morphological Transformation
* manipulate the figures of images by filtering

 - erosion | shrink pixels ( more intensity )
 - dilation | expand objects ( in opposite to erosion )

 HSV colors

## HUE
https://www.lifewire.com/what-is-hsv-in-design-1078068

* Hue is the color portion of the model, expressed as a number from 0 to 360 degrees:

Red falls between 0 and 60 degrees.
Yellow falls between 61 and 120 degrees.
Green falls between 121-180 degrees.
Cyan falls between 181-240 degrees.
Blue falls between 241-300 degrees.
Magenta falls between 301-360 degrees.

* SATURATION
Saturation describes the amount of gray in a particular color, from 0 to 100 percent. Reducing this component toward zero introduces more gray and produces a faded effect. Sometimes, saturation appears as a range from just 0-1, where 0 is gray, and 1 is a primary color.

* VALUE (OR BRIGHTNESS)
Value works in conjunction with saturation and describes the brightness or intensity of the color, from 0-100 percent, where 0 is completely black, and 100 is the brightest and reveals the most color.
