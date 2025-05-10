Face Recognition System

Implemented a face recognition system using a CNN based on the LeNet architecture.

Unpickled and loaded grayscale face images and corresponding labels from serialized files.

Applied preprocessing including histogram equalization, normalization, and reshaping of images.

Encoded labels using LabelEncoder and converted them to one-hot format.

Built a CNN using Keras with convolutional, pooling, and dense layers ending in a softmax output.

Trained the model using categorical cross-entropy loss and the Adam optimizer.

Evaluated model performance using accuracy, loss plots, confusion matrix, and classification report.

Visualized training/validation metrics to monitor performance and generalization.

Saved the trained model as final_model.h5 for future inference or deployment.

Tech Stack
Python, NumPy, OpenCV, Matplotlib, Seaborn, TensorFlow, Keras, Scikit-learn, Pickle

