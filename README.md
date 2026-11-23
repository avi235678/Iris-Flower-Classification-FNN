Iris Flower Classification using FNN



Project Overview



This project uses a Feedforward Neural Network (FNN) to classify Iris flowers into three different species based on their measurements.



The model is developed using Python, TensorFlow and Keras.



Dataset Information



The Iris dataset contains 150 records and 4 input features.



Input Features



\- Sepal Length

\- Sepal Width

\- Petal Length

\- Petal Width



Target Classes



\- Setosa

\- Versicolor

\- Virginica



Technologies Used



\- Python

\- NumPy

\- Pandas

\- Matplotlib

\- Seaborn

\- Scikit-learn

\- TensorFlow

\- Keras

\- Jupyter Notebook



FNN Architecture



The neural network contains the following layers:



1\. Input Layer – 4 features

2\. Hidden Layer 1 – 16 neurons (ReLU)

3\. Hidden Layer 2 – 8 neurons (ReLU)

4\. Output Layer – 3 neurons (Softmax)



Model Configuration



\- Optimizer: Adam

\- Loss Function: Sparse Categorical Crossentropy

\- Metrics: Accuracy

\- Epochs: 50

\- Batch Size: 8



Model Performance



\- Total Dataset Records: 150

\- Training Records: 120

\- Testing Records: 30

\- Test Accuracy: 80%

\- Test Loss: 0.3376

\- Total Parameters: 243



Prediction Example



The model successfully predicted the following flower:



Input Measurements:



\- Sepal Length: 5.1

\- Sepal Width: 3.5

\- Petal Length: 1.4

\- Petal Width: 0.2



Predicted Species: Setosa



Project Files



\- "Iris\_FNN\_Classification.ipynb" – Project implementation

\- "iris\_fnn\_model.keras" – Trained FNN model

\- "iris\_scaler.pkl" – Saved feature scaler

\- "requirements.txt" – Required Python libraries

\- ".gitignore" – Files excluded from Git



Conclusion



This project demonstrates how a Feedforward Neural Network can be used for multi-class classification. The model learns patterns from flower measurements and predicts the corresponding Iris species.


Trained Model Files

The trained model files are not included in this repository because of GitHub file size limitations.

The following files are part of this project:

--- iris_fnn_model.keras - Trained Feedforward Neural Network model.
--- iris_scaler.pkl - Scaler used for input data preprocessing.

NOTE :- To use the model for prediction, train the model using the provided Jupyter Notebook to generate the required files.

