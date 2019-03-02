# Color-Compressor-GUI
Uses the K-means clustering algorithm to compress images in terms of both size and amount of colors to K colors with a simple and intuitive user interface.
![K-means clustering algorithm](https://i.imgur.com/n7rjeTE.png)

(From Andrew Ng)

# Sample Usage

![](https://i.imgur.com/PihbF4q.png)
Built in file system support for opening and saving images.

In version v1.2, you now have the ability to select the colors chosen by the algorithm and change them to any color desired.
![clusterchanging](https://i.imgur.com/JSfUjJN.png)
![changed](https://i.imgur.com/c5fheli.png)
Additionally, color palette swaps can be undone (Ctrl Z) and redone (Ctrl Y)

Currently only accepts raster images (.jpg, .png, .jpeg) files up to 8 megapixels. Handles basic user error checking. Does not support images with transparent pixels and works best with images that do not have a solid background. 

Here we show using the application with different K values. 
![Penguins](https://i.imgur.com/G9FfXN8.png)

This application was written by Tiffany Do with minor bug fixes and help from Dylan Yu and Seong Ioi Wang. Image preprocessing was provided by Vibhav Gogate at UT Dallas. 
