# Image Caption Generator

This project implements an **Image Caption Generator** using PyTorch. It combines Convolutional Neural Networks (CNNs) for image feature extraction and Recurrent Neural Networks (RNNs) for generating natural language descriptions of images.

## Example

![Example](example_output.jpg)

**Caption:** _"A little girl climbing into a wooden playhouse."_

---

## 🔧 Features

- CNN Encoder (ResNet50) to extract image features
- RNN Decoder (LSTM) to generate captions
- Custom dataset handling with PyTorch `Dataset` and `DataLoader`
- Tokenization and vocabulary building using `nltk`
- Training loop with loss tracking and optimizer
- Compatible with Google Colab and Google Drive

---

## 📂 Dataset

The project uses the [Flickr8k dataset](https://www.kaggle.com/datasets/adityajn105/flickr8k).

**Folder Structure:**
ML_Datasets/
└── archive/
├── Images/
│ ├── 1000268201_693b08cb0e.jpg
│ └── ...
└── captions.txt

📎 Dependencies
Python 3.7+
PyTorch
torchvision
nltk
PIL (Pillow)

**Contributing**
Feel free to fork this repo, open issues, or submit PRs! Collaboration is welcome.
