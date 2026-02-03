# MyoAuth

This project is based on a biometric authentication system based on Surface Electromyography (sEMG) signals using a single-channel acquisition setup.
It explores the feasibility of using voluntary muscle activation patterns as a secure and liveness-aware biometric, addressing limitations of conventional authentication methods such as fingerprints, face recognition, and passwords.

The system records a user-defined authentication gesture as a biometric password, applies sliding window–based signal segmentation, extracts time-domain features from each segment, and performs user authentication using a K-Nearest Neighbors (KNN) classifier. The approach is designed to distinguish users even when similar gestures are performed, while keeping hardware requirements minimal.

This repository documents the signal acquisition pipeline, preprocessing, feature extraction methodology, and classification workflow, serving as an experimental foundation for further research in sEMG-based biometric security systems.
