# Image-to-Text Generation Project

## Overview

This project focuses on the evaluation of an image-to-text model, exploring the performance through two commonly used metrics: Bilingual Evaluation Understudy (BLEU) score and Cosine Similarity. The model generates textual captions for given images, and its effectiveness is assessed based on both n-gram overlap and vector similarity with reference captions.

## Techniques Used

### Image-to-Text Model

The core of this project is an image-to-text model, designed to generate descriptive captions for input images. The model utilizes convolutional neural networks (CNNs) for image feature extraction and recurrent neural networks (RNNs), specifically Long Short-Term Memory (LSTM) networks, for sequence generation. PyTorch is the primary deep learning framework employed for model development.

### Evaluation Metrics

#### 1. BLEU Score

The BLEU score is a widely used metric for machine translation and text generation tasks. It measures the similarity between the generated caption and reference captions based on n-gram overlap. The evaluation involves comparing the model's predictions against multiple reference captions and calculating the average BLEU score for each image.

#### 2. Cosine Similarity

Cosine similarity is employed to measure the vector similarity between the generated caption and reference captions. This technique involves finding the embedding vector for each word in the caption, computing the average vector for the entire caption, and then calculating the cosine similarity between the generated caption and each reference caption. The average cosine similarity score is obtained for each image.

## Project Structure

The project is structured as follows:

- **1. BLEU Score Evaluation**
  - Subsection 1.1: Average BLEU score on all data.
  - Subsection 1.2: Exemplary high and low BLEU score samples.

- **2. Cosine Similarity Evaluation**
  - Subsection 2.1: Cosine similarity computation.
  - Subsection 2.2: Cosine similarity examples.

- **3. Comparing BLEU and Cosine Similarity**
  - Subsection 3.1: Test set distribution of scores.
  - Subsection 3.2: Analysis of individual examples.

- **4. Model Performance Evaluation Summary**
  - A comprehensive summary comparing the strengths and weaknesses of BLEU score and Cosine Similarity, along with a detailed analysis of the model's performance on the test set.

## Running the Code

Ensure that you have the required dependencies installed, including PyTorch, NLTK, and scikit-learn. The project assumes the existence of a trained image-to-text model.

To evaluate the model using BLEU and Cosine Similarity metrics, run the provided code snippets in the respective sections of the codebase.

## Results and Insights

The project provides valuable insights into the model's strengths and weaknesses, considering both n-gram overlap and semantic similarity. The comparative analysis of BLEU and Cosine Similarity scores offers a nuanced understanding of the model's performance on the test set.

## Future Work

Future iterations of this project could involve fine-tuning the model based on the insights gained from the evaluation. Additionally, exploring other evaluation metrics and incorporating more advanced techniques, such as attention mechanisms, could further enhance the model's performance.

Feel free to explore the code and adapt it for your specific use case. We hope this project serves as a valuable resource for image-to-text generation tasks.
