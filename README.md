Project Description: CNN–RNN Hybrid Model for Handwritten Digit Recognition
 This project implements a hybrid deep learning model that combines Convolutional Neural Networks (CNN) and Recurrent Neural Networks (RNN with LSTM) to recognize handwritten digits (0–9).
 The MNIST dataset contains 70,000 grayscale images of size 28×28 pixels. The images are first normalized and reshaped before being fed into the model.
 Model Architecture:
   CNN Layers (Feature Extraction)
   Convolutional layers detect edges, curves, and digit patterns.
   MaxPooling reduces spatial dimensions.
   Output feature maps capture spatial structure of digits.
   Reshape Layer
   Converts CNN feature maps into sequential format.
   Treats extracted features as a sequence for temporal learning.
   LSTM Layer (Sequence Learning)
   Learns dependencies within extracted feature sequences.
   Improves pattern understanding across digit strokes.
   Fully Connected Layers
   Dense layers perform classification.
   Softmax activation outputs probability for 10 digit classes.
Performance Metrics:
   Model evaluation includes:
   Accuracy → Overall correct predictions (Expected: 97–99%)
   Confusion Matrix → Shows correct & incorrect classifications per digit
   Precision → Correct positive predictions
   Recall → Ability to detect actual positives
   F1-Score → Balance between precision and recall

Thanks to CodeAlpha that i was able to get my hands on on the project handwritten recognition using CNN and RNN in ML
Author - SEELAM SULOCHANA
   
