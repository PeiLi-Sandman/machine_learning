This is the description for HW2: https://github.com/schneider128k/machine_learning_course/blob/master/homework/hw2.md

I created five different architectures and use K-Fold validation to reevaluate the best model.


Overall, several key points can be concluded:
   * Deep network is better, but it requires much more training time
   * Drop Out layer is a solution for over-fitting problem
   * Adam optimizer is better than SGD
   * Data Augmentation has significant improvement for model's performance on validation dataset
   * K-folder validation tends to have a better performance than the simple hold-out validation

Speficically, [HW2_jupyter.ipynb](https://github.com/PeiLi-Sandman/machine_learning/blob/master/HW2/HW2_jupyter.ipynb)
contains all the five model and the K-Folder validation process on the best model. 

[hw2.ipynb](https://github.com/PeiLi-Sandman/machine_learning/blob/master/HW2/hw2.ipynb) is just a simple copy of the established models on Colab. [hw2 with k folder.ipynb](https://github.com/PeiLi-Sandman/machine_learning/blob/master/HW2/hw2_with_k_folder.ipynb)is also a copy only for K-Folder validation

If you want to see the whole process of architecture selection and comparation. Please take a look at [HW2_jupyter.ipynb](https://github.com/PeiLi-Sandman/machine_learning/blob/master/HW2/HW2_jupyter.ipynb).

In total, I built five neural networks.
  * Model 1
  ![](https://github.com/PeiLi-Sandman/machine_learning/blob/master/HW2/picture/model1.PNG)
