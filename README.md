# Rot Check-A Carrot Classifier

**Rot Check** is a machine learning-based web application that classifies images of carrots, determining whether they are suitable for packaging or not. This project uses a **Convolutional Neural Network (CNN)** model to process the images and make predictions. Users can upload carrot images via a simple web interface, and the application will return a classification based on the pre-trained model.

The goal of this project is to **automate the quality assurance process** for carrot packaging, reducing human error and improving efficiency. Additionally, the application learns from user feedback to improve its predictions over time.

## Features

- **Image Upload**: Users can upload images of carrots.
- **Real-time Classification**: The machine learning model processes the image and returns a classification.
- **Web Interface**: Built using **Flask**, providing an easy-to-use interface.
- **Model Accuracy**: Trained on a dataset of carrot images to ensure accuracy in predictions.
- **User Feedback**: Users can provide feedback by selecting whether the classification result was correct or not. This feedback helps improve future iterations of the model by allowing it to learn from the input.
  
## Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Flask
- **Machine Learning**: Python, TensorFlow (CNN Model)

## How to Use

1. Open the application in your browser (`http://localhost:5000`).
2. Upload an image of a carrot.
3. The model will classify whether the carrot is suitable for packaging or not.
4. After the classification, you will be asked to confirm if the result was correct. You can select whether the classification was correct or not.
5. The application will learn from your feedback, and over time, its predictions will improve.

