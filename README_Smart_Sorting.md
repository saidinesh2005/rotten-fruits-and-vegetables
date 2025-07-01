# 🍎 Smart Sorting: Transfer Learning for Identifying Rotten Fruits and Vegetables

Smart Sorting is a deep learning-based web application that classifies fruits and vegetables as **fresh** or **rotten** using image recognition. This solution leverages **transfer learning** (MobileNetV2) and integrates it with a **Flask** server, allowing users to upload images via a user-friendly UI.

---

## 🔍 Features

- 🧠 Transfer learning with MobileNetV2
- 📷 Upload and classify fruit/vegetable images in real-time
- 🌐 Web interface built with HTML + Flask
- ✅ Outputs prediction with accuracy >90%

---

## 🏗️ Project Structure

```
├── app.py                # Flask backend
├── templates/
│   └── index.html        # Upload UI
├── static/
│   └── sample.jpg        # Uploaded images
├── smart_sort_model.h5   # Trained model
├── requirements.txt      # Python dependencies
└── README.md
```

---

## 🚀 How to Run Locally

### 1. Clone the repository
```bash
git clone https://github.com/PRAVEEN4785/Rotten-fruits-and-vegetables.git
cd Rotten-fruits-and-vegetables
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the Flask App
```bash
python app.py
```

Visit `http://127.0.0.1:5000` in your browser.

---

## 📊 Dataset Used

**Kaggle Dataset:** [Fruits Fresh and Rotten for Classification](https://www.kaggle.com/datasets/sriramr/fruits-fresh-and-rotten-for-classification)

---

## 🧪 Model Training

- **Model:** MobileNetV2 (Pre-trained on ImageNet)
- **Image Size:** 224x224
- **Optimizer:** Adam
- **Epochs:** 10
- **Accuracy:** ~92% on test data

---

## 🖼️ Output Screenshots

| Upload Page | Prediction Result |
|-------------|--------------------|
| ![](static/upload_mock.png) | ![](static/result_mock.png) |

---

## ✅ Advantages

- High accuracy and speed
- Scalable architecture
- Simple UI for non-technical users

---

## ⚠️ Limitations

- Depends on good lighting and image quality
- Limited dataset variety
- Runs locally unless hosted on cloud

---

## 🛠️ Future Scope

- Multi-class classification (bruised, mold, insect-damaged)
- Deploy on Raspberry Pi or Jetson Nano
- Conveyor belt + actuator integration

---

## 📎 License

This project is licensed under the MIT License.

---

## 🙌 Acknowledgments

- [Kaggle Dataset](https://www.kaggle.com/datasets/sriramr/fruits-fresh-and-rotten-for-classification)
- TensorFlow, Keras, Flask
