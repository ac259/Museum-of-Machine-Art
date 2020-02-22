# Museum of Machine Art
This repository explores the different ways to generate machine art, particularly style transfer. Implementations of optimization based style transfer and the fast style transfer methods. For More information, check out the [Wiki](https://github.com/ac259/Museum-of-Machine-Art/wiki)

## Usage
Run the ipython notebook -> provide style image and content image.

-------------------------------
## Notes.
The Style transfer - using optimization is working.
I could not get the Fast style transfer to work - Initial dataset used -> `COCO training 2014` - 80k training images. 

## References:
I have taken references from a couple of other implementations,
1) `Keras` official implementation of style transfer : \
https://github.com/keras-team/keras/blob/master/examples/neural_style_transfer.py
2) https://medium.com/tensorflow/neural-style-transfer-creating-art-with-deep-learning-using-tf-keras-and-eager-execution-7d541ac31398

## Notes:
Fast Style Transfer
I could not get my implementation to work - for checking the outputs I ran the existing implementation of fast style transfer. This was run on the `VOC Pascal dataset`. The link of the implementation executed is https://github.com/lengstrom/fast-style-transfer.
The outputs from this are in the fast-style-tranfer-repo.
