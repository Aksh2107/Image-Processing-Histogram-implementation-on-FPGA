# Image-Processing-Histogram-implementation-on-FPGA

Histogram equalisation is a contrast enhancement or contrast normalisation technique. It uses the
histogram to construct a monotonic mapping that results in a flattened output histogram. From an
information theoretic perspective, histogram equalisation attempts to maximise the entropy of an image
by making each pixel value in the output equally probable.

From a contrast enhancement perspective, the assumption behind histogram equalisation is that
the peaks of the input histogram contain the information of interest and the contrast between the
peaks is of lesser importance. To make the output histogram flat, it is necessary to reduce the average
height of the peaks by spreading the pixel values out. This increases the contrast of these regions.
The valleys between the peaks are compressed to raise the average value, effectively reducing the
contrast of these features.
