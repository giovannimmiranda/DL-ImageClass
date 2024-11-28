##Deep Learning Project: Image Classification and Object Localization

**Project Overview**

This project is part of the Deep Learning course undertaken during my undergraduate studies. The goal is to design and implement a deep neural network capable of:
	•	Predicting the class of an image (1, 2, or 3) based on the main object it contains.
	•	Predicting the bounding box coordinates for the object in the image.

The dataset consists of 186 labeled images categorized into three classes, with the following inputs:
	•	Input Image: A 227 × 227 × 3 tensor representing RGB images, with pixel values ranging from [0, 255].
	•	Image Label: An integer (1, 2, or 3) indicating the class of the object in the image.
	•	Bounding Box Coordinates: Four integers, (x1, y1) (bottom-left) and (x2, y2) (top-right), defining the object’s bounding box within the image. The values lie in the range [1, 227].

**Task Description**

The primary objective is to design a neural network model capable of performing two tasks simultaneously:
	1.	Classification Task: Predict the class label (1, 2, or 3) for each input image.
	2.	Prediction Task: Predict the bounding box coordinates (x1, y1, x2, y2) for the object within the image.

**Results**

	•	Achieved a classification accuracy of 77% on the test dataset.
	•	Predicted bounding box coordinates with an average MSE of 0.06%.



This project serves as a foundation for developing a more efficient and robust model. There is significant potential for enhancing both the model architecture and the dataset to achieve superior performance. However, such optimizations were beyond the scope and requirements of this specific course.

