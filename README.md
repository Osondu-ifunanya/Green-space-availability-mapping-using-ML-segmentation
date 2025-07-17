
## 🌿 Green Space Availability Mapping using ML Segmentation

This project uses synthetic satellite-like RGB imagery to identify and classify **green spaces** (vegetated areas) using a **machine learning segmentation** approach. It simulates real-world remote sensing applications for urban planning and environmental monitoring.

---

### 📌 Overview

* **Goal**: Detect green (vegetated) areas in an image using RGB data.
* **Method**: Random Forest classifier trained on synthetic RGB data to predict pixel-wise green space.
* **Data**: Generated synthetic image with random shapes and color intensity variations.

---

### 🧪 Features Used

* **Red, Green, Blue (RGB)** pixel values
* **Green space mask** as the label

---

### 🚀 How to Run

1. Install required packages:

```bash
pip install numpy pandas scikit-learn scikit-image openpyxl
```

2. Run the script:

```bash
python green_space_segmentation.py
```

3. Output will be saved as:

```
green_space_segmentation.xlsx
```

---

### 📊 Output

The Excel file contains:

* Pixel-level RGB values
* True green space label
* Predicted label from the ML model

---

### 📁 File Structure

* `green_space_segmentation.py` – Main script
* `green_space_segmentation.xlsx` – Model output (Excel)

---

### 👤 Author

**Ifunanya Osondu**
GIS | Climate | GeoAI Researcher
🔗 [LinkedIn](https://www.linkedin.com) | [GitHub](https://github.com)
