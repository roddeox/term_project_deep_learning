In the folder classifier, sign_language_classifier.ipynb was used to train the CNN classifier. hands_model_cnn.pth are the trained weights.

  
In the folder mediapipe, hands.ipynb was used to train the Mediapipe's extracted landmarks classifier. hands_model.pth are the trained weights.

  
In the yolov5 folder, the yolo5 model is located. The results of running the model are in the runs folder. "signlanguage-abcde.v1i.yolov5pytorch" was the dataset used for training the yolo.

  
In the dataset folder, the scripts related to managing the dataset for the classifiers are included.


The requirements to use the cnn and mediapipe classifiers are in requirements_cnn_mediapipe.txt and to use the yolo are in requirements_yolo.txt.


The original dataset for the classifiers in the .npy format is not included here because of it's size. It can be downloaded directly from: 27 Class Sign Language Dataset (https://www.kaggle.com/datasets/ardamavi/27-class-sign-language-dataset).
