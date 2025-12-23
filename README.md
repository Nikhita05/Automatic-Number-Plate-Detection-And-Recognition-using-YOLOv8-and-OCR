# Automatic Number Plate Recognition (ANPR)

This repository contains a **Jupyter Notebook implementation of an Automatic Number Plate Recognition (ANPR) system**.  
The notebook demonstrates how vehicle number plates are detected from images and how the license number is extracted using computer vision and deep learning techniques.



## 📌 Notebook Overview

The notebook covers the complete ANPR pipeline:
- Image preprocessing
- Number plate detection
- Plate cropping and enhancement
- Optical Character Recognition (OCR)
- Display of final results



## 🛠️ Technologies Used

- Python  
- OpenCV  
- YOLOv5  
- EasyOCR / Custom OCR  
- NumPy, Pandas  
- Matplotlib  
- Jupyter Notebook / Google Colab  



## ⚙️ How It Works

1. **Input Image**
   - A vehicle image is provided as input to the system.

2. **Preprocessing**
   - The image is resized and normalized.
   - Noise is reduced to improve detection accuracy.

3. **Number Plate Detection**
   - A deep learning model (YOLOv5) detects the license plate region in the image.

4. **Plate Cropping**
   - The detected plate area is cropped from the original image for focused processing.

5. **Image Enhancement**
   - The cropped plate is enhanced using grayscale conversion and thresholding.

6. **Character Recognition (OCR)**
   - OCR is applied to extract the alphanumeric characters from the license plate.

7. **Final Output**
   - The recognized license plate number is displayed along with the detection result.

