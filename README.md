# MNIST Digit Classifier
[![Language](https://img.shields.io/badge [![Framework](https://img.shields.io/badge/TensorFlow-2.x-FF6F00.svg(https://www.tensorflow.orghttps://img.shields.io/badge/Jupyter-Notebook-F37626.svg[![License](https://img.shields.io/badge(https://github.com/kyleyuen/MNIST-Digit-Classifer Project Overview

A deep learning project demonstrating digit classification on the MNIST dataset using TensorFlow and Keras. Designed for beginners and intermediate developers to understand neural network training, evaluation, and deployment workflows with Python and Jupyter Notebooks.

## 🎯 Purpose
This project showcases a practical approach to computer vision classification tasks with:

- Modern TensorFlow/Keras API usage

- End-to-end experimentation (exploration, preprocessing, modeling, and results)

- Reproducible code for educational and portfolio purposes

## ✨ Features
### Core Functionality
🔢 Digit Recognition: Classifies hand-written digits (0–9) from pixel images

📈 Model Training & Evaluation: Tracks accuracy/loss through epochs, with clear results

📊 Visualization: Live plots of accuracy, loss, and training history (via Matplotlib)

🗂 Data Preprocessing: Automated normalization/scaling for better convergence

📤 Prediction Examples: Predicts sample digit images and shows output visually

### Technical Highlights
☑️ Sequential Keras Model: Simple, readable neural network architecture (Flatten, Dense layers)

⚡ Fast Model Fit: ~98% accuracy after just a few epochs

🔄 Validation Split: Monitors model generalization and prevents overfitting

✅ Error Handling: Catches & explains input and dataset errors

## 🛠️ Tech Stack
- Language: Python 3.8+

- Frameworks: TensorFlow 2.x, Keras

- Notebook: Jupyter Notebook

- Libraries: NumPy, Matplotlib

- Dataset: MNIST (from TensorFlow/Keras API)

- Platform: Cross-platform (Linux, macOS, Windows)

## 🚀 Getting Started
### Prerequisites
- Python >= 3.8

- Jupyter Notebook

- pip (for package installation)

### Installation & Setup
1. Clone the Repository

```bash
git clone https://github.com/kyleyuen/MNIST-Digit-Classifer.git
cd MNIST-Digit-Classifer
```
2. Install Dependencies

```bash
pip install tensorflow matplotlib numpy
```
3. Launch Notebook

```bash
jupyter notebook MNIST_py.ipynb
```
Follow the notebook step-by-step to run preprocessing, train the model, and evaluate predictions.

## 📖 Usage Guide
### Training & Inference Flow
1. Import Libraries: TensorFlow, NumPy, Matplotlib

2. Load & Preprocess Data: MNIST dataset is normalized and split

3. Build Model: Sequential NN, Flatten → Dense (ReLU) → Dense (Softmax)

4. Train Model: Fit for 5 epochs, monitor validation split

5. Evaluate: On test set for final accuracy

6. Predict: Try some example digits, visualize their predictions

### Sample Output
```text
=== MNIST Digit Classifier ===

Train Accuracy: 98.63%
Validation Accuracy: 97.45%
Test Accuracy: 97.58%

Sample Predictions:
 - 7      Predicted: 7   ✅
 - 2      Predicted: 2   ✅
 - 5      Predicted: 3   ❌
```
See notebook plots for full training and prediction results.

## 🎯 Learning Outcomes
You'll gain hands-on experience in:

- TensorFlow/Keras Basics: Model definition and training

- Data Preprocessing: Preparing image data for ML tasks

- Computer Vision: Digit recognition workflow

- Model Evaluation: Validating accuracy and interpreting results

- Portfolio Development: Creating clear, reproducible ML projects for GitHub

## 🔮 Future Enhancements
### Planned Features
- [ ] Model Tuning: Test deeper architectures, regularization

- [ ] Augmentation: Image rotation/scaling for robust training

- [ ] Confusion Matrix: Error analysis and class-wise breakdown

- [ ] Export Model: Save/restore trained models easily

- [ ] Interactive Inference: Upload your own digits to classify

- [ ] Docker Deployment: Containerize for easy sharing

### Potential Improvements
- Advanced Architectures: Test CNNs to push accuracy higher

- Visualization: Animated plots and richer result dashboards

- Testing Suite: Unit tests for model/data pipeline

## 📊 Technical Specifications
| Aspect | Details |
|----------------|-------------------------|
| Framework      | TensorFlow 2.x, Keras   |
| Language       | Python 3.8+             |
| Notebook       | Jupyter Notebook        |
| Dataset        | MNIST                   |
| Test Accuracy  | ~97.6%                  |
| Platform Support | Linux, macOS, Windows |

## 🤝 Contributing
Contributions are welcome! To contribute:

1. Fork this repo & create PRs

2. Review code style, add comments

3. Update notebook if new features added

4. Reference issues for major changes

## 📜 License
This project is licensed under the MIT License - see the LICENSE file for details.

## 👨‍💻 Author
**Kyle Yuen**

- GitHub: @kyleyuen

- Project Link: MNIST-Digit-Classifer

## 🙏 Acknowledgments
- Inspired by classic MNIST tutorials in TensorFlow/Keras

- Built for hands-on machine learning practice and demo

- Thanks to TensorFlow, Keras, and open data communities

⭐ **Star this repository if you found it helpful!** ⭐

---
Last Updated: October 2025
