# Nonlinear Binary Classification with PyTorch - A Typical Workflow
a typical workflow for a nonlinear binary classification

In this article, we'll have a look at a typical workflow for a simple nonlinear binary classification problem. We'll keep things simple.

## Contents

### Data Preparation
We'll use a method from sklearn.datasets to create some data.

![image](https://github.com/user-attachments/assets/feac0c15-6836-407b-b8c9-b70193de53b1)

### Model Building
We have the data in place, it's time to build a model. Besides the model, we'll define a loss function and optimizer.

![image](https://github.com/user-attachments/assets/9c897ba8-dec1-441f-9ec4-c8277c6d6239)

### Model Training
Training the model involves two loops: a training loop, where the model learns the relationships between the features and labels, and a testing loop, where the model is evaluated.

![image](https://github.com/user-attachments/assets/4bb2a9c9-2787-40c5-b5dc-e118e8251f48)

### Model Evaluation
Let's evaluate the model and see how it performs on data it never saw.

![image](https://github.com/user-attachments/assets/1fef8924-3b9e-4ad5-b585-8dcb79e8c58d)
