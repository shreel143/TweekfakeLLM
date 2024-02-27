# TweekfakeLLM: AI vs. Human Comment Classifier

## Overview
This project leverages the capabilities of advanced Large Language Models (LLMs) to accurately classify comments within the TweepFake dataset as either AI-generated or human-generated. Our goal is to enhance the understanding and detection of AI-generated text in social media platforms, contributing to the broader efforts of ensuring authenticity and transparency online.

## Objective
The primary aim of this project is to develop a highly accurate classification system that can distinguish between AI and human-generated comments. This involves training sophisticated LLMs on the TweepFake dataset, which contains a diverse range of comments with varying levels of complexity and style.

## Features
- **Data Preprocessing**: Scripts to clean and preprocess the TweepFake dataset for optimal model training.
- **Model Training**: A detailed pipeline for training LLMs on the processed dataset, including parameter tuning and optimization strategies.
- **Classification Interface**: A user-friendly interface for submitting comments to the model and receiving classifications in real time.
- **Evaluation Metrics**: Comprehensive metrics to evaluate the model's performance, including accuracy, precision, recall, and F1 score.
- **Visualization Tools**: Tools for visualizing the model's decision-making process and the distribution of AI vs. human comments within the dataset.

## Getting Started

### Prerequisites
- Python 3.8 or later
- PyTorch 1.8 or later
- Transformers library
- Pandas
- Numpy

### Installation
1. Clone the repository:
```
git clone https://github.com/shreel143/ai-vs-human-comment-classifier.git
```
2. Install required dependencies:
```
cd ai-vs-human-comment-classifier
pip install -r requirements.txt
```

### Usage
1. Preprocess the dataset:
```
python preprocess_data.py
```
2. Train the model:
```
python train_model.py
```
3. Classify comments:
```
python classify_comment.py --comment "Your comment here"
```

## Contributing
We welcome contributions from the community. Please read our [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on how to contribute to the project.

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments
- TweepFake dataset contributors
- OpenAI for providing access to LLMs
- The AI research community for their continuous support and inspiration

## Contact
For any inquiries or contributions, please contact us at shreeltrivedi2020@gmail.com.
