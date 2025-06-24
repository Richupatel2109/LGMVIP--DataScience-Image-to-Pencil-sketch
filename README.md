# 🖼️ Image to Pencil Sketch using Python 🖌️

This project converts a colored image into a realistic pencil sketch using Python and OpenCV. It demonstrates basic image processing techniques like grayscale conversion, image inversion, Gaussian blurring, and blending.

## 🛠️ Dependencies

Install the required libraries using pip:

```bash
pip install -r requirements.txt
```
---
## 📄 requirements.txt
```bash
opencv-python
matplotlib
```
---
## ▶️ How to Run

  Clone the repository or download the files.

  Place your image as sample_input.jpg in the root directory.

  Run the script:
  ```bash
    python pencil_sketch.py
 ```
  Output images will be saved inside the output/ folder.
---
## 🧠 Concepts Used

    cv2.cvtColor() - for color space conversions

    cv2.bitwise_not() - for image inversion

    cv2.GaussianBlur() - for blurring

    cv2.divide() - for blending images to simulate sketch effect

