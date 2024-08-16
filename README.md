# Petals-to-the-Metal-Classification

## Objective
The goal of this competition is to build a machine learning model that can classify 104 different types of flowers based on images. The dataset is provided in TFRecord format, which is commonly used for efficient data handling in TensorFlow. The competition evaluates models based on the macro F1 score, which takes into account the performance across all classes.

## Dataset
The dataset consists of images of flowers drawn from five different public datasets.
Each image is labeled with one of 104 flower classes.
The dataset has imperfections, such as flowers appearing in unusual contexts, which adds to the challenge of classification.

## Challenges
Class Imbalance: Some classes may have significantly fewer examples than others.
Noisy Data: Images might contain backgrounds or objects that can distract the model.
High Intra-Class Variability: Different images of the same flower type might look very different due to variations in lighting, angle, and background.

## Evaluation Metric
The macro F1 score is used as the evaluation metric. This metric calculates the F1 score for each class independently and then averages them. It gives equal weight to all classes, regardless of their size.
