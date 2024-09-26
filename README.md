Boombots: Deepfake Detection System
Project Overview
This repository contains the project developed for Smart India Hackathon 2024 under the problem statement ID SIH1683 titled "Development of AI/ML-based solution for detection of face-swap-based deep fake videos." The project focuses on creating an efficient and scalable solution for detecting deepfakes using advanced deep learning models and frameworks.

Problem Statement
The primary goal of the project is to develop a solution that detects face-swap-based deep fake videos using a hybrid LSTM-CNN model. Additionally, the system should be able to generate deepfakes and analyze video frames in real time.

Key Features
Hybrid Model: Combines LSTM for temporal analysis and ResNext CNN for feature extraction.
Real-World Ready: The system is trained on multiple large datasets like FaceForensic++, Deepfake Detection Challenge, and Celeb-DF.
User-Friendly Interface: Allows for simple video uploads and delivers real-time results.
Cross-Platform Integration: Can be extended from a web-based platform to a browser plugin for automated detection across multiple platforms.
Resource Efficient: Optimized for both high and low-performance devices.
Technical Approach
Algorithm Development: The core detection system uses a combination of LSTM-CNN models to analyze video frames.

Frameworks: The project is built using PyTorch and Django for the web application interface.

Datasets:

FaceForensic++
Deepfake Detection Challenge
Celeb-DF
Core Functionality:

Preprocessing: The input video is encoded, and faces are detected and aligned.
Feature Extraction: The CNN model extracts features from the aligned faces.
Manipulation Detection: The LSTM layers perform temporal analysis to detect any inconsistencies across video frames.
Output: The model provides a percentage score indicating the probability of the video being fake.
System Architecture
The system follows a structured process flow:

Video Input: User uploads the video through a web interface.
Image Pre-Processing: The uploaded video frames undergo face detection and alignment.
Deepfake Detection: The hybrid CNN-RNN model processes the frames to detect any manipulations.
Output: The system provides the likelihood of the video being a deepfake along with frame-by-frame analysis.
Feasibility and Viability
Challenges:
Evolving deepfake techniques make it difficult to detect new and more sophisticated manipulations.
High costs and market competition in developing scalable and real-time solutions.
Strategies:
Use adaptive learning to continuously update the models.
Leverage transfer learning to reduce computational costs and time during training.
Optimize the LSTM-CNN hybrid model for real-time performance on low-power devices.
Benefits:
Social: Enhances media literacy and reduces misinformation.
Economic: Lowers legal and reputational costs associated with misinformation.
Environmental: Reduces the environmental impact associated with misleading media production.
Getting Started
Requirements
Python 3.x
PyTorch
Django
MySQL
OpenCV (for face detection and video processing)
