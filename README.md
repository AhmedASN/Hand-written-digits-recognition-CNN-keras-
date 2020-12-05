# Hand-written-digits-recognition-CNN-keras
MNIST ("Modified National Institute of Standards and Technology") is the de facto “hello world” dataset of computer vision.
We use two convolutional neural networks, one is based on Conv2D and the other on SeparableConv2D from Keras.

## Data:
The data file train.csv contain gray-scale images of hand-drawn digits, from zero through nine.

Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total. Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. This pixel-value is an integer between 0 and 255, inclusive.

![](https://github.com/AhmedASN/Hand-written-digits-recognition-CNN-keras-/blob/main/Number%20of%20digit%20classes.png)

The  data set, (train.csv), has 785 columns. The first column, called "label", is the digit that was drawn by the user. The rest of the columns contain the pixel-values of the associated image.

![](https://github.com/AhmedASN/Hand-written-digits-recognition-CNN-keras-/blob/main/samples.png)

Each pixel column in the training set has a name like pixelx, where x is an integer between 0 and 783, inclusive. To locate this pixel on the image, suppose that we have decomposed x as x = i * 28 + j, where i and j are integers between 0 and 27, inclusive. Then pixelx is located on row i and column j of a 28 x 28 matrix, (indexing by zero).
