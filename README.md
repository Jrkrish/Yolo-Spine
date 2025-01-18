---

# Spine Segmentation using YOLOv8

This repository provides an application for spine segmentation using the YOLOv8 model. The application predicts spine parts (L1, L2, L3, L4, L5, and S1) from uploaded images, drawing bounding boxes around the detected areas.

---

## **Features**
1. **Class Names**: 
   - L1, L2, L3, L4, L5, S1
   - These represent different parts of the spine.
2. **Why This Process?** 
   - Spine segmentation is essential in the medical field to identify, track, and analyze the vertebrae and sacrum sections. This process helps radiologists, orthopedic surgeons, and medical practitioners improve their diagnostic and surgical precision.
3. **How It Helps**:
   - Automatic identification of spine parts reduces manual effort.
   - Facilitates accurate diagnoses.
   - Aids in advanced research by providing annotated data for further training.

---

## **Getting Started**

### **Clone the Repository**
```bash
git clone https://github.com/K-GOKULAPPADURAI/Spin-Segmentation-using-Yolov8.git
cd Spin-Segmentation-using-Yolov8
```

### **Install Requirements**
Ensure you have Python 3.12.3 installed. Install the required packages by running:
```bash
pip install -r requirements.txt
```

### **Model Files**
The YOLOv8 model weights (`best.pt` and `last.pt`) are available in the `datasets/weights` folder:
- `best.pt`: The optimized model.
- `last.pt`: The most recent model checkpoint.

---

## **How to Run the Application**
1. Start the Streamlit app:
   ```bash
   streamlit run main.py
   ```
2. Open the application in your browser (usually available at `http://localhost:8501`).
3. Upload an image from the `test_images` folder or any compatible image for spine segmentation.
4. View the predicted image with bounding boxes for the spine parts.

---

## **Test Images**
Sample test images are provided in the `test_images` folder. Feel free to use these for running the application.

---

## **Classes and Colors**
- **Class Names**: The application detects six classes: `L1`, `L2`, `L3`, `L4`, `L5`, and `S1`.
- **Color Codes**:
  - L1: **Red**
  - L2: **Green**
  - L3: **Blue**
  - L4: **Cyan**
  - L5: **Magenta**
  - S1: **Yellow**

---

## **For Help or Queries**
Feel free to reach out for any assistance:
- **Email**: [k.gokulappaduraikjgv@gmail.com](mailto:k.gokulappaduraikjgv@gmail.com)
- **Phone/WhatsApp**: +91 9025421765

---

### **Repository Link**
[Spin Segmentation using YOLOv8](https://github.com/K-GOKULAPPADURAI/Spin-Segmentation-using-Yolov8.git)

---
