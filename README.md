# Face Mask Detection

![Project Banner](https://via.placeholder.com/1000x300.png?text=Face+Mask+Detection)

## 📖 Overview

Face Mask Detection is an AI-driven project designed to identify individuals wearing or not wearing masks in real-time. Using deep learning techniques, the model analyzes images or video streams and detects compliance with mask-wearing protocols to enhance public safety.

## ✨ Features

- **High Accuracy:** Achieved over 95% accuracy using a Convolutional Neural Network (CNN).
- **Real-Time Detection:** Integrates with OpenCV for real-time mask detection on live video feeds.
- **Cross-Platform:** Deployable as a web app using Flask or Streamlit.
- **Customizable:** Easy to adapt for various use cases, including workplaces, public spaces, and healthcare settings.

## 🚀 Technologies Used

- **Programming Languages:** Python
- **Deep Learning Libraries:** TensorFlow, Keras
- **Computer Vision:** OpenCV
- **Web Framework:** Flask, Streamlit
- **Dataset Source:** Kaggle

## 🗂️ Project Structure

```plaintext
├── datasets         # Training and validation datasets
├── models           # Pre-trained and saved models
├── scripts          # Python scripts for training and testing
├── app.py           # Web application entry point
├── requirements.txt # Python dependencies
└── README.md        # Project documentation
```

## 📋 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/face-mask-detection.git
   ```

2. Navigate to the project directory:
   ```bash
   cd face-mask-detection
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Download the dataset and place it in the `datasets` directory.

## 🛠️ Usage

### 1. Training the Model
Run the following command to train the model:
```bash
python scripts/train_model.py
```

### 2. Testing the Model
Evaluate the model's performance:
```bash
python scripts/test_model.py
```

### 3. Real-Time Detection
Launch the real-time mask detection system:
```bash
python scripts/realtime_detection.py
```

### 4. Web Application
Start the web app:
```bash
python app.py
```
Access the app at `http://127.0.0.1:5000`.

## 📊 Results

- **Accuracy:** 95% on the validation dataset
- **Precision:** 94%
- **Recall:** 96%
- **Inference Speed:** <1 second per frame

## 🖼️ Sample Outputs

| Input Image         | Detection Output        |
|---------------------|-------------------------|
| ![Input1](https://via.placeholder.com/150) | ![Output1](https://via.placeholder.com/150) |
| ![Input2](https://via.placeholder.com/150) | ![Output2](https://via.placeholder.com/150) |

## 🧑‍💻 Contributors

- **[Your Name](https://github.com/your-username)** - Project Lead

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 📬 Contact

For any queries, feel free to reach out:
- Email: your.email@example.com
- LinkedIn: [Your LinkedIn Profile](https://linkedin.com/in/your-profile)

---

**Empowering safety, one mask at a time.**
