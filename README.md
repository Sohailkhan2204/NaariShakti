*Protecting Women from Safety Threats*:
- It is not a perfectly optimized code but a proof of concept.
---

# Protecting-Women-from-Safety-Threats-Using-Computer-Vision

## Problem Statement

Through this project we wish to address the growing concern for women's safety and increase in crimes against women in cities. We have used computer vision and AI models to determine when a woman is in threat and take immediate action to counter it. The solution uses live footage from CCTVs and analysis of behavioural patterns to analyze safety threats such as violence, the presence of multiple men near a lone woman or any such suspicious activity along with timely alerts to prevent and intervene beforehand. The data collected from this is further analyzed to locate hotspots to assist law enforcement in effectively addressing and preventing crimes against women.


### This was built for *BitShift-Hackathon* organised by Usha Martin University, where our main aim was to develop a scalabe solution using women safety analytics. The proposed solution uses real-time threat detection using AI models and alert systems which function based on live footage.

---

## How to Clone the Repository

To clone the repository to your local machine, use the following command:
- Step-1
bash

git clone https://github.com/ShanawazS-bit/NariRakshak/


- Step -2
bash
pip install -r requirements.txt

---

## Documentation


### Technical Approach

1. *Person Detection*: Utilizes YOLOv8 for detecting individuals in CCTV footage and tracking them across frames.
2. *Gender Detection*: Based on Transformer models, it identifies gender to detect if a woman is surrounded by multiple men.
3. *Emotion and Pose Detection*: Uses MediaPipe for facial emotion detection (like fear or distress) and body pose classification (running, walking, standing).
4. *Violence Detection*: MobileNet-based model for identifying violent activity such as fights or physical altercations.
5. *Hotspot Detection*: Using DBSCAN and GRU, the model detects locations with repeated instances of potential danger, identifying unsafe zones or "hotspots."

---

## Links and References

- *Object Detection*: [YOLO Object Detection with OpenCV](https://github.com/yash42828/YOLO-object-detection-with-OpenCV)
- *Gender Classification*: [Hugging Face - Gender Classification](https://huggingface.co/rizvandwiki/gender-classification)
- *Violence Detection*: [Real-Time Violence Detection](https://github.com/abduulrahmankhalid/Real-Time-Violence-Detection)
- *MediaPipe for Pose and Emotion*: [MediaPipe](https://github.com/google-ai-edge/mediapipe)
- *Hotspot Detection*: [Crime Analysis for Hotspot Detection](https://github.com/mcoric96/Crime-analysis)
- *Crime in India Dataset*: [Kaggle Dataset](https://www.kaggle.com/datasets/rajanand/crime-in-india)

---
# Authors:

Team Name: HackSmith
---
Authors: Sohail Khan, Shanawaz Sharif, Vagisha Kumari, Anandita Gupta
---
Email: sharifshanawaz100@gmail.com
---
