# Volume estimation using Image-processing
We perform object measurement using Computer Vision. We will use an A4 paper as our guide and find the width and height of objects placed in this region. The main library used will be OpenCV in python programming language.
We start the project by capturing reference images of the graduated tube. Image acquisition is always the first step in a workflow sequence because images are needed for processing. Image processing starts by acquiring an unprocessed picture, and converting it into a digital form. 
Image edge is the most basic feature of the image, so-called edge(EDGE) refers to the discontinuities of the local characteristics of the image. Canny edge detection uses linear filtering with a Gaussian kernel to smooth noise and then computes the edge strength and direction for each pixel in the smoothed image.

