# 😷 Face Mask Detection System

This project implements a real-time face mask detection system using deep learning and computer vision. It is capable of detecting whether a person is wearing a face mask or not using images or webcam input.

## 📊 Dataset

The dataset used for this project was taken from **Kaggle**:

🔗 [Kaggle - Face Mask Detection Dataset](https://www.kaggle.com/datasets/)

- Contains labeled images of individuals with and without masks.
- Preprocessed and augmented for better model performance.
- Used to train a Convolutional Neural Network (CNN) classifier.

## 🧠 Model

- Built using **TensorFlow** and **Keras**
- Uses a CNN architecture for binary classification (Mask / No Mask)
- Trained using the provided Jupyter notebook: `face_mask_detection_f.ipynb`

## 🚀 Getting Started

### Prerequisites

- Python 3.7+
- TensorFlow, OpenCV, NumPy, Matplotlib, etc.

Install dependencies using pip:

```bash
pip install -r requirements.txt
```

### Running the Model

1. Open and run the Jupyter notebook:
    ```
    face_mask_detection_f.ipynb
    ```

2. To integrate with a webcam or application, export the trained model and load it in a Python Flask or streamlit app.

## 🛠️ Tools & Technologies

- Python
- Jupyter Notebook
- TensorFlow / Keras
- OpenCV
- Kaggle Dataset

## 📁 Files

```
├── face_mask_detection_f.ipynb     # Jupyter notebook for training/testing
├── dataset/                        # (optional) dataset folder
├── model/                          # Saved models (if any)
└── README.md
```

## 🧑‍💻 Author

**Manikanta Nallamalli**  
GitHub: [@manikanta09-ai](https://github.com/manikanta09-ai)

## 📄 License

For academic and research purposes. Please cite the original dataset authors if reused.
