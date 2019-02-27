# Color-Compressor-GUI
Uses the K-means clustering algorithm to compress images in terms of both size and amount of colors to K colors with a simple and intuitive user interface.
![K-means clustering algorithm](https://i.imgur.com/n7rjeTE.png)

(From Andrew Ng)

# Sample Usage
![Example](https://i.imgur.com/2qyp4aT.png)

Built in file system support for opening and saving images
![Example2](https://i.imgur.com/j6TUxEL.png)

Currently only accepts raster images (.jpg, .png, .jpeg) files up to 8 megapixels. Handles basic user error checking. Does not support images with transparent pixels and works best with images that do not have a solid background. 

Here we show using the application with different K values. 
![Penguins](https://i.imgur.com/G9FfXN8.png)

# Upcoming 
Due to user feedback, we are currently working on implementing a crop function as well as the ability to modify the K colors that the algorithm chose. These will be released at a later time and our progress can be seen on various different branches. 

This application was written by Tiffany Do with minor bug fixes and help from Dylan Yu and Seong Ioi Wang. Image preprocessing was provided by Vibhav Gogate at UT Dallas. 
