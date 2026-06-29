# 😷 Face Mask Detection

A deep learning-based project to automatically detect whether a person is wearing a face mask or not using computer vision techniques.

## 🚀 Features

- Real-time face mask detection using webcam or video
- Trained with TensorFlow/Keras or PyTorch (customizable)
- Support for multiple faces in a single frame
- Easy-to-use and extensible codebase

## 📸 Demo
<img src="images/images0.png" width="900"/>
<img src="images/images2.png" width="900"/>
<img src="images/images5.png" width="900"/>
<img src="images/images3.png" width="900"/>

## 🧠 How It Works

This project uses a convolutional neural network (CNN) to classify images of faces into two categories:

- **Mask**
- **No Mask**

It uses OpenCV to detect faces and then runs predictions on each detected face.

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/face-mask-detection.git
cd face-mask-detection
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## 🛠 Usage

To detect from webcam:

```bash
python detect_mask_video.py
```

To test on an image:

```bash
python detect_mask_image.py --image test.jpg
```

For training:

```bash
python train_mask_detector.py
```

## 📁 Project Structure

```
face-mask-detection/
├── dataset/                 # Dataset for training/testing
├── models/                  # Saved models
├── detect_mask_video.py     # Real-time detection script
├── detect_mask_image.py     # Image detection script
├── train_mask_detector.py   # Training script
├── utils/                   # Helper functions
├── README.md
└── requirements.txt
```

## 📊 Dataset

Uses a combination of public datasets such as:

- [RMFD (Real-World Masked Face Dataset)](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset)
- [LFW (Labeled Faces in the Wild)](http://vis-www.cs.umass.edu/lfw/)

Or your own custom annotated dataset.

## 🧪 Testing

```bash
pytest tests/
```

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you’d like to change.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## ✨ Credits

- OpenCV
- TensorFlow / Keras or PyTorch
- Community datasets
