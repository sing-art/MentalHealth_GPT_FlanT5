# Mental Health Classification with T5 Transformer

This project aims to develop a machine learning model capable of classifying text from Reddit posts into three categories: "suicide," "depressed," and "normal." The primary goal is to identify individuals who may be at risk or struggling with mental health challenges and could potentially benefit from intervention or support.

## Project Motivation

Mental health is a critical concern, and early detection of potential issues can be life-saving. Online platforms like Reddit provide valuable insights into individuals' thoughts and feelings. By leveraging machine learning techniques, we can analyze text data to identify potential signs of mental distress.

## Dataset

The dataset comprises Reddit posts collected and labeled into three categories:

* **Suicide:** Posts indicating suicidal ideation or intent.
* **Depressed:** Posts expressing feelings of sadness, hopelessness, or other symptoms of depression.
* **Normal:** Posts that do not exhibit signs of mental health distress.

The dataset is carefully split into training, validation, and testing sets to ensure robust model evaluation and generalization.

## Model and Methodology

This project employs a T5 Transformer model, a powerful language model pre-trained on a massive text corpus. The model is further fine-tuned specifically for the task of text classification, enabling it to accurately categorize Reddit posts based on their content.

The project leverages the following libraries and tools:

* **pandas:** Data manipulation and analysis.
* **scikit-learn:** Machine learning library for model training and evaluation.
* **datasets:** Library for efficient dataset management and processing.
* **transformers:** State-of-the-art natural language processing library providing access to pre-trained models like T5.
* **accelerate:** Library for optimizing model training and inference.

## Running the Project

The code for this project is designed to be executed in a Google Colab environment. To run the project:

1. Ensure you have a Google Colab account.
2. Open the provided Colab notebook.
3. Install the necessary libraries using the provided `!pip install` commands within the notebook.
4. Execute the code cells in sequential order to load the data, fine-tune the model, and evaluate its performance.
