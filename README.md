# 🐶 Use a Pre-trained Image Classifier to Identify Dog Breeds

## 🌟 Project Overview

This project is part of the Udacity AI Programming with Python Nanodegree and Accenture scholarship. It leverages a pre-trained image classifier to accurately identify dog breeds as part of the registration process for a citywide dog show. By using Python and pre-trained CNN models, this project aims to ensure that each participant registered is indeed a dog and to help correctly identify each dog's breed.

### Goals:
- Utilize a Python-based image classifier to verify dog breeds. 🐕
- Evaluate various CNN architectures (AlexNet, VGG, ResNet) to determine the most effective model for breed classification. 🏆
## 🚀 Installation and Setup

### Prerequisites
- Python 3.x 🐍
- Pip (Python package installer) 📦

### Setting Up the Project
1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/Use-a-Pre-trained-Image-Classifier-to-Identify-Dog-Breeds.git
   cd Use-a-Pre-trained-Image-Classifier-to-Identify-Dog-Breeds

### Usage
`python test_classifier.py --dir <directory_with_images> --arch <model_architecture>`

```<directory_with_images>: The path to the directory that contains the images to be classified. 📁```
```<model_architecture>: The CNN architecture to use (options: 'AlexNet', 'VGG', 'ResNet'). 🧠```

### 📂 File Descriptions
`classifier.py`: Contains the function to classify images using different CNN models. 🔍
`test_classifier.py`: Provides an example of how to use the classifier function. 📖
`requirements.txt`: Lists all the dependencies required for the project. 📋