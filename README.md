# CAL implementation of image processing functions
This repo relates to Rathlin deliverable D9: Encoding exemplary CAL image processing functions.

Disclaimer: This is a non-exhaustive list. Not all function will be implemented within the life-time of Rathlin (I) project. Exemplars will be implemented from selected categories. 

# Functions:
(I: Implemented, IP: In-progress  P: Planned)

#Image Arithmetic (P)
1. Addition - pointwise addition: image + image (or constant)
2. Subtraction - pointwise subtraction: image - image (or constant)
3. Multiplication - pointwise multiplication: images * image (or constant)
4. Division - pointwise division: images / image (or constant)
5. Blending / Fusion - pointwise linear combination of two image
6. Logical AND/NAND - pointwise logical ANDing/NANDing of two binary images
7. Logical OR/NOR - pointwise logical ORing/NORing of two binary images
8. Logical XOR/XNOR - pointwise logical XORing/XNORing of two binary images
9. Invert / Logical NOT - pointwise inversion of a binary image
10. Bitshift Operators - pointwise scaling of an image using shift operation 2^x. More efficient than division / multiplication. 

# Point Operations (P)
1. Thresholding - select pixels with given values to produce binary image
2. Adaptive Thresholding - like Thresholding except choose values locally
3. Contrast Stretching - spreading out graylevel distribution
4. Histogram Equalisation - general method of modifying intensity distribution
5. Logarithmic Operator - reducing contrast of brighter regions
6. Exponential / Raise to Power Operator - enhancing contrast of brighter regions
7. RGB to YUV - Color Space Converstion 
8. YUV to RGB - Color Space Converstion

# Geometric Operations (P)
1. Scale - change image content size (Bilinear / Bicubic)
2. Rotate - change image content orientation
3. Reflect - flip over image contents
4. Translate - change image content position
5. Affine Transform - general image content linear geometric transformation

# Image Analysis (P)
1. Intensity Histogram - the image intensity distribution
2. Classification - mapping from pixel values to feature or object classes
3. Connected Components Labeling - grouping pixels with the same class label into regions
4. Pixel Value Distribution - the number of pixels having each value
5. Classified Pixels - the category of scene entity that the corresponding pixel is taken from
6. Connected Componenets - the groups of pixels all of which have the same label or classification

# Morphology (P)
1. Dilation - grow image regions
2. Erosion - shrink image regions
3. Opening - structured removal of image region boundary pixels
4. Closing - structured filling in of image region boundary pixels
5. Hit and Miss Transform - image pattern matching and marking
6. Thinning - structured erosion using image pattern matching
7. Thickening - structured dilation using image pattern matching
8. Skeletonization/Medial Axis Transform - finding skeletons of binary regions

# Feature Detectors (IP)
1. Roberts Cross Edge Detector - 2×2 gradient edge detector
2. Sobel Edge Detector - 3×3 gradient edge detector (I)
3. Canny Edge Detector - non-maximal suppression of local gradient magnitude
4. Compass Edge Detector - 3×3 gradient edge detectors
5. Zero Crossing Detector - edge detector using the Laplacian of Gaussian operator
6. Line Detector - line (as distinct from edge) feature detector

# Image Transforms (P)
1. Distance Transform, maps binary images to distance from background
2. Fourier Transform, maps image into spatial frequency domain
3. Hough Transform, maps image into votes for specified shapes
4. Wavelet Transform, maps image into spatial frequency domain -- FWT 5/3 lifting for 5 level decomposition (I) 

# Temporal Image Analysis (P)
1. Motion Estimation
2. Optic Flow Computation

# Image Statistics (P)
1. Histogram Computation
2. Statistical Distributions

# Higher Level Algorithm (IP)
1. Scene Saliency Computation
2. Meanshift Tracking (I)
3. Crowd Analsysis
4. Person Re-Identification
5. RFS tracking  
6. ACF pedestrian detector


#Reference read: 
1. http://homepages.inf.ed.ac.uk/rbf/HIPR2/wksheets.htm
2. https://en.wikipedia.org/wiki/Kernel_(image_processing)
3. https://en.wikipedia.org/wiki/Discrete_wavelet_transform
4. https://en.wikipedia.orghttp://cvcl.mit.edu/SUNSlides/9.912-CVC-ImageAnalysis-web.pdf/wiki/Kernel_(image_processing)#Convolution
5. https://en.wikipedia.org/wiki/Mean_shift
6. http://www.cse.psu.edu/~rtc12/CSE598G/introMeanShift.pdf
7. http://dx.doi.org/10.1109/TPAMI.2003.1195991
