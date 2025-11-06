# MNIST Digit Classification using Keras

This project trains a simple **Artificial Neural Network (ANN)** on the **MNIST dataset** to classify handwritten digits (0–9). 
The dataset contains 70,000 grayscale images (28×28 pixels), split into 60,000 for training and 10,000 for testing.

###  Tech Stack
- Python · TensorFlow/Keras · NumPy · Matplotlib · Scikit-learn

### Model Summary
- Input: Flattened 28×28 images  
- Hidden Layers: Dense(128, ReLU), Dense(64, ReLU)  
- Output: Dense(10, Softmax)  
- Optimizer: Adam | Loss: Sparse Categorical Crossentropy  

### Results
- Training Accuracy: ~98%  
- Test Accuracy: ~97–98%  

### Future Work
Upgrade to **CNN** for better accuracy, add **dropout** layers.

---

👩‍💻 **Author:** Mehak Imran  
🎓 Computer Science Student | 💡 AI Enthusiast
