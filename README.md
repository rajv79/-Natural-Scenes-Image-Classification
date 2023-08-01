# -Natural-Scenes-Image-Classification
# Deep Learning Image Classification with Inception TensorFlow Model

This project aims to classify images of natural scenes into six categories: buildings, forests, glaciers, mountains, seas, and streets using a deep learning model based on the Inception TensorFlow transfer learning model from TensorFlow Hub. The Intel_image_classification dataset is used for training and evaluation.

## Dataset

The dataset consists of approximately 25,000 images of size 150x150. It is divided into three subsets:
- Training: 14,000 images
- Testing: 3,000 images
- Prediction: 7,000 images

## Model Development

The deep learning model is built using the Inception TensorFlow transfer learning model from TensorFlow Hub. Transfer learning allows us to leverage the pre-trained Inception model's feature extraction capabilities and fine-tune it for our specific image classification task.

## Preprocessing

Prior to feeding the images into the model, the dataset is preprocessed to ensure compatibility with the input layer of the Inception model. This involves resizing the images to 150x150 pixels and any other necessary transformations to optimize the training process.

## Evaluation

The model's performance is evaluated using various classification metrics, including accuracy, precision, recall, and F1-score. A classification report is generated to provide insights into the model's performance for each of the six categories.

## Practical Applications

This project demonstrates a practical application of deep learning in image classification, which can be utilized in various real-world scenarios. One such scenario is automatic tagging of natural scene images for easier organization and search, making it valuable for image management systems and photo-sharing platforms.


Happy classifying  -vivek_raj
