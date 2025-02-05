# 🔄 Recurrent Neural Networks (RNN) with PyTorch  

## 📜 Overview  
This project explores **Recurrent Neural Networks (RNNs)** using **PyTorch**, and processes sequential data.

📌 **Key Concepts Covered**:  
- **Recurrent Neural Networks (RNNs)**  
- **Handling Sequential Data**  
- **Training an RNN in PyTorch**  
- **Backpropagation Through Time (BPTT)**  
- **Evaluating RNN Predictions**  

## 🚀 Implementation Details  

### **Step 1: Data Preprocessing**  
✅ **Load and preprocess sequential data**.  
✅ **Convert data into tensors for PyTorch**.  

### **Step 2: Building the RNN Model**  
✅ **Define an RNN model** using `torch.nn.RNN()`.  
✅ **Customize hidden layers and activation functions**.  
✅ **Initialize weights and biases**.  

### **Step 3: Training the RNN**  
✅ **Define loss function and optimizer**.  
✅ **Train the model over multiple epochs**.  
✅ **Backpropagate errors using PyTorch’s autograd system**.  

### **Step 4: Model Evaluation & Visualization**  
✅ **Evaluate performance on test sequences**.  
✅ **Visualize predictions vs. actual data**.  
- Overall, there is overfitting here since there is a significant gap between the training and validation accuracy. The training accuracy quickly reaches near 100%, indicating that the model is effectively learning the training data; however, the validation accuracy remains significantly lower compared to the training accuracy and is relatively flat throughout the epochs. On the other hand, the training loss decreases rapidly and approaches zero, which corresponds with the high training accuracy. Meanwhile, the validation loss fluctuates and slowly increases over time. This indicates that the model learns the training set extremely well but fails to perform effectively on unseen data.
![Graph](https://github.com/pngo1997/Images/blob/main/Pytorch.png)  

## 📌 Summary  
✅ Implemented an RNN from scratch using PyTorch.

✅ Trained the model on sequential data.  

✅ Visualized model performance and predictions.
