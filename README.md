# Image Caption Generating

## Project Overview  
The **Image Caption Generating** system generates short, descriptive captions for images by understanding their semantics using multiple pretrained models. This system is designed to generate captions that not only describe the objects within the image but also capture the context and relationships between them.

## Key Features  
- Generates captions for images by interpreting their content.  
- Utilizes pretrained models such as Xception, Bidirectional LSTM, and Glove embeddings for improved accuracy and performance.  
- Offers a simple and intuitive GUI for easy interaction with the model.  

## Technologies Used  
- **Python**: For the backend and processing logic.  
- **TensorFlow Framework**: For building and training deep learning models.  
- **Xception Pretrained Model**: For feature extraction and image understanding.  
- **Bidirectional LSTM**: For sequence modeling and generating captions.  
- **Glove Pretrained Weights**: For word embeddings and improving semantic understanding.  
- **GUI**: For providing a user-friendly interface for interaction.

## Dataset  
The dataset used for this project is from [Kaggle's Image Captioning Dataset](https://www.kaggle.com/dataset-link). You can download the dataset and place it in the appropriate directory for training.

## How It Works  
1. **Image Upload**: Users can upload an image through the GUI.  
2. **Feature Extraction**: The image is processed using the Xception model to extract relevant features.  
3. **Caption Generation**: The features extracted from the image are passed through a Bidirectional LSTM network to generate a relevant caption.  
4. **Output**: A short caption describing the image is generated and displayed on the GUI.

## Installation and Setup  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/YourUsername/Image-Caption-Generating.git  
   cd Image-Caption-Generating  
2. Install required libraries:
   ```bash
   pip install -r requirements.txt  
3. Download the dataset from Kaggle:
   https://www.kaggle.com/datasets/nunenuh/flickr30k/code
   Unzip the dataset and place it in the appropriate directory.
4. Run the application:
   ```bash
   python app.py
## Dataset
The dataset used for this project can be downloaded from [Kaggle's flickr30k Dataset](https://www.kaggle.com/datasets/hsankesara/flickr-image-dataset). Download and place it in the `data/` folder for training.
