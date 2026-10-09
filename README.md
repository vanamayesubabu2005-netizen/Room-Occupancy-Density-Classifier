# Room Occupancy Density Classification Using CNNs

## 📌 Project Description

The **Room Occupancy Density Classification Using CNNs** project is a deep learning-based computer vision system designed to automatically classify room occupancy levels using images. The system categorizes indoor spaces into three classes: **Empty, Low Occupancy, and High Occupancy**.

The project uses a pre-trained **ResNet-18 Convolutional Neural Network (CNN)** with transfer learning to extract meaningful visual features and classify room images. Image preprocessing techniques, including resizing, normalization, and data augmentation, are applied to improve model performance and generalization across different lighting conditions, camera angles, and room layouts.

To improve model interpretability, **Grad-CAM (Gradient-weighted Class Activation Mapping)** is used to generate heatmaps that highlight the image regions influencing the model's predictions.

This system can support efficient space utilization and automated occupancy monitoring in classrooms, laboratories, libraries, and other shared indoor environments.

## 🎯 Objectives

* Automatically classify room images based on occupancy density.
* Apply CNNs and transfer learning for image classification.
* Reduce the complexity of individual person detection and counting.
* Evaluate model performance using accuracy, F1-score, and a confusion matrix.
* Use Grad-CAM to visualize the regions influencing predictions.
* Support better utilization of indoor spaces and campus facilities.

## 🛠️ Technologies Used

* **Python**
* **Deep Learning**
* **Convolutional Neural Networks (CNNs)**
* **ResNet-18**
* **Transfer Learning**
* **PyTorch**
* **Image Processing**
* **Grad-CAM**
* **Google Colab**

## 📂 Occupancy Classification Categories

1. **Empty:** A room with no people present.
2. **Low Occupancy:** A room with a small number of people or sparse occupancy.
3. **High Occupancy:** A room with a high density of people.

## ⚙️ Methodology

1. **Data Collection:** Use public classroom and crowd image datasets, along with a custom dataset collected from campus locations.
2. **Data Preprocessing:** Resize images to 224 × 224 pixels, normalize RGB channels, and apply data augmentation.
3. **Model Training:** Fine-tune a pre-trained ResNet-18 model using transfer learning.
4. **Occupancy Classification:** Predict one of the three occupancy categories.
5. **Model Evaluation:** Evaluate the model using accuracy, weighted F1-score, and a confusion matrix.
6. **Explainable AI:** Apply Grad-CAM to visualize important regions contributing to predictions.

## 📊 Model Performance

The trained ResNet-18 model achieved the following results, as reported in the project report:

* **Training Accuracy:** 100.00%
* **Validation Accuracy:** 99.51%
* **Custom Test Accuracy:** 97.60%
* **Validation Weighted F1-Score:** 99.51%
* **Custom Test Weighted F1-Score:** 97.58%

## 🌟 Applications

* Smart classrooms and educational institutions.
* Laboratory and library occupancy monitoring.
* Indoor space utilization and facility management.
* Smart campus management systems.
* Future integration with CCTV feeds and IoT-based smart building systems.

## 🚀 Future Enhancements

* Real-time occupancy classification using live camera feeds.
* Integration with IoT and smart building systems.
* Deployment on edge devices for efficient inference.
* Automatic alerts when a room reaches high occupancy.
* Training with larger and more diverse datasets.

## 📚 Datasets

* [Classroom Data – Kaggle](https://www.kaggle.com/datasets/harinivasganjarla/classroom-data/data)
* [Classroom Occupancy – Roboflow](https://app.roboflow.com/shaiksafiyahashmi-gmail-com/classroom-occupancy-air1s/overview)
* [Classroom Occupancy – Roboflow Universe](https://universe.roboflow.com/pragyas-workspace-jctq5/classroom-occupancy)

## 👥 Project Team

Developed as an academic Data Mining project by students of the Department of Computer Science and Engineering, Prasad V. Potluri Siddhartha Institute of Technology.

---

**Keywords:** Room Occupancy Classification, CNN, ResNet-18, Deep Learning, Transfer Learning, Computer Vision, Image Classification, Grad-CAM, Smart Campus.
