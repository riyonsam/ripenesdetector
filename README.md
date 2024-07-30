# This is a simple fruit ripeness detector created using MatLab.
Custard Apple Ripeness Detection Using Image Processing

### Overview
This project aims to develop an image processing-based solution to determine the ripeness of custard apples. The approach leverages the RGB and HSV color spaces to identify color characteristics indicative of ripeness and employs edge detection techniques to enhance accuracy. This solution is particularly useful for automated quality control in agricultural processes and can be extended to other fruits with similar characteristics.

### Features
- Color Channel Extraction: Separates the image into its Red, Green, and Blue components for individual analysis.
- HSV Conversion : Converts the RGB image to the HSV color space to simplify the identification of color characteristics associated with ripeness.
- Binary Mask Creation : Generates a binary mask to highlight areas in the image that fall within the defined Hue and Saturation ranges for ripe custard apples.
- Noise Reduction : Applies a median filter to the binary mask to remove noise.
- Edge Detection : Uses the Canny edge detection method to identify the edges of the custard apple, which aids in the accurate determination of the fruit's area.
- Ripeness Determination : Combines color detection and edge detection results to evaluate the ripeness of the custard apple based on the area of identified ripe regions.
- Visual Output : Displays various stages of processing including the original image, ripe color mask, edge detection result, and the combined result.


