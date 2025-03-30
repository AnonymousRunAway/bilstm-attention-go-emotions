# GoEmotions: Emotion Classification using Transformers and BiLSTM+Attention

## Overview
GoEmotions is a dataset developed by Google containing 58k Reddit comments labeled with 27 emotion categories and neutrality. This project leverages the GoEmotions dataset to build an **emotion classification model** using:
- **BiLSTM with Attention**

The goal is to create a robust model that can accurately detect emotions in text, aiding in applications like sentiment analysis, mental health monitoring, and conversational AI.

## Features
- Multi-label emotion classification
- Comparison between Transformer models and BiLSTM+Attention
- Custom model training and evaluation pipeline
- Fine-tuning on the GoEmotions dataset

## Dataset
The dataset consists of:
- **58k** labeled Reddit comments
- **27 emotions** + neutral label
- Multi-label classification (a comment can have multiple emotions)

Download the dataset from the [GoEmotions repository](https://github.com/google-research/google-research/tree/master/goemotions).

## Installation
Clone the repository and install dependencies:
```bash
git clone https://github.com/yourusername/goemotions-project.git
cd goemotions-project
pip install -r requirements.txt
```

## Model Implementations
### 1. Transformer-based Model (BERT)
Fine-tunes a pre-trained **BERT-based** model on GoEmotions for multi-label classification.

### 2. BiLSTM + Attention
Implements a **Bidirectional LSTM** with **self-attention** to capture contextual information effectively.
To run the training, run this notebook in google colab.

## Results
| Model           | Accuracy | F1 Score |
|----------------|----------|----------|
| BERT           | XX%      | XX%      |
| BiLSTM+Attention | XX%    | XX%      |

## Applications
- **Mental health analysis**: Detect emotions in conversations.
- **Chatbots & Virtual Assistants**: Improve empathetic responses.
- **Customer sentiment analysis**: Understand user emotions in feedback.

## Future Work
- Experiment with **XLNet, RoBERTa** for improved classification.
- Integrate real-time inference API.
- Extend to multilingual emotion classification.

## Contributing
Feel free to fork the repo, raise issues, or submit PRs for improvements!

## License
This project is licensed under the MIT License.

## Acknowledgments
- Google Research for the GoEmotions dataset.
- NLP research community for valuable insights.

