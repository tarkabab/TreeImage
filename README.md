Requirement

You have to develop, in Scala, a program that allows the user to manipuate images encoded as trees. To make it simple, we will consider only 2n squared-sized images (either in black-and-white, grayscale, or colored). Here’s the idea : an image filled with white only (or with black only) is represented by its unique color, while a composite image is naturally divided into 4 square-sized sub-images : The leaves of a quadtree correspond to a zone of the picture that is filled with a unique color. Inner nodes store the average of the colors of their child nodes.

Basic functions

Write a program that delivers at least the following functionalities :

Charge an image from a .ppm file (portable pixmap file format) into a colored matrix. From this matrix, generate the corresponding quadtree  
Save an image : from a quadtree and a desired image size, generate the corresponding colored matrix.  
Save this matrix into a ppm file.  
On a image that is loaded in memory, allow the following manipulations :
- rotation: 90° clockwise or counter-clockwise
- mirror: reversal left-right and top-bottom
- color reversal  

needs to be done by 19th January 8pm


***
Notes:
- https://en.wikipedia.org/wiki/Netpbm_format
