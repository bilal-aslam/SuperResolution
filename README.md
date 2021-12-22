# SuperResolution
This is a project that improves the image quality by upsacaling it, using machine learning.

The idea is to improve the quality of low quality images. There are different approaches used for this purpose.

Bilinear Approach.
K mean Approach.
Model Prediction.
Ground Truth.
We will be using Model prediction using deep network to train a model to improve image quality.

The first step is to preapare data. We will use google_images_download library for downloading images from internet and then we will use torch.Transform for transforming the downloaded images to lower size and to tensor data structure.

Torch.Tensor is similar to multidimentional matrices in numpy, The advantagae is that it offer better performance in operations and the best part is that it offers GPU computation.

Now we will prepare the dataset for our model. We will divide the dataset into train and test set and transform the images using torch.transform

After training our model we will test it by downscaling an image and then pass it through our model.

We can alwasy increase the dataset for better results.

