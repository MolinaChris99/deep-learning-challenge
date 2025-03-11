### Alphabet Soup Neural Network Model Report
- Overview
* The objective of this analysis is to develop a deep learning model capable of predicting the success of Alphabet Soup funding applicants. Using historical funding data, a binary classification model was built to enhance decision-making. The dataset underwent preprocessing, the neural network was optimized, and performance was evaluated to determine whether deep learning is an effective approach for this problem.

### Results
- Data Preprocessing
* Target Variable (y): IS_SUCCESSFUL (1 = successful, 0 = unsuccessful).
* Feature Variables (X): A mix of categorical and numerical features, including APPLICATION_TYPE, CLASSIFICATION, ASK_AMT, etc.
* Removed Columns: EIN and NAME (irrelevant identifiers).
### Model Compilation, Training, and Evaluation
- Neural Network Architecture
* Input Layer: Matches the number of preprocessed features.
*Hidden Layers:
-- Layer 1: 128 neurons, ReLU activation.
-- Layer 2: 64 neurons, ReLU activation.
-- Layer 3: 32 neurons, ReLU activation.
* Output Layer: 1 neuron with Sigmoid activation.
* Performance
- Test Accuracy: 72.52% (Target: 75%)
### Optimization Attempts
* Increased the number of neurons and added a third hidden layer.
* Experimented with ReLU and LeakyReLU activation functions.
* Tuned hyperparameters:
-- Batch size: 32
-- Epochs: 100
-- Learning rate: Adjusted in Adam optimizer (0.001).
* Tried dropout layers (not included in the final model).
### Conclusion & Recommendations
* The deep learning model did not reach the 75% accuracy goal.
* Increasing model complexity did not significantly improve performance.
* Alternative machine learning models such as Random Forest or XGBoost may be more effective for this structured dataset.
### Resources Used
1) Course materials & recorded sessions.
2) Teaching assistant support.
3) Google Colab documentation.
4) TensorFlow Playground.
5) YouTube tutorials.
6) ChatGPT assistance.
