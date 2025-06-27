# 🌾 Agriguard Rover – AI-Powered Agricultural Rover

**April 2025**  
**Technologies Used**: Python, TensorFlow, OpenCV, CNN, DenseNet121, ResNet50, Xception

Agriguard Rover is an AI-powered mobile agricultural rover designed to detect paddy leaf diseases in real-time with high precision. This project leverages deep learning techniques to support farmers with early disease identification, thus improving crop health and yield.

---

## 🚀 Features

- ✅ Detects common **paddy leaf diseases** with up to **95% accuracy**.
- 🔍 Uses **image preprocessing with OpenCV** for optimal model input.
- 🧠 Experimented with multiple deep learning models:
  - Custom CNN
  - ResNet50
  - Xception
  - ✅ Final Model: **DenseNet121**
- 📸 Real-time deployment-ready using TensorFlow.
- 🛠️ Can be integrated with rover hardware for autonomous field inspection.

---

## 🧑‍🌾 Use Case

Designed for agricultural fields where farmers can use the rover to automatically:
- Capture paddy leaf images
- Detect diseases on-the-spot
- Provide actionable insights for early intervention

---

## 🗂️ Project Structure

Agriguard/
├── Agriguard.ipynb # Jupyter notebook containing model training and evaluation
├── dataset/ # Directory containing paddy leaf images (training & testing)
├── models/ # Saved model files (e.g., DenseNet121.h5)
├── utils/ # Preprocessing and helper functions
├── requirements.txt # Python dependencies
└── README.md # Project documentation


---

## 📊 Model Evaluation

| Model       | Accuracy |
|-------------|----------|
| CNN         | 88%      |
| ResNet50    | 92%      |
| Xception    | 93%      |
| **DenseNet121** | **95%**  |

> DenseNet121 outperformed other models in both training and validation phases and was selected as the final model.

---

## 🔧 Installation & Setup

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/agriguard-rover.git
   cd agriguard-rover

   
2. Install required packages:
   
pip install -r requirements.txt

3. Run the notebook:

jupyter notebook Agriguard.ipynb
🖼️ Sample Prediction

Input: Paddy leaf image
Output: Disease detected – Bacterial Blight
Confidence: 95.3%

📌 Future Enhancements

Integrate real-time inference with rover hardware.
Expand to detect nutrient deficiencies.
Add Bluetooth/mobile app interface for user-friendly alerts.
Enable multi-language support for farmers.

👩‍💻 Author

Meenakshi S Menon
CSE (AIML), VIT Bhopal University

📄 License

This project is open-source and available under the MIT License.




