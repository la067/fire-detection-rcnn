# 🔥 Fire Detection Using R-CNN

### 📌 Overview
This project uses **Faster R-CNN** to detect fire flames using **computer vision and image processing** techniques. It analyzes fire properties like color and characteristics to achieve **99% accuracy**.

---

## 📂 Folder Structure
fire-detection-rcnn/ │── dataset/ # Fire and non-fire images used for training/testing │── models/ # Pre-trained model files │── src/ # Source code │ │── main.py # Main script to run the fire detection model │ │── train.py # Script to train the model │ │── preprocess.py # Preprocessing functions for dataset │── requirements.txt # List of dependencies │── README.md # Project documentation │── LICENSE # License file (optional)


---

## ⚙️ **Installation**
1. Install Python (Recommended: Python 3.5+).
2. Clone the repository:
git clone https://github.com/your-username/fire-detection-rcnn.git
*(Since you don't have Git installed, you can manually download the repo as a ZIP and extract it.)*
3. Install dependencies:
pip install -r requirements.txt
4. Run the project:
python src/main.py

---

## 📦 **Dependencies**
- Python 3.5+
- TensorFlow 1.13.1
- OpenCV
- NumPy

Install dependencies using:
```bash
pip install tensorflow==1.13.1 opencv-python numpy
📊 Dataset
The dataset consists of 1000 images:
80% for training
20% for validation
Images labeled as fire and non-fire using LabelImg.

🛠 How It Works
Loads the dataset and pre-processes images.
Trains the Faster R-CNN model on labeled fire images.
Detects fire in real-time using a camera or video input.
Outputs results with bounding boxes around detected flames.

📸 Screenshots
Fire Detected	No Fire Detected

🤖 Future Improvements
Deploy as a real-time IoT-based fire detection system.
Optimize for edge devices like Raspberry Pi.

---




