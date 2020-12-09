# Style-Transfer
In this project, I have created a style transfer method that is outlined in the paper, [Image Style Transfer Using Convolutional Neural Networks](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Gatys_Image_Style_Transfer_CVPR_2016_paper.pdf), by Gatys in PyTorch.

In this paper, style transfer uses the features found in the 19-layer VGG Network, which is comprised of a series of convolutional and pooling layers, and a few fully-connected layers.

## Separating Style and Content
Style transfer relies on separating the content and style of an image. Given one content image and one style image, the aim is to create a new, target image which should contain the desired content and style components:

* objects and their arrangement are similar to that of the **content image**
* style, colors, and textures are similar to that of the **style image**
