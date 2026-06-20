**Project Overview:**

LipNet is a deep learning-based lip reading application that translates silent lip movements into text. The app utilizes facial landmarks and temporal convolutional networks to recognize spoken words without audio input. 

**Key Features:**

* Lip movement detection and translation
* Face and Lip Landmark tracking using OpenCv
* Deep Learning Model trained on GRID dataset.
* User Interface for input and output display

**Rational & Market Relevance:**

Why this project?
Silent communication is essential in many scenarios, like classrooms, libraries, or individuals with speech impairments. Current speech-to-text tools fail in a silent or noisy environment.

**Real World Problem Addressed:**

There’s a communication gap for people who are unable to speak or in environments where audio input isn't feasible. This app bridges that gap using computer vision and deep learning.

**Workflow & Methodology:**

**Approach & Techniques:**

* Preprocessing: Use OpenCV to extract lip keypoints from video frames.
* Model: Use CNN + LSTM or a 3D Convolutional Neural Network to capture spatial and temporal lip movement features.
* Training: Train on a dataset like GRID.
* Post-processing: Convert model output to readable text.

**Tools/Frameworks:**
* Python, OpenCV
* TensorFlow/Keras 
* Streamlit for the UI

**Development Steps:**

* Dataset Collection & Preprocessing
* Model Design & Training
* Lip Landmark Detection Pipeline
* UI Development
* Testing & Optimization

**Workflow**
  
  <img width="467" height="303" alt="work" src="https://github.com/user-attachments/assets/5ed6e0bd-cf21-40bc-84db-642cd2251788" />

**DEMO**


https://github.com/user-attachments/assets/047e6039-8208-42bd-ae0b-6cf94d7cbe87

