# Semantic Segmentation
### Introduction
In this project, you'll label the pixels of a road in images using a Fully Convolutional Network (FCN).

### Setup
##### Frameworks and Packages
Make sure you have the following is installed:
 - [Python 3](https://www.python.org/)
 - [TensorFlow](https://www.tensorflow.org/)
 - [NumPy](http://www.numpy.org/)
 - [SciPy](https://www.scipy.org/)
##### Dataset
Download the [Kitti Road dataset](http://www.cvlibs.net/datasets/kitti/eval_road.php) from [here](http://www.cvlibs.net/download.php?file=data_road.zip).  Extract the dataset in the `data` folder.  This will create the folder `data_road` with all the training a test images.

### Start
##### Implement
Implement the code in the `main.py` module indicated by the "TODO" comments.
The comments indicated with "OPTIONAL" tag are not required to complete.
##### Run
Run the following command to run the project:
```
python main.py
```
**Note** If running this in Jupyter Notebook system messages, such as those regarding test status, may appear in the terminal rather than the notebook.

### Submission
1. Ensure you've passed all the unit tests.
2. Ensure you pass all points on [the rubric](https://review.udacity.com/#!/rubrics/989/view).
3. Submit the following in a zip file.
 - `helper.py`
 - `main.py`
 - `project_tests.py`
 - Newest inference images from `runs` folder  (**all images from the most recent run**)
 
 ## How to write a README
A well written README file can enhance your project and portfolio.  Develop your abilities to create professional README files by completing [this free course](https://www.udacity.com/course/writing-readmes--ud777).

Output:
------------------------------------------------------------------------------------------
Epoch: 1 / 20  Loss: 0.417
Epoch: 2 / 20  Loss: 0.318
Epoch: 3 / 20  Loss: 0.153
Epoch: 4 / 20  Loss: 0.055
Epoch: 5 / 20  Loss: 0.217
Epoch: 6 / 20  Loss: 0.072
Epoch: 7 / 20  Loss: 0.041
Epoch: 8 / 20  Loss: 0.104
Epoch: 9 / 20  Loss: 0.074
Epoch: 10 / 20  Loss: 0.102
Epoch: 11 / 20  Loss: 0.026
Epoch: 12 / 20  Loss: 0.027
Epoch: 13 / 20  Loss: 0.061
Epoch: 14 / 20  Loss: 0.038
Epoch: 15 / 20  Loss: 0.027
Epoch: 16 / 20  Loss: 0.032
Epoch: 17 / 20  Loss: 0.034
Epoch: 18 / 20  Loss: 0.068
Epoch: 19 / 20  Loss: 0.039
Epoch: 20 / 20  Loss: 0.025
Training Finished. Saving test images to: ./runs/1514309122.9212842
------------------------------------------------------------------------------------------
