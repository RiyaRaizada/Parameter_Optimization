# Parameter_Optimization Of SVM
Support Vector Machines (SVM) are widely used in machine learning for classification and regression tasks. The performance of an SVM model depends heavily on its parameter settings, such as the kernel type, the penalty parameter C, and the kernel coefficient gamma. Therefore, optimizing these parameters is critical for achieving better accuracy and generalization.

Parameter optimization refers to the process of fine-tuning the parameters of machine learning algorithms to achieve better performance on a given dataset.

## Dataset
This dataset contains features of various dry beans, specifically seven different classes from common bean species for agricultural research.
Number of Instances: 13611
Number of Attributes: 17
The goal of this dataset is typically classification, aiming to predict the class of dry beans based on their features. 

## Result Analysis

### Result Table:
![image](https://github.com/RiyaRaizada/Parameter_Optimization/assets/88757064/851851fc-9e2e-4d4e-a66c-4f80bbd3afc0)

### Convergence Graph
![image](https://github.com/RiyaRaizada/Parameter_Optimization/assets/88757064/0340a899-78cd-4a5d-a746-1b067aa0c7be)

## Conclusion
Best Accuracy: The highest accuracy achieved among all experiments was 63% (Sample 1) using a linear kernel with a Nu value of 8.40 and an Epsilon value of 8.76.
Kernel Performance: The linear kernel outperformed the polynomial kernel in terms of accuracy, with the highest accuracy achieved using the linear kernel.
Impact of Nu and Epsilon: Higher values of Nu and Epsilon generally contributed to higher accuracy, as evidenced by the configurations with the highest accuracy scores.
Sample Variability: There was variability in the performance across different samples, indicating the sensitivity of the model to the choice of hyperparameters.
Consistency: Although there were fluctuations in accuracy across samples, linear kernel configurations consistently appeared among the top-performing setups.
