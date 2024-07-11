# Fashion Product Recommendation System

This project implements a Fashion Product Recommendation System (FRS) using a pre-trained ResNet50 model for feature extraction and the Annoy algorithm for finding similar products. The system allows users to input an image of a fashion product and receives recommendations for similar products.

## Requirements

- Python 3
- TensorFlow
- OpenCV
- NumPy
- Matplotlib
- Pandas
- Annoy
- tqdm

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/fashion-recommendation-system.git
   cd fashion-recommendation-system
   
### 1- Install dependencies:

   
    pip install -r requirements.txt

### 2- Download the Myntra Fashion Product Dataset from Kaggle:
 
    kaggle datasets download -d hiteshsuthar101/myntra-fashion-product-dataset
    unzip myntra-fashion-product-dataset.zip


## Usage
1- Run the fashion_recommendation_system.ipynb notebook to train the model, extract features, and build the recommendation system.

2- Follow the instructions in the notebook to input an image and receive product recommendations.
