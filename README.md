Hand Gesture Recognition
This project focuses on developing a hand gesture recognition system using Convolutional Neural Networks (CNNs). The dataset used for training the model is the Leap Gesture Recognition dataset, which contains images of various hand gestures captured from a Leap Motion Controller.

Dataset Description
The dataset is organized into ten categories, each representing a different hand gesture:

Palm (01_palm)
L (02_l)
Fist (03_fist)
Fist Moved (04_fist_moved)
Thumb (05_thumb)
Index (06_index)
OK (07_ok)
Palm Moved (08_palm_moved)
C (09_c)
Down (10_down)
The dataset is split into training, validation, and testing sets to train and evaluate the CNN model.

Requirements
Python 3.x
NumPy
PIL (Python Imaging Library)
Matplotlib
TensorFlow
Keras
scikit-learn
You can install these dependencies using pip: pip install numpy pillow matplotlib tensorflow keras scikit-learn

Usage
Clone the repository or download the source code. Set up your Python environment with the required dependencies. Run the provided Python script (hand_gesture_recognition.py) to train and evaluate the CNN model.

File Structure
hand_gesture_recognition.py: Python script for training the CNN model. README.md: This file containing project information and instructions.

LICENSE: License information for the project (if applicable).
requirements.txt: List of dependencies for easy installation.

Training the Model
To train the CNN model, run the following command: python hand_gesture_recognition.py The script will preprocess the dataset, build and train the CNN model, and evaluate its performance on the test set.

Results
After training and evaluation, the model's accuracy on the test set is displayed.

License
This project is licensed under the MIT License.
