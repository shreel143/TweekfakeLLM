# TweepFakeLLM: AI vs. Human Comment Classifier

## Overview 
Utilizing Large Language Models (LLMs) to distinguish between AI-generated and human-generated comments in the TweepFake dataset, aiming to bolster online authenticity.

## Features
- **Data Preprocessing**: Prepare the TweepFake dataset for model training.
- **Model Training**: Use LLMs for accurate classification.
- **Real-Time Classification**: Interface for instant comment classification.

## Quick Start

### Prerequisites
Ensure you have Python 3.8 or newer, along with PyTorch, Transformers, Pandas, and Numpy installed.

### Setup
Clone the repository and install dependencies:
```bash
git clone https://github.com/shreel143/ai-vs-human-comment-classifier.git
cd ai-vs-human-comment-classifier
pip install -r requirements.txt
```

### Usage
To preprocess data, train the model, and classify comments:
```bash
python preprocess_data.py
python train_model.py
python classify_comment.py --comment "Your comment here"
```

## Contributing
We welcome contributions. For significant changes, please email us at shreeltrivedi2020@gmail.com to discuss what you'd like to change or add.

## License
This project is open source, available under the MIT License.

## Contact
Questions or contributions? Email us at shreeltrivedi2020@gmail.com.
