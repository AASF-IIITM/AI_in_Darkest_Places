# AI_in_Darkest_Places
Steps to be followed:
1. Take an image in dark.
2. Now, pass this image through the deep learning model trained for this task.
3. Output image will be bright.

This can be done using traditional image processing techniques like increasing the brightness and contrast of image. But this process may not produce desired results. 
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
