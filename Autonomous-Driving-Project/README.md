# Autonomous Driving Project

## Overview
This project explores Autonomous Driving concepts using Deep Learning, Computer Visio and Data Analysis techniques. The project is divided into two major parts:

1. Vehicle Detection and Classification using image data
2. Tesla Autonomous Driving Accident Analysis using Natural Language Processing (NLP)

The goal of the project is to understand how AI can be applied in autonomous driving systems for object detection, vehicle analysis and accident data interpretation.

---

# Part 1 — Vehicle Detection and Classification

## Objective
Build a deep learning pipeline for processing vehicle image datasets and preparing them for autonomous driving model training.

---

## Technologies Used
- Python
- OpenCV
- TensorFlow
- Keras
- NumPy
- Pandas
- Scikit-learn

---

## Workflow

### 1. Dataset Preparation
- Extracted image datasets
- Loaded vehicle label annotations
- Organized training data

### 2. Image Preprocessing
- Resized images to fixed dimensions
- Cleaned inconsistent image labels
- Prepared bounding box coordinates

### 3. Feature Engineering
- Converted labels into one-hot encoding
- Prepared image arrays for deep learning

### 4. Model Preparation
- Split dataset into training and testing sets
- Prepared vehicle classification pipeline

---

## Features
- Vehicle image preprocessing
- Bounding box handling
- Dataset cleaning
- Deep learning-ready image pipeline
- Vehicle class encoding

---

# Part 2 — Tesla Autonomous Driving Accident Analysis

## Objective
Analyze Tesla autonomous driving accident and fatality data using NLP and data analysis techniques.

---

## Technologies Used
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- NLTK

---

## Workflow

### 1. Data Inspection
- Checked missing values
- Inspected data types
- Visualized missing data patterns

### 2. Data Cleaning
Removed:
- unnecessary columns
- irrelevant links
- duplicate information
- unused identifiers

### 3. NLP Processing
Used NLTK for:
- tokenization
- lemmatization
- text preprocessing

### 4. Visualization
Generated:
- heatmaps
- data quality visualizations
- exploratory analysis plots

---

## Key Concepts Covered
- Computer Vision
- Image Processing
- Deep Learning
- Object Detection
- NLP
- Data Cleaning
- Exploratory Data Analysis
- Autonomous Driving Analytics

---

## Project Structure

Autonomous-Driving-Project/
│
├── data/
├── notebooks/
│   ├── autonomous_driving_part1.ipynb
│   └── autonomous_driving_part2.ipynb
├── outputs/
├── README.md
└── requirements.txt

---

## How to Run

1. Clone the repository

2. Install dependencies

pip install -r requirements.txt

3. Open Jupyter Notebook

jupyter notebook

4. Run notebook cells sequentially

---

## Future Improvements
- Build real-time vehicle detection system
- Implement YOLO or Faster R-CNN
- Add lane detection
- Train advanced CNN models
- Deploy autonomous driving dashboard
- Add real-time accident prediction analysis

---

## Skills Demonstrated
- Deep Learning
- Computer Vision
- NLP
- Data Preprocessing
- Image Handling
- Data Visualization
- TensorFlow & Keras
- Autonomous Driving Analytics

---

## Author
Faizan Khurshid