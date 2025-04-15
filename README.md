🦴 **Knee Osteoarthritis Severity Prediction from X-ray Images**

Millions of people worldwide are affected by knee osteoarthritis (OA), a prevalent condition involving the deterioration of joint cartilage and underlying bone.
In this project, the important issue of predicting knee OA severity using X-ray images is addressed through the utilization of deep learning models.
Dataset- https://www.kaggle.com/datasets/shashwatwork/knee-osteoarthritis-dataset-with-severity


📁 **Dataset**

X-ray images divided into 3 classes: Healthy, Moderate, and Severe

~500 images per class

Preprocessed and split into training, validation, and test sets

Loaded using Keras ImageDataGenerator

🧠 **Models Used**
Baseline CNN Model

Simple 3-layer CNN architecture

Trained from scratch

Achieved ~79% test accuracy

Deeper CNN

More convolutional layers added to improve feature extraction

Achieved ~83% test accuracy

EfficientNetB5 (Transfer Learning)

Pretrained on ImageNet

Final layer customized for 3-class classification

Currently training and evaluating

📊 **Evaluation Metrics**

Each model is evaluated using:

Accuracy (train, validation, test)

Loss

Confusion Matrix

Classification Report (Precision, Recall, F1-score)

Training/Validation loss and accuracy curves


📈 **Sample Results (So Far)**

	Model | Train Acc | Val Acc | Test Acc | Notes
	Baseline CNN | ~73% | ~79% | ~79% | Simple model, solid results
	Deeper CNN | ~64% | ~68% | 83% | Improved generalization
	EfficientNetB5 | TBD | TBD | TBD | Still training
