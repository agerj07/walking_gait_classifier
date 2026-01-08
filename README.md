# walking_gait_classifier
Classify gait phases for patients into one of six labels: Loading Response, Midstance, Terminal Stance, Preswing, Initial+Mid Swing, or Terminal Swing.

Used Raspberry Pi and Python to collect data from dual shank 3-axis IMUs and run the model locally.
Collected and labeled 25 unique walking cycles across 5 participants.
Implemented SMOTE-Tomek for class balancing. 
Converted model to ONNX runtime to optimize inference achieving a 75% speedup.

Created a hybrid LSTM-CNN (long short-term memory, convolutional neural network) architecture in PyTorch.
Achieved an accuracy of 0.80 and macro avg. f1 score of 0.80.
Future Considerations: Dealing with class overlap.

(Raspberry Pi code for collecting data and implementing model locally not availble in this repo)
