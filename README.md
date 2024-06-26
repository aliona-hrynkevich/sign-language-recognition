# Sign Language Recognition
The sign language recognition system is developed based on the “Slovo” video dataset. 100 isolated gestures were selected for recognition. Recognition was carried out based on key points using classical machine learning models and neural networks.

## Results: 
Accuracy 0.61, F1 score 0.61, which is equal to the best result achieved in the original Sberbank paper, but much faster

# Project presentation: sign_recognition_Hrynkevich A_v5.pptx

## Notebooks
- `sign_recognition_data praparation.ipynb`: Exploratory Data Analysis
- `sign_recognition_EDA_data 100.ipynb`: Exploratory Data Analysis
- `sign_recognition_finding_keypoints.ipynb`: Keypoints Extraction
- `sign_recognition_training_20_frames&flipping&+augumentation.ipynb`: Model Training
- `sign_recognition_inferenсe.ipynb`: Model Inference

## Additional files:
- annotations_100.csv: annotation for a dataset with 100 classes
- class_data_2.csv: dictionary to translate class label to class name
- best_model_transformer_v1.pth: weights for the best model

## Links:
- Initial dataset - https://github.com/hukenovs/slovo
- original Sberbank paper "Slovo: Russian Sign Language Dataset" - https://arxiv.org/pdf/2305.14527
