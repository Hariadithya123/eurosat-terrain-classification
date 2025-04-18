# EuroSAT Terrain Classification (TensorFlow - Google Colab)

This project classifies satellite images into 4 types of terrain using TensorFlow and a simple **Gradio interface**. The model is trained on the **EuroSAT dataset** and runs on **Google Colab**. 

Now, you can easily upload an image through a user-friendly interface to predict the terrain type!

## Classes Used
- Highway 🛣️  
- Residential 🏘️  
- River 🌊  
- Jungle 🌳  

## What It Does
- Downloads the EuroSAT dataset
- Filters and keeps only 4 selected terrain classes
- Builds and trains a deep learning model using **EfficientNetB0**
- Saves:
  - Trained model
  - Accuracy plot
  - Confusion matrix
  - Classification report
- Allows you to upload a satellite image and get predictions through a Gradio interface

## How to Use
1. Open the **EuroSAT_Colab_Notebook.ipynb** in **Google Colab**.
2. Mount your **Google Drive** to store and access files.
3. Run all the cells in the notebook:
   - The dataset will be downloaded and preprocessed.
   - The model will be trained.
4. **Use the Gradio Interface**:
   - Once the model is ready, you can use the Gradio interface to upload a satellite image and get a prediction.
   - The prediction will return the terrain class and the confidence percentage.

## Output Files (Saved in Drive)
- `eurosat_tf_model.h5` - Trained model
- `accuracy_plot.png` - Training accuracy plot
- `confusion_matrix.png` - Confusion matrix
- `classification_report.txt` - Model performance metrics

## Example Prediction
Upload a satellite image to the Gradio interface and you’ll get results like:
Prediction: Highway (97.65%)

markdown
Copy
Edit

## Tools Used
- **TensorFlow** for training the model
- **Google Colab** for running the code
- **Gradio** for building the interactive interface
- **EuroSAT Dataset** for satellite images

## Author
Hari Adithya V
Made with ❤️ using Python, TensorFlow, and Gradi
