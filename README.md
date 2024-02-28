---

# Face Detection using KNN Model

## Introduction
In coaching centers and educational institutions, the traditional method of taking attendance often involves students scanning attendance cards or signing attendance sheets. However, this method is not always efficient and reliable, as students can share their cards with others to mark attendance on their behalf, leading to inaccurate attendance records. To address this issue and enhance the efficiency of attendance management, we propose a Face Detection Attendance System.

## Motivation
The motivation behind this project is to improve the accuracy and reliability of attendance tracking in coaching centers and educational institutions. The current method of scanning attendance cards is prone to manipulation, as students can share their cards with others to mark their attendance, even if they are not present in class. By implementing a face detection attendance system, we aim to create a more secure and automated method of attendance management. With face detection technology, attendance can be marked accurately based on the presence of the individual's face, eliminating the possibility of proxy attendance.

## Implementation
- **Face Detection:** Utilizes the Haar Cascade Classifier for face detection, along with OpenCV for real-time face detection using the webcam.
- **K-Nearest Neighbors (KNN) Classifier:** Implements the KNN algorithm for facial recognition, training the model with a dataset of pre-registered faces and their corresponding labels.
- **Attendance Logging:** Logs attendance along with timestamps in CSV files, ensuring accurate record-keeping.

## Working Of Model
1. **add_faces.py:** Data collection module for capturing face data by taking 100 photos of each person's face using the camera. Stores face data and corresponding names in pickle files.
2. **test.py:** Implements the KNN model for facial recognition, loading the trained model and face data from pickle files and predicting the identity of faces based on input images.

## Technologies Used
- Python
- OpenCV
- scikit-learn
- Pickle

## Project Workflow
1. **Data Collection:** Run add_faces.py to capture face data for each person and ensure dataset diversity.
2. **Training:** Train the KNN model using the captured face data.
3. **Testing:** Run test.py to test the facial recognition system and predict the identity of faces using input images.

## Conclusion
The Face Detection project showcases the implementation of a facial recognition system using the KNN machine learning algorithm. By capturing face data and training the KNN model, the system can accurately predict the identity of faces based on input images. This project demonstrates the practical application of machine learning in real-world scenarios and highlights the importance of data collection and model training in achieving accurate results.

The Face Detection Attendance System offers a more reliable and secure method of attendance management compared to traditional methods. By leveraging face detection technology and machine learning algorithms, the system accurately identifies individuals and records their attendance in real-time.

---
