# Virtual Wardrobe
A proof of concept application of a virtual wardrobe, which is able to scan clothes
and display them on a 3D model of a character. This was achieved by combining C++,
Python as well as Unreal Engine 4. To scan the clothes a Kinect V2 is used.
A C++ class provides easy access to stored clothes and
scanning for new ones. Furthermore, a convolutional neural network was trained to recognize
which category a clothing item belongs to. It recognized the different categories very well
and - for example - had a confidence of around 92% when predicting jeans.
