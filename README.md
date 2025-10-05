
## 🌫️ Single Image Dehazing using Python

This project implements **Single Image Dehazing** based on the paper:
**"Efficient Image Dehazing with Boundary Constraint and Contextual Regularization" (Meng et al., ICCV 2013)**.
It removes haze or fog from a single input image using an efficient dehazing algorithm.

---



---

### 🚀 Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/siddhunayak/Image-Dehazing.git
   cd Single-Image-Dehazing-Python-master
   ```

2. **Create a virtual environment (optional but recommended)**

   ```bash
   python -m venv venv
   venv\Scripts\activate     # On Windows
   # or
   source venv/bin/activate  # On macOS/Linux
   ```

3. **Install dependencies**

   ```bash
   pip install opencv-python numpy
   ```

---

### 🧠 Usage

1. Place your hazy image inside the `Images/` folder.
   Example: `Images/foggy_oaks.jpg`

2. Run the example script:

   ```bash
   python example.py
   ```

3. The dehazed image will be displayed and saved automatically to:

   ```
   outputImages/result.png
   ```







### 📄 Reference

* **Meng, Gaofeng, et al.**
  *"Efficient Image Dehazing with Boundary Constraint and Contextual Regularization"*,
  Proceedings of the IEEE International Conference on Computer Vision (ICCV), 2013.

---

### ⚙️ Dependencies

* Python ≥ 3.8
* OpenCV
* NumPy

Install them using:

```bash
pip install -r requirements.txt
```

*(Optional: Create a `requirements.txt` file with these contents)*

```
opencv-python
numpy
```




