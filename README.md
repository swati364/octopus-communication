# octopus-communication
#OCTOPUS DETECTION AND POSE ESTIMATION USING YOLOV8 AND TRANSFER LEARNING

##overview
this project focuses on detecting octopus and estimating their poses in underwater images and videos using the YOLOV8 deep learning model.
The model is fine-tuned with transfer learning to adapt YOLOv8' s pre-trained weights for the specific task of marine animal recognition.

Application include:
-Marine biology research
-Octopus activity tracking
-Underwater robotics and monitoring

## Problem Statement
Traditional object detection models struggle with underwater environments due to:
- Low visibility
- Color distortions
- Complex backgrounds
This project aims to provide a robust solution by applying YOLOv8 and transfer learning for accurate octopus detection and body keypoint estimation.

## Methodology
1. *Dataset Preparation*
   - Underwater images of octopuses annotated with bounding boxes and pose keypoints.
   - Data augmentation (rotation, blur, color shift).

2. *Model Selection*
   - Base model: YOLOv8 (pre-trained on COCO dataset).
   - Tasks: Detection (bounding boxes) + Pose Estimation (keypoints).

3. *Transfer Learning*
   - Fine-tuning YOLOv8 weights on the custom octopus dataset.
   - Reduces training time and improves accuracy.

4. *Training*
   - Framework: PyTorch +train.py + Ultralytics YOLOv8.
   - Hyperparameters: Learning rate, batch size, epochs.

5. *Evaluation*
   - Metrics: mAP (mean Average Precision), PCK (Pose estimation accuracy).
  
## Tech Stack
Backend (Python)

app.py → Likely a backend application file (could be using Flask, FastAPI, or Django).

train.py → Suggests some machine learning / model training script (probably using libraries like TensorFlow, PyTorch, or scikit-learn).

Frontend (Web technologies)

index.html → The main webpage.

style.css → Styles for the webpage.

script.js → JavaScript for frontend interactivity.

Project setup

requirements.txt → Lists Python dependencies (backend + ML libraries).

TODO.md → Notes or project tasks.

invalid.txt → Might be sample data or logs (not standard).

Likely Tech Stack:

Frontend:

HTML, CSS, JavaScript

Backend:

Python (probably Flask or FastAPI)

Machine Learning:

A model trained with train.py (framework depends on the requirements listed in requirements.txt)

Environment Management:

Dependencies handled through requirements.txt
