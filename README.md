
Conversion of images in dark to bright images can be done using deep learning piplines. 
This can also be done using traditional image processing techniques like increasing the brightness and contrast of image. But this process may not produce desired results. 
RAW images can be processed with rawpy. But processing the image using rawpy adds noise into it so we have to apply a deep learning model to make desired outputs.


DATASET:

1. Download the dataset from the below url:
   Sony (25GB)
   https://drive.google.com/file/d/1G6VruemZtpOyHjOC5N8Ww3ftVXOydSXx/view
2. Place the dataset inside the dataset/Sony/ folder.

Requirements:

Tensorflow(>=1.1)
CUDA(>=8.0)
Scipy, Numpy, Rawpy
CuDNN(>=5.0) 
