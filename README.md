# Breast Cancer Prediction Web App

This Python script is a web application for predicting whether a breast tumor is malignant or benign. It utilizes a pre-trained machine learning model for breast cancer classification.

## Dataset

- **Dataset Name**: Breast Cancer dataset
- **Data Source**: upload on git.
- The dataset contains the following attributes:
- **Feature columns**: ["id","diagnosis","radius_mean","texture_mean","perimeter_mean","area_mean","smoothness_mean","compactness_mean","concavity_mean","concavepoints_mean","symmetry_mean","fractal_dimension_mean","radius_se","texture_se","perimeter_se","area_se","smoothness_se","compactness_se","concavity_se","concavepoints_se","symmetry_se","fractal_dimension_se","radius_worst","texture_worst","perimeter_worst","area_worst","smoothness_worst","compactness_worst","concavity_worst","concave points_worst","symmetry_worst","fractal_dimension_worst"]
  
-**Target columns**:['label']

## Project Structure

- **README.md**: Documentation of the project.
- **main.py**: Python script for running the breast cancer prediction web app.
- **model.joblib**: Pre-trained machine learning model for breast cancer classification.

## Setup
1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd breast-cancer-prediction

## Usage
-Clone this repository to your local machine.

-Ensure you have the pre-trained machine learning model ('model.joblib') in the same directory as the script ('main.py').

-Open a command prompt or terminal and navigate to the directory where the script is located.

-Run the script using Streamlit: `streamlit run main.py`

Follow the instructions in the web app to input features and get predictions.

## Model Training
The project uses a machine learning model trained on breast cancer data to classify tumors as malignant or benign. The pre-trained model is saved as 'model.joblib'.

## Input Features
The web app accepts the following input features for making predictions:

Mean Radius
Mean Texture
Mean Perimeter
Mean Area
Mean Smoothness
Mean Compactness
Mean Concavity
Mean Concave Points
Mean Symmetry
Mean Fractal Dimension
... (and additional features for error and worst cases)
## Results
The web app provides predictions for breast cancer based on the input features. The result indicates whether the tumor is malignant or benign.

## Future Improvements
There are several ways to enhance the web app and model:

-Implement a more user-friendly interface.

-Explore and integrate more advanced machine learning models.

-Improve the input validation and error handling.

-Gather more labeled data for improved model accuracy.
## References

-Author: Mirza salman

-Contact: salmansaluu661@gmail.com

Feel free to customize this README to include any additional information you want to provide about the project.
