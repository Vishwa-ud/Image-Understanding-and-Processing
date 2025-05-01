# 📷 Image Understanding and Processing with OpenCV-Python

## 🚀 Introduction
This repository provides an introduction to image processing and understanding using **OpenCV** with **Python**. OpenCV is an open-source computer vision library that allows for real-time image and video processing, making it widely used in fields such as **robotics, AI, and medical imaging**.

## 🔧 Prerequisites
Ensure you have **Python** installed on your system before proceeding. It is recommended to use **Python 3.6 or later**.

---

### 🖼️ Image Processing Topics Covered

1. **Image Smoothing / Blurring Filters using OpenCV**
   - Averaging (Lowpass) filter with `cv2.filter2D`
   - Box filter with `cv2.boxFilter`
   - Simple blur with `cv2.blur`
   - Median filter with `cv2.medianBlur` (good for salt-and-pepper noise)
   - Gaussian filter with `cv2.GaussianBlur`

2. **Noise Removal Techniques**
   - Salt noise removal using Min Filter (PIL)
   - Pepper noise removal using Max Filter (PIL)
   - Both Salt & Pepper noise removal using Median Filter

3. **PIL-Based Image Processing**
   - `ImageFilter.MinFilter` and `ImageFilter.MaxFilter`
   - Grayscale conversion using `ImageOps.grayscale`
   - Edge detection using `ImageFilter.FIND_EDGES`

4. **Edge Detection**
   - Sobel operator using `cv2.Sobel` (X and Y derivatives)
   - Laplacian operator using `cv2.Laplacian`
   - Laplacian of Gaussian (LoG): combining Gaussian blur + Laplacian

5. **Histogram Equalization**
   - Improve contrast of:
     - Dark images
     - Bright images
     - Low contrast images

6. **Image Transformations**
   - Negative Transformation (invert pixel values)
   - Power-Law (Gamma) Transformation for brightness correction

---

## 📥 Installation
To set up your environment, install the required dependencies using **pip**:

```bash
pip install opencv-python
pip install matplotlib
python -m pip install jupyter
```

## ▶️ Running Jupyter Notebook
To start working with Jupyter Notebook, run the following command:

```bash
python -m notebook
```

This will open **Jupyter Notebook** in your web browser, allowing you to execute and visualize **OpenCV-based image processing** scripts. 

## ⌨️ Jupyter Notebook Shortcuts
Here are some essential **Jupyter Notebook keyboard shortcuts** to improve efficiency:

### General Shortcuts
- `Shift + Enter` → Run the current cell and move to the next
- `Ctrl + Enter` → Run the current cell but stay on it
- `Alt + Enter` → Run the current cell and insert a new one below
- `Esc + A` → Insert a new cell **above**
- `Esc + B` → Insert a new cell **below**
- `Esc + D + D` → Delete the selected cell
- `Esc + M` → Convert cell to **Markdown**
- `Esc + Y` → Convert cell to **Code**
- `Esc + L` → Toggle **line numbers** in cell
- `Esc + H` → Show **help menu**

### Navigation
- `Up/Down Arrow` → Move **between cells**
- `Ctrl + Shift + -` → Split a cell at the cursor
- `Shift + Tab` → Show **tooltip** for functions
- `Ctrl + Shift + P` → Open **command palette**

## 🤝 Contributing
Contributions are welcome! Feel free to submit **issues** or **pull requests** to enhance this repository. 

## 📜 License
This project is licensed under the **MIT License**. See the `LICENSE` file for more details.
