# CNN Architecture Implementation from Scratch (PyTorch)

This project demonstrates the construction and forward pass of a deep convolutional neural network (CNN) using PyTorch, as part of my graduate coursework in Artificial Intelligence.

## 🔧 Features Implemented

### 🔹 Part 1.1 - Single Convolution Layer Visualization
- Implemented a custom `Conv2d` layer using PyTorch
- Loaded a color image (`fruits.jpg`) using `Matplotlib`/`Pillow`
- Applied a convolutional layer with **4 filters**, **padding**, and **stride**
- Visualized each output channel using `Matplotlib`

### 🔹 Part 1.2 - Forward Pass through Custom CNN Architecture
- Architecture includes:
  - Multiple convolutional layers with padding, batch normalization, and ReLU
  - MaxPooling layers
  - Dropout layers (5% and 10%)
  - Dense (fully connected) layers for classification
- Only forward pass is implemented (no training/backprop)

## 🛠️ Technologies Used
- Python
- PyTorch
- Matplotlib
- OpenCV / PIL

## 🖼️ Sample Visualizations
<img width="986" height="811" alt="image" src="https://github.com/user-attachments/assets/a387835c-f550-4856-90b2-fc2ed140e984" />


## 📁 How to Run
```bash
# Clone the repo
git clone https://github.com/یdoki244/pytorch-cnn-architecture.git

# Run notebook or script
python main.py
