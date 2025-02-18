# Extract_Car_License_Plate 🚗  

This project processes car images to extract the license plate using OpenCV and Tesseract OCR. It involves four main steps: cropping the dark window, extracting the white window (license plate), enhancing contrast, and extracting text.  

---

## ✨ Features  
- **Dark Window Cropping**: Identifies and crops the dark window region where the license plate is located.  
- **White Window Extraction**: Extracts the white region (license plate) from the dark window.  
- **Contrast Enhancement**: Increases the contrast for better text recognition.  
- **Text Extraction**: Utilizes Tesseract OCR to extract text from the license plate.  

---

## 🔧 Prerequisites  
Ensure the following are installed:  
- Python 3.x  
- OpenCV  
- Pillow  
- pytesseract  

---

## 📥 Installation  
```bash
pip install opencv-python pillow pytesseract

