Over-the-Top Compliment Generator

This is an entertaining project that generates over-the-top compliments based on an uploaded image. The application uses image processing to analyze the image, detects features such as smiles and dominant clothing colors, and based on these features, it generates a personalized compliment using a language model.

This is a project that takes an image, checks if the person in the image is smiling and identifies the dominant color of his clothes, and then produces a compliment through a language model. It is all about giving people light-hearted positive feedback.

Personalized Compliments: Generates unique, fun compliments based on detected features.


Setup and Installation

Prerequisites

Python 3.7 or later

Google Colab or a local environment supporting Jupyter notebooks


Installation

1. Clone the repository or download the script.


2. Open the script in Google Colab or your local Python environment.



Install the required packages

Run the following command in your environment:

!pip install gradio transformers torch opencv-python scikit-learn

Usage

1. Run the Program: Run the script to start the application.


Open Gradio Interface; after you run the script successfully it opens a web interface featuring an upload button.

Third Step: Upload An Image; upload a photograph so that it uses the application to analyze smile and colour on clothing.

Fourth Step: Get Compliment. The application will now bring out a personal compliment given the analysis result.

____________

Technologies Used in the Project

Python will be used as the code language in the project.

OpenCV: It used image processing and feature extraction.

Hugging Face Transformers: This is used as the text compliments' generative model.

Scikit-learn: It used KMeans clustering to detect color.

Gradio: For creating a simple and interactive frontend.

 
Acknowledgements

This project was supported with resources from:

Hugging Face for the language model API

OpenCV and scikit-learn for image processing

Gradio for the user interface.
