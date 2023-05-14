# Cifar10-imageClassification

# Image Classification Project Documentation
Program Screens



1-	 Splash Screen


  










Program Screens



2- Program Screen


  
















Program Screens
	


2- Program Screen (Test)


  
















Program Screens
	


2- Program Screen (Test)


  











# Description

This project implements an image classification model using Convolutional Neural Networks (CNNs) to classify images into 10 different categories.

# Dependencies
•	Python 3.x
•	tkinter
•	PIL (Python Imaging Library)
•	keras
Installation	

•	Install Python 3.x from the official website.
•	Install the required dependencies using the following command: pip install tkinter pillow keras.

# Usage

To use the image classification program, follow these steps:

1.	Run the Python script.
2.	The program will display a splash screen with a loading animation.
3.	Once the loading is complete, the main window will open.
4.	Click on the "Upload Image Here" button to select an image for classification.
5.	The program will classify the image and display the predicted class label.

# Examples

•	Example 1: Uploading an image of a car will classify it as a "car".
•	Example 2: Uploading an image of a dog will classify it as a "dog".
# File Structure

•	main.py: The main Python script that implements the image classification program.
•	assets/: Directory containing images used in the program.
•	model/: Directory containing the pre-trained CNN model for image classification.

# Functions/Classes
•	new_win(): Opens the main window and handles the image classification process.

•	upload_image(): Allows the user to upload an image for classification.

•	show_classify_button(file_path): Displays the "Classify Image" button after an image is uploaded.

•	classify(file_path): Classifies the uploaded image using the pre-trained CNN model.

•	center_window(top, width, height): Centers the main window on the screen.

•	Configuration.

•	There are no specific configuration options for this project.

# Troubleshooting
•	If the program fails to load or crashes, make sure you have installed all the required dependencies.
•	Ensure that the path to the pre-trained model is correct in the code.
Contributions
•	Contributions to this project are welcome. Please follow the guidelines outlined in the CONTRIBUTING.md file.

# License
•	This project is licensed under the MIT License.

# Contact
•	For any questions or support, please contact the project maintainer at alinoorspam@gmail.com.

# Acknowledgements
•	This project was inspired by the CIFAR-10 dataset and the Keras library for deep learning.

# Version History
•	v1.0.0 (2023-05-12): Initial release.
# References
•	Keras Documentation: https://keras.io/
•	CIFAR-10 Dataset: https://www.cs.toronto.edu/~kriz/cifar.html
