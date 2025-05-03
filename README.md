
# 🐾 **Cat-Dog Classifier** 🐾

## 🎯 **Overview**  
Welcome to the **Cat-Dog Classifier**! This project utilizes **ResNet18** with **transfer learning** to classify images as either a **cat** or a **dog**. With a simple and user-friendly **Streamlit** web app, you can instantly upload images and get predictions.

## 🧑‍💻 **Tech Stack**
- **Deep Learning Framework**: PyTorch  
- **Pre-trained Model**: ResNet18  
- **Deployment**: Streamlit  
- **Dataset**: [Kaggle Dogs vs. Cats Dataset](https://www.kaggle.com/datasets/chetankv/dogs-cats-images)

---

## 📸 **Demo**

**[Streamlit App](https://catdogclassifier-zghs4dvschl6ndmfxjfz9h.streamlit.app/)**  
![image](https://github.com/user-attachments/assets/f4ee9a02-1da2-4a7d-9aef-05a5764a27e5)

---

## 📂 **Dataset Details**  
The classifier is trained on the **[Dogs vs. Cats Images dataset](https://www.kaggle.com/datasets/chetankv/dogs-cats-images)** from Kaggle. The dataset consists of thousands of images of cats and dogs that have been used to train and test the model.

### Dataset Breakdown:
- **Total Images**: 25,000+  
- **Classes**:  
  - `Cat`  
  - `Dog`  

---

## ⚡ **How It Works**  
### 1. **Transfer Learning**  
We use the **ResNet18** architecture as a pre-trained model. This model is fine-tuned to classify images of cats and dogs efficiently.

### 2. **Data Augmentation**  
Data augmentation techniques such as **rotation**, **scaling**, and **flipping** help improve model robustness and generalization.

### 3. **Performance**  
The model achieves **95% accuracy** on the test set, making it highly reliable for real-time predictions.

---

## 🚀 **Getting Started**  

### 1. **Clone the Repo**
To get started, clone the repository:

```bash
git clone https://github.com/Janmejaya119/cat-dog-classifier.git
cd cat-dog-classifier
```

### 2. **Install Dependencies**
Install all required packages with:

```bash
pip install -r requirements.txt
```

### 3. **Run the Streamlit App**

Launch the app by running:

```bash
streamlit run app.py
```

### 4. **Upload an Image**
Once the app is running, upload an image of a cat or dog, and the model will predict the label along with the confidence score.

---

### 🐱 **Sample Predictions**
| Image | Prediction | Confidence |
|-------|------------|------------|
| Dog   | Dog        | 97%        |
| Cat   | Cat        | 95%        |

---

## 🛠 **Future Improvements**
- **More Animals**: Expand the classifier to recognize multiple animal species.  
- **Mobile Compatibility**: Optimize the model for mobile devices.  
- **Visualization**: Implement Grad-CAM for visual explanations of predictions.  

---

## 📧 **Contact**
- **Email**: janmejay119@gmail.com  
- **GitHub**: [Janmejaya119](https://github.com/Janmejaya119)

---

## 💖 **Acknowledgments**
- Kaggle for providing the dataset.  
- PyTorch for their powerful deep learning library.  
- Streamlit for their easy deployment framework.  
- The open-source community for continued support and inspiration.
