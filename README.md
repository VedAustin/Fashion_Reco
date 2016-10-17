# Fashion_Reco
Deep Learning: Simple implementation to visualise effectiveness of transfer learning

### Summary
A simple script to identify similar images using deep learning api.

### Description:
Image analysis via computer vision is getting increasingly better thanks to advances in deep learning. Prior to deep learning, some common algorithm alternatives I had been using to classify images were logistic regression, SVMs and doing some PCA preprocessing if necessary. They were quick to prototype, didnt require GPUs and mostly worked. However advances made in CNNs are too hard to ignore especially when you are looking for the next break through in image recognition, although deep learning is finding its way in other application areas as well. 

A lot of the big tech companies have recently open sourced their deep learning libraries including Facebook, Google, Amazon, Microsoft, Samsung, Baidu to name a few. A critical requirement to run any of their libraries is hardware - particularly GPUs, although you can play with toy sized datasets with regular CPUs. Another major requirement is training the network with lots of data and building several hidden layers and soon you will reach the limitation of your low power laptop spec. 

Another option is to do transfer learning from pre trained models where the biggest advantage is you dont require a lot of data from your end to build a great model. Luckily in addition to using this option, there are also 3rd party apis like Indico, that I used here, that will do all the heavy lifting for you using infrastructure from their end. 

### Data (*amazon-fashion-women-new*):
I used women's clothing as a basis here because of the sheer breadth of catalogue of different images. The images were directly downloaded from the amazon website using a handy tool from the Chrome store. The images roughly fall in the following categories: 

1. dresses, 

2. jumpsuits/overalls, 

3. maternity, 

4. uniforms/work & safety, 

5. fashion hoodies/sweat shirts

Approximately 50 images from each category (~ 250 total images) were downloaded and used for training purposes. A small portion of the dataset (~14) was used for testing purposes. 

### Jupyter Notebook Script (*Amzn_dress_recommendation.ipynb*)
This script with only a few lines of code demonstrates the effectiveness (visual inspection) of deep learning via 3rd party api's. 




