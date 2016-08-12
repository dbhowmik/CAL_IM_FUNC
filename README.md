# CAL implementation of image processing functions
This repo relates to Rathlin deliverable D9: Encoding exemplary CAL image processing functions.

Disclaimer: This is a non-exhaustive list. Not all function will be implemented within the lif-time of Rathlin (I) project. Exemplars will be implemented from selected categories. 

# Functions:
(I: Implemented, IP: In-progress  P: Planned)

#Image Arithmaetic (P)
1. Addition
2. Subtraction
3. Multiplication
4. Division
5. Blending
6. Logical AND/NAND
7. Logical OR/NOR
8. Logical XOR/XNOR
9. Invert / Logical NOT
10. Bitshift Operators

# Point Operations (P)
1. Thresholding
2. Adaptive Thresholding
3. Contrast Stretching
4. Histogram Equalisation
5. Logarithmic Operator
6. Exponential / Raise to Power Operator
7. RGB to YUV Color Space Converstion
8. YUV to RGB Color Space Converstion

# Geometric Operations (P)
1. Scale
2. Rotate
3. Reflect
4. Translate
5. Affine Transform

# Image Analysis (P)
1. Intensity Histogram
2. Classification
3. Connected Components Labeling 
4. Pixel Value Distribution
5. Classified Pixels
6. Connected Componenets

# Morphology (P)
1. Dilation - grow image regions
2. Erosion - shrink image regions
3. Opening - structured removal of image region boundary pixels
4. Closing - structured filling in of image region boundary pixels
5. Hit and Miss Transform - image pattern matching and marking
6. Thinning - structured erosion using image pattern matching
7. Thickening - structured dilation using image pattern matching
8. Skeletonization/Medial Axis Transform - finding skeletons of binary regions

# Feature Detectors (P)
1. Roberts Cross Edge Detector - 2×2 gradient edge detector
2. Sobel Edge Detector - 3×3 gradient edge detector
3. Canny Edge Detector - non-maximal suppression of local gradient magnitude
4. Compass Edge Detector - 3×3 gradient edge detectors
5. Zero Crossing Detector - edge detector using the Laplacian of Gaussian operator
6. Line Detector - line (as distinct from edge) feature detector

# Image Transforms (P)
1. Distance Transform, maps binary images to distance from background
2. Fourier Transform, maps image into spatial frequency domain
3. Hough Transform, maps image into votes for specified shapes
4. Wavelet Transform, maps image into spatial frequency domain

# Temporal Image Analysis (P)
1. Motion Estimation
2. Optic Flow Computation

# Image Statistics (P)
1. Histogram Computation
2. Statistical Distributions

# Higher Level Algorithm (P)
1. Scene Saliency Computation
2. Meanshift Tracking
3. Crowd Analsysis
4. Person Re-Identification
5. RFS tracking  


#Reference read: 
1. http://homepages.inf.ed.ac.uk/rbf/HIPR2/wksheets.htm
2. https://en.wikipedia.org/wiki/Kernel_(image_processing)
3. https://en.wikipedia.org/wiki/Discrete_wavelet_transform
4. https://en.wikipedia.orghttp://cvcl.mit.edu/SUNSlides/9.912-CVC-ImageAnalysis-web.pdf/wiki/Kernel_(image_processing)#Convolution
5. https://en.wikipedia.org/wiki/Mean_shift
6. http://www.cse.psu.edu/~rtc12/CSE598G/introMeanShift.pdf
7. http://dx.doi.org/10.1109/TPAMI.2003.1195991
8. 
