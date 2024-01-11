# Siamese Networks for Metric Learning

## Overview
This assignment involves preparing image data for a Siamese Network model. The tasks include data splitting, loading, preprocessing, and creating image pairs for model training.

## Image Data Loading and Preprocessing
- Load images from the dataset and preprocess them by cropping and resizing.
- Normalize pixel values to the range [0, 1].

## Shape Inspection
- Inspect the shapes of the loaded data and labels for consistency.

## Image Pair Creation
- Create positive and negative pairs of images for the Siamese Network.

## Model Definition
- Define the main Siamese Network model with necessary layers and functions like `euclidean_distance`.
- Compile the model with a contrastive loss function and an optimizer.

## Training Configuration
- Set hyperparameters like epochs, batch size, and margin for the contrastive loss.
- Train the model with the defined configuration.

## Results Visualization
- Plot accuracy and loss metrics.
- Visualize predictions on test data pairs.