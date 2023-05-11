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

__Running Code__

When running the files, be sure to run them in the order as listed above. To run the files, just run the notebooks.

__Results__

Here are our results and observations:

Below are the optimum parameters for our model that we obtained through hyperparameter tuning.

![Image 5](https://github.com/kierengill/Deep-Learning-Project/blob/main/readme_images/5.png)



![Image 1](https://github.com/kierengill/Deep-Learning-Project/blob/main/readme_images/1.png)
![Image 2](https://github.com/kierengill/Deep-Learning-Project/blob/main/readme_images/2.png)
![Image 3](https://github.com/kierengill/Deep-Learning-Project/blob/main/readme_images/3.png)
![Image 4](https://github.com/kierengill/Deep-Learning-Project/blob/main/readme_images/4.png)

![Image 6](https://github.com/kierengill/Deep-Learning-Project/blob/main/readme_images/6.png)
![Image 7](https://github.com/kierengill/Deep-Learning-Project/blob/main/readme_images/7.png)
