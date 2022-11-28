# Normalised-Histogram-Area
Calculating the normalised area of the histogram from an image

let's suppose following is the histogram for which normalised area has to be estimated:

   ![5000_corr_train](https://user-images.githubusercontent.com/104511030/204223580-cab92d1d-3edf-4740-a32f-de29a3917429.png)

Normalised area, mathematically is given by 
          (x0y0 + x1y1 + x2y2 + x3y3 + ...)/(y1 + y2 + y3 + y4 + ......)
          where xi denotes the x-value of the mid of each bin and yi denotes the y-value of the top of each bin

* Note: The area is getting estimated from an image of histogram which requires the knowledge of image processing to understand the code provided
