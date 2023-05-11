# Deep-Learning-Project
# Andy Ebenbach and Kieren Gill

__Project Description:__

Problem Statement: The goal is to develop a deep learning model capable of accurately detecting breast cancer in mammograms, enabling earlier detection and improved patient outcomes.

Solution Approach: Our approach combines transfer learning, region of interest (ROI) cropping, and a hybrid model of object detection and convolutional neural networks (CNNs) to achieve accurate breast cancer detection. We used CAM-Grad to help with the interpretability of the model. 

Value/Benefit: The developed model has the potential to significantly enhance breast cancer detection, reducing false negatives, and ultimately leading to more effective treatment and higher survival rates.


__Code Structure__

This repo has 5 files:
- preprocessing.ipynb: This notebook contains the preprocessing steps that we used for before training our model.
- train-yolo-and-extract-roi.ipynb: This notebook contains our ROI cropping and model training.
- hyperparameter-tuning.ipynb: This notebook contains our model hyperparameter tuning.
- grad-notebook.ipynb: This notebook contains the CAM-grad code, which helps with the interpretability of the model.

When running the files, be sure to run them in the order as demonstrated above. Some example commands to run the files are as follows:


Here are our results and observations:
![Image 1]([https://github.com/kierengill/Deep-Learning-Project/blob/main/readme_images/1.png])
