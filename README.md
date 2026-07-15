# Carpal Tunnel Syndrome Diagnosis System

An end-to-end computer-aided diagnosis system that combines nerve conduction waveform analysis, wrist ultrasound imaging, backend services, a clinical web application, and a patient mobile application to support carpal tunnel syndrome assessment.

## Repositories

- [Clinical Web Application](https://github.com/linh123-newbie/CTS_demo)  
  React application for doctors to manage patients, review examination results, adjust waveform markers, inspect ultrasound segmentation, and confirm AI predictions.

- [Backend API](https://github.com/linh123-newbie/CTS_backend)  
  ASP.NET Core Web API responsible for authentication, patient records, clinical examinations, result storage, and communication with AI microservices.

- [NCS Waveform AI Service](https://github.com/linh123-newbie/cts)  
  Python service for processing SNAP and CMAP waveform data, extracting nerve conduction features, and classifying CTS into four clinical severity levels using machine learning.

- [Ultrasound AI Service](https://github.com/linh123-newbie/cts_ultrasound)  
  Python service for median nerve segmentation, structural feature extraction, image classification, and gated feature fusion.

- [Patient Mobile Application](https://github.com/linh123-newbie/cts-user-mobile)  
  Flutter application that allows users to view examination results, complete medical questionnaires, perform the Phalen’s test, and track disease progression.

## Main Features

- Four-level CTS severity classification using SNAP and CMAP waveforms
- Waveform processing and nerve conduction feature extraction
- Median nerve segmentation from wrist ultrasound images
- Ultrasound classification using DenseNet-121
- Gated fusion of image embeddings and structural features
- Clinical web interface for doctors
- Patient examination history and result tracking
- Phalen’s test and medical questionnaires
- Independent AI microservices deployed on a Linux VPS
- Automated CI/CD deployment using GitHub Actions

## Tech Stack

- **Backend:** ASP.NET Core, Entity Framework Core, PostgreSQL
- **Web:** React
- **Mobile:** Flutter
- **AI & Machine Learning:** Python, PyTorch, scikit-learn, MONAI, OpenCV
- **API Services:** FastAPI
- **Deployment:** Linux VPS, GitHub Actions, CI/CD
