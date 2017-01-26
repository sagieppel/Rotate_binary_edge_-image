# Rotate_binary_edge_-image
Rotate binary (logical) edge image (I) in (Ang) degrees. Maintain line connectivity.
	
Rotate binary edge image (I) in (Ang) degrees 
The rotated output image will also also be a binary edge image. 
The connectivity/topology of all edges/curves in the input image (I) will be maintained and the line thickness of the curves in the output image (mat) will remain 1 pixel. 
The center of rotation is the center of the image 
The dimensions of the output image (mat) will be different from the input image and will be set such that the rotated image is fully within the image frame. 
Input 
I: Binary edge image (logical type) consist of lines and curves with a thickness of one pixels (such as curves, contour line, template, or edge images) 
Ang: Rotation angle of the image in Degrees 
  
Output 
mat: Rotated version of the input image (I), also binary edge image, the connectivity/topology of the edges/curves in input image (I) is maintained and also the line thickness remain one pixel.
