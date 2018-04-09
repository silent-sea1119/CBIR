# CBIR
My efforts to create a google photos like classifier because why not.


## Motivation

Ever since my CBIR project back in grad school, I've wanted to build a CBIR system that would classify my pictures and learn just like Google Photos does. I've also wanted very badly, to implement [this paper](https://cs.stanford.edu/people/karpathy/deepimagesent/)

However lets start small. This is the MVP:
 1. Create a web interface to upload pictures
 2. Track them with a DB and archive them in a set location
 3. Run the images via a face detection kernel
 4. Detect faces and label them like you would in Facebook and Google Photos
 
 
The next list is a little more ambitious:
 1. Create a multi platform app to do that (qt/js-Electron)
 2. Create a phone app that would allow you to do that
 3. Implement the paper and generate image descriptors and index them
 4. Update interface to allow queries like: "image where: dad standing in front of mountains" or "images where: all of us"r
 
 
## Requirements:

1. Django to create the interface
2. Postgres db
3. Django rest framework
4. OpenCV3/Python3 or C++ if it's the better documented library
5. Scikit-learn and Tensorflow to explore image classification

