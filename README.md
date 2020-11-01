# Median-Cut-Implementation
Median cut is an algorithm to sort data of an arbitrary number of dimensions into series of sets by recursively cutting each set of data at the median point along the longest dimension. Median cut is typically used for color quantization. For example, to reduce a 64k-colour image to 256 colours, median cut is used to find 256 colours that match the original data well.

The Implementation Takes an input image to quantize and the number of colors to be in the palette and outputs the image using only the colors in the palette.

The number of colors in the palette can only be in powers of 2 (2,4,8,16,32,64,128,256....)
