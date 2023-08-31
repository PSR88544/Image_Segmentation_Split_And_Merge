# Image_Segmentation_Split_And_Merge

## Introduction
Image segmentation is a process of dividing a digital image into multiple segments, also known as regions or objects. The goal of image segmentation is to simplify and change the representation of an image into something that is more meaningful and easier to analyze. Image segmentation can be used for many applications, such as locating objects and boundaries, measuring tissue volumes, diagnosing diseases, planning surgeries, and detecting faces. Image segmentation works by assigning a label to every pixel in an image, such that pixels with the same label share certain characteristics, such as color, intensity, or texture. The result of image segmentation is a set of segments that collectively cover the entire image, or a set of contours extracted from the image. Image segmentation can be done using various techniques, such as clustering, edge detection, thresholding, region growing, and neural networks. One of the most popular techniques for image segmentation is semantic segmentation, which detects the class of the object that each pixel belongs to. For example, semantic segmentation can label each pixel as sky, road, car, person, etc. Semantic segmentation can be done using deep neural networks that learn to extract features and classify pixels from large amounts of labeled data. Semantic segmentation can achieve high accuracy and flexibility for complex images. Split and merge segmentation is an image processing technique used to segment an image. The image is successively split into quadrants based on a homogeneity criterion and similar regions are merged to create the segmented result. The technique incorporates a quadtree data structure, meaning that there is a parent-child node relationship. The total region is a parent, and each of the four splits is a child.

## Algorithms
1. Define the criterion to be used for homogeneity. This could be, for example, the average intensity of the pixels in a region, the standard deviation of the intensities, or the entropy of the intensities.
2. Split the image into equal size regions.
3. Calculate the homogeneity for each region.
4. If the region is homogeneous, then merge it with neighbors.
5. The process is repeated until all regions pass the homogeneity test.

## Output 
![Output](https://github.com/PSR88544/Image_Segmentation_Split_And_Merge/blob/main/Images/seg%20output.jpg)
