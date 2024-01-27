# edge-detection
AIM: The aim of this code is to demonstrate the application of edge detection operators, specifically the Sobel, Prewitt, and Roberts operators, on a image.


Sobel Operator:
Purpose: Sobel operator is used for edge detection and image gradient computation.
Operation: Computes the gradient of the image intensity in both the horizontal (Sobel X) and vertical (Sobel Y) directions.
Kernel: It uses convolution with a small, separable kernel.
Effect: Emphasizes edges in the image.
Prewitt Operator:
Purpose: Similar to Sobel, Prewitt is used for edge detection.
Operation: Computes the gradient of the image intensity in both horizontal (Prewitt X) and vertical (Prewitt Y) directions.
Kernel: Employs a convolution operation with a 3x3 kernel.
Effect: Emphasizes edges in a manner similar to Sobel.
Roberts Operator:
Purpose: Roberts Cross operator is used for edge detection.
Operation: Computes the gradient using a pair of 2x2 convolution kernels.
Kernel: The two kernels are applied separately to calculate horizontal and vertical gradients.
Effect: Emphasizes edges with a simple and fast computation, but it can be sensitive to noise.
