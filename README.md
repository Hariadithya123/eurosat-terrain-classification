# EuroSAT Terrain Classification (TensorFlow - Google Colab)

This project classifies satellite images into 4 types of terrain using TensorFlow. It runs on Google Colab and saves results to Google Drive.

## Classes Used
- Forest 🌳
- Highway 🛣️
- River 🌊
- Residential 🏘️

## What It Does
- Downloads the EuroSAT dataset
- Keeps only 4 selected classes
- Builds and trains a deep learning model (EfficientNetB0)
- Saves:
  - Trained model
  - Accuracy plot
  - Confusion matrix
  - Classification report
- Lets you upload an image and shows the prediction

## How to Use
1. Open the notebook in Google Colab
2. Mount your Google Drive
3. Run all cells one by one
4. Upload an image to test the model

## Output Files (Saved in Drive)
- `eurosat_tf_model.h5` (model)
- `accuracy_plot.png`
- `confusion_matrix.png`
- `classification_report.txt`

## Example Prediction
Prediction: Residential (97.65%)

## Tools Used
- TensorFlow
- Google Colab
- EuroSAT Dataset

## Author
Hari Adithya v
Made with ❤️ using Python and Colab.
