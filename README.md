# Signature Detection and Verification System

## Project Overview

This project is an AI-powered Signature Detection and Verification System that combines:

- YOLO (You Only Look Once) for signature detection
- Siamese Neural Network (SNN) for signature verification

The system first detects the signature region from an input image and then verifies whether the signature belongs to a registered person by comparing it with reference signatures.

---

## Features

✅ Automatic Signature Detection using YOLO

✅ Signature Verification using Siamese Neural Network

✅ Reference Signature Matching

✅ Support for Multiple Users

✅ Google Colab Compatible

✅ Deep Learning-Based Verification

---

## Project Structure

```text
Signature-Detection-Project/
│
├── datasets/
│
├── models/
│   └── signature_yolo_best.pt
│
├── notebook/
│   ├── signature_detection_yolo.ipynb
│   ├── signature_detection_snn.ipynb
│   └── signature_yolo_snn_finalcode.ipynb
│
├── reference_images/
│   └── Reference_Images/
│       ├── Person1/
│       ├── Person2/
│       ├── Person3/
│       ├── Person4/
│       ├── Person5/
│       ├── Person6/
│       └── Person7/
│
├── .gitignore
└── README.md
```

---

## Technologies Used

- Python
- TensorFlow / Keras
- YOLO
- OpenCV
- NumPy
- Matplotlib
- Google Colab

---

## Workflow

### Step 1: Signature Detection

YOLO detects the signature region from the input image.

### Step 2: Signature Cropping

The detected signature is cropped from the image.

### Step 3: Signature Verification

The Siamese Neural Network compares the detected signature with stored reference signatures.

### Step 4: Prediction

The system returns:

- Verified Signature
- Person Identification
- Similarity Score

---

## Models

### YOLO Model

File:

```text
models/signature_yolo_best.pt
```

Used for signature detection.

### Siamese Neural Network Model

The trained `.h5` model is not included in this repository because GitHub restricts files larger than 100 MB.

---

## Reference Images

Reference signatures are stored inside:

```text
reference_images/Reference_Images/
```

Each folder represents one registered person.

Example:

```text
Person1/
Person2/
Person3/
...
```

---

## How to Run

1. Open the notebooks in Google Colab.
2. Upload the required models.
3. Mount Google Drive if necessary.
4. Run all notebook cells.
5. Provide a test signature image.
6. View verification results.

---

## Future Improvements

- Web Application Integration
- Real-Time Signature Verification
- Larger Signature Dataset
- Multi-Language Support
- Improved Verification Accuracy

---

## Author

**Devi Vaishnavi Vallala**

Artificial Intelligence & Machine Learning Student

---

## License

This project is developed for educational and research purposes.
