# AI_Powered_Motorcycle_Traffic_Violation_Monitoring_-_Analytical_Reporting_System 
## Project Overview

This project presents an AI-driven system designed to automatically detect and analyze motorcycle traffic violations using deep learning models.

## The system identifies:

- Riders without helmets

- Triple riding (more than two people on a motorcycle)

- Mobile phone usage while riding

### In addition to detection, the system generates structured analytical reports and violation statistics, converting raw predictions into meaningful traffic safety insights.

## Objectives

Build an automated motorcycle violation detection system using YOLOv8

Analyze violation patterns using statistical techniques

Generate structured safety reports and compliance metrics

Compare multiple YOLOv8 model variants for performance evaluation

## Technologies Used

Python

YOLOv8 (Ultralytics)

Kaggle (GPU training)

OpenCV

Pandas

Matplotlib

## Project Structure
AI_Powered_Motorcycle_Traffic_Violation_Monitoring_-_Analytical_Reporting_System/
│
├── dataset/
├── main.ipynb
│   
├── models/
│   ├── yolov8n/
│   
├── reports/
│   ├── confusion_matrix.png
│   ├── violation_summary.csv
│   └── traffic_risk_report.pdf
├── requirements.txt
└── README.md

## Model Training

The model was trained on a custom annotated dataset of motorcycle riders under different violation scenarios.

Dataset Split:

Train: 87%

Validation: 8%

Test: 4%

## Evaluation Metrics

Model performance was evaluated using:

Confusion Matrix

Precision

Recall

mAP (Mean Average Precision)

Precision–Recall Curves

## Analytical Reporting Module

After detection, the system calculates:

Helmet compliance rate

Triple riding percentage

Mobile usage violation rate

Overall traffic safety risk score

This transforms the project from simple detection into a data-driven traffic monitoring and reporting system.

## Key Features

✔ Multi-class motorcycle violation detection
✔ Automated violation statistics generation
✔ Visual performance reports
✔ Scalable and modular design

