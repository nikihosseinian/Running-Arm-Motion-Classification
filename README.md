# Running-Arm-Motion-Classification
A motion pattern recognition system that classifies arm motions in running.

System uses a SensorTile sensor to detect motions and an EmbeddedML neural network for its machine learning capabilities. Neural network relies on rotation angle and speed to classify motion patterns.

This code modifies the EmbeddedML system developed by Charles Zaloom.

Key modifications include:
- Using the gyroscope data source for recognizing a motion pattern consisting of two rotations.
- Using the event timing data source as a feature for classifying motion patterns.
- Creating a user interface for training and executing a system for classifying arm motions in running.
