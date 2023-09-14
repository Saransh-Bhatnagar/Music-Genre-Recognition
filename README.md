# Music-Genre-Recognition
The project uses Deep Learning techniques, specifically Artificial Neural Networks, to recognize music genres. The dataset used in this project is the GTZAN dataset which consists of features extracted from 10 different music genres, with 100 songs of 30 seconds each. These songs are further divided into 10 parts of 3 seconds each for analysis.

## Dataset Used

We trained our Music Genre Recognition model using the GTZAN dataset. You can download and get more information about the dataset from [here](https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification).

## Technologies Used

This project was built using the following technologies and tools:

- **Python:** The core programming language used for development.
- **Librosa:** A Python library for audio and music analysis.
- **Scikit-learn:** A machine learning library for building and evaluating models.
- **Jupyter Notebook:** An interactive development environment used for data analysis and model training.
- **Google Colab:** A cloud-based platform for running Jupyter Notebooks and collaborating on projects.
- **Pandas:** A data manipulation library used for handling datasets.
- **NumPy:** A library for numerical operations and data manipulation.
- **Matplotlib:** A plotting library used for creating visualizations.

## How to Identify the Genre of Your Own Audio Clip

Follow these steps to identify the genre of your own audio clip using our Music Genre Recognition model:

### Step 1: Extract Features from Your Audio Clip

1. Open the `dataman.ipynb` notebook in your Jupyter environment.
2. Upload your audio clip to the notebook.
3. Run the code in the notebook. This code will extract all the necessary features from your audio clip.
4. The extracted features will be saved in an Excel file named `testing.csv`. You can download this file.

### Step 2: Predict the Genre

1. Open the `music_genre_recognition.ipynb` notebook in your Jupyter environment.
2. Upload the `testing.csv` file that you obtained in Step 1.
3. Run the code in the notebook to get predictions from the trained model.
4. The model will predict the genre of your audio clip.

For subsequent files after the model has been trained, you can directly run the prediction part of the code.

## Model Performance and Limitations

Our music genre classification model has achieved an impressive accuracy rate of 93% on our testing dataset. However, it's important to note that even with this high accuracy, the model may still misclassify songs in certain cases.

### Why Misclassifications May Occur

Misclassifications can occur due to various factors:

- Variations in genre characteristics: Some songs may exhibit characteristics that overlap with multiple genres, making them challenging to categorize accurately.
  
- Subtle differences in audio features: Certain genres may share similar audio features, leading to confusion in classification.
  
- Complexity of genre boundaries: Music genres can be subjective and fluid, with no strict boundaries. Songs that experiment with genre blending can pose classification challenges.

### Real-World Scenarios

In real-world scenarios, misclassifications might be more common for songs that:

- Blend multiple genres or incorporate unconventional elements.
  
- Are at the fringes of traditional genre definitions.
  
- Contain unique or experimental musical compositions.




