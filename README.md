# Running-Arm-Motion-Classification
A motion pattern recognition system with machine learning capabilities. System relies on rotation angle and speed to classify arm motions in running.

This code modifies the EmbeddedML system developed by Charles Zaloom.

Key modifications include:
- Using the gyroscope data source for recognizing a motion pattern consisting of two rotations instead of one.
- Using the event timing data source as a feature for classifying motion patterns.
- Creating a user interface for training and executing a system for classifying arm motions in running.
