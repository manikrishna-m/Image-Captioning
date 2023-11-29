# Image Captioning with Evaluation Metrics

This project involves training an image captioning model using precomputed features and evaluating its performance using two different metrics: BLEU score and cosine similarity.

## 1. Data Preparation

### 1.1 Loading Data

- The COCO dataset is used for training and evaluation.
- Split the dataset into training and validation sets.

## 2. Data Preprocessing

### 2.1 Image Features

- Extract and save image features using a pre-trained CNN model.
- Save the features map for later use.

### 2.2 Tokenization

- Tokenize the captions and build a vocabulary.

## 3. Model Training

### 3.1 Design Decoder RNN

- Design a Recurrent Neural Network (RNN)-based decoder for generating captions.
- Train the decoder using precomputed image features.

## 4. Generate Predictions on Test Data

- Display sample test images with model-generated captions and reference captions.
- Evaluate the model's performance on the test set.

## 5. Caption Evaluation using BLEU Score

### 5.1 Average BLEU Score on All Data

- Calculate the average BLEU score on the entire test set.
- Display a histogram of the distribution of BLEU scores.

### 5.2 Exemplar High and Low BLEU Score Samples

- Display high and low BLEU score examples with model predictions and reference captions.

## 6. Caption Evaluation using Cosine Similarity

### 6.1 Cosine Similarity

- Calculate cosine similarity scores between generated captions and reference captions.
- Display a histogram of the distribution of cosine similarity scores.

### 6.2 Cosine Similarity Examples

- Display examples of high and low cosine similarity scores with model predictions and reference captions.

## 7. Comparing BLEU and Cosine Similarity

### 7.1 Test Set Distribution of Scores

- Compare model performance using BLEU and cosine similarity.
- Discuss strengths and weaknesses of each method.

### 7.2 Analysis of Individual Examples

- Display examples where BLEU and cosine similarity scores are similar and different.
- Discuss the findings and implications.

## Conclusion

- Summarize the project, highlighting key findings and insights.
- Discuss potential improvements and future work.

