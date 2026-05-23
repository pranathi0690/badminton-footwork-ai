AI-Based Badminton Footwork Analysis System

An AI-powered badminton analytics system that detects players from match videos, tracks body movement, extracts biomechanical pose features, and classifies badminton footwork patterns using Machine Learning.

---

 Features

✅ Automatic Player Detection using YOLOv8  
✅ Single-player tracking (nearest player only)  
✅ Accurate dynamic bounding boxes  
✅ Pose Keypoint Extraction  
✅ Biomechanical Feature Engineering  
✅ Random Forest Footwork Classification  
✅ Confidence Score Prediction  
✅ Video Output Rendering with Labels  

---

 Footwork Classes

The model classifies:

- Forehand Front
- Forehand Mid
- Forehand Back
- Backhand Front
- Backhand Mid
- Backhand Back

---

 Technologies Used

- Python
- OpenCV
- YOLOv8
- Scikit-learn
- NumPy
- Pandas
- Joblib

---

 Project Pipeline

Video Input
↓
YOLOv8 Player Detection
↓
Player Tracking
↓
Pose / Keypoint Extraction
↓
Biomechanical Feature Engineering
↓
Random Forest Classification
↓
Bounding Box + Confidence + Label Visualization
↓
Final Output Video

---

 Dataset

The dataset contains:
- Hip coordinates
- Knee coordinates
- Ankle coordinates
- Biomechanical movement features
- Footwork labels

Total Samples: 1186+

---

 Output

The system generates:
- Dynamic player bounding boxes
- Footwork labels
- Confidence scores
- Annotated badminton videos

---

 Model Performance

Random Forest Accuracy:
86%+

---

How to Run

## 1. Install Dependencies

```bash
pip install ultralytics opencv-python pandas numpy scikit-learn joblib
```

## 2. Train Model

```bash
python train_rf_model.py
```

## 3. Run Video Inference

```bash
python video_inference.py
```

---
 Future Improvements

- Temporal movement analysis
- Super Single-player analysis
- Court mapping
- Heatmaps
- Coach analysis

---
 Author

A Sai Pranathi

---

Project Goal

To build an intelligent AI system capable of understanding badminton movement biomechanics and automated sports analytics.