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

When running the files, be sure to run them in the order as listed above. To run the files, just run the notebooks. You may need to change the file paths in the code to match your system.

__Results__

Here are our results and observations:

Below are the optimum parameters for our model that we obtained through hyperparameter tuning:

![Image 5](https://github.com/kierengill/Deep-Learning-Project/blob/main/readme_images/5.png)

Here is an image demonstrating how our ROI cropping works:

![Image 1](https://github.com/kierengill/Deep-Learning-Project/blob/main/readme_images/1.png)

This is a plot for our training and validation loss:

![Image 2](https://github.com/kierengill/Deep-Learning-Project/blob/main/readme_images/2.png)

This is the structure of our highest performing model:

![Image 3](https://github.com/kierengill/Deep-Learning-Project/blob/main/readme_images/3.png)

The next few images will demonstrate what our model "looks" at to classify the images.

This is an example image that one might input into the model:

![Image 4](https://github.com/kierengill/Deep-Learning-Project/blob/main/readme_images/4.png)

This heatmap represents the pixels in the image that is relevant to the model when making its classification decision:

![Image 6](https://github.com/kierengill/Deep-Learning-Project/blob/main/readme_images/6.png)

This superimposes the heatmap over the original image, so you can clearly see that the model is detecting the tumor.

![Image 7](https://github.com/kierengill/Deep-Learning-Project/blob/main/readme_images/7.png)

Here are our final accuracy metrics for our highest performing model:

Final auROC:  0.7813942807683052

Final auPR:  0.22049217230240403

Final fbeta:  0.3093812375249501
