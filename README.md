# Content-based-fashion-Image-Retrieval-using-deep-neural-networks
Developing 2 neural network models to retrieve similar fashion images: From data collection to evaluation of the model

# Data Collection
This involves scraping product images from 6 categories- Men's Shirts, T-Shirts, Ladies Tops, Kis's Dresses, Ladies Bags and Shoes from 'Flipcart' e-commerce website.

# Model Development

2 deep neural models- Convolutional Autoencoder from scratch and Triplet network using pre-trained Resnet50 backbone is developed. The raw images are pre-processed, split into training, validation and test datasets and trained, validated and fine-tuned using these models and evaluated for mean average precision.

10 most similar images were retrieved for each image in the unseen test dataset.
