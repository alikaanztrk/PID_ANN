# Diabetes Prediction using Neural Network
This repository contains Python code to build and train a neural network model for predicting diabetes using the Pima Indian Diabetes dataset. The code is implemented using TensorFlow and Keras. The model is trained on a subset of the dataset and evaluated for its accuracy.

## Dependencies

Before running the code, make sure you have the following Python libraries installed:

- numpy
- pandas
- tensorflow
- keras
- scikit-learn
- matplotlib
- seaborn
  
You can install these dependencies using pip:
```bash
pip install numpy pandas tensorflow scikit-learn matplotlib seaborn

```
## 🛠️ Usage
Clone the repository to your local machine:
```bash
git clone https://github.com/alikaanztrk/PID_ANN.git
```
Download the Diabetes dataset (Diabetes.tsv) and place it in the same directory as the code.

## Model Architecture
The neural network model consists of the following layers:

- Input Layer with 8 neurons (input_dim=8) and sigmoid activation function.
- Hidden Layer 1 with 32 neurons and sigmoid activation function.
- Hidden Layer 2 with 16 neurons and ReLU activation function.
- Hidden Layer 3 with 8 neurons and ReLU activation function.
- Output Layer with 1 neuron and sigmoid activation function.
- The model is compiled with binary cross-entropy loss and the Adam optimizer.

![image](https://github.com/alikaanztrk/PID_ANN/assets/75249091/bd3fe5fa-1266-4fb8-9ebb-499e4e282497)

![image](https://github.com/alikaanztrk/PID_ANN/assets/75249091/dab09dfe-9d77-472e-9002-7eab489778d6)

![image](https://github.com/alikaanztrk/PID_ANN/assets/75249091/bb59c368-ede0-43f5-83ff-cff9109ccad8)

![image](https://github.com/alikaanztrk/PID_ANN/assets/75249091/1be8f327-54ca-4097-b7f8-28377a3ee0d0)




