# Image Classification using Google Teachable Machine

## Overview

This project demonstrates a simple image classification workflow using a pre-trained TensorFlow/Keras model exported from Google Teachable Machine.

The notebook loads an image, preprocesses it, predicts its class, and displays the predicted class along with the confidence score.

---

## Project Structure

```
.
├── Untitled0.ipynb      # Google Colab notebook
├── keras_model.h5       # Pre-trained classification model
├── labels.txt           # Class labels
├── images.jpg           # Sample cat image
├── prev.jpg             # Sample dog image
```

---

## How to Run

1. Open `Untitled0.ipynb` in Google Colab.
2. Upload all project files to the Colab session.
3. Make sure the image filename in the notebook matches the image you want to test.
4. Run all notebook cells.
5. The notebook will display:
   - Predicted class
   - Confidence score

---

## Example Images

- `images.jpg` → Cat
- `prev.jpg` → Dog

You can replace either image with your own image by changing the filename inside the notebook.

---

## Model Information

- Framework: TensorFlow / Keras
- The notebook automatically resizes input images to 224 × 224 pixels before feeding them into the model.
- Input Normalization: [-1, 1]
- Model Source: Google Teachable Machine

---
