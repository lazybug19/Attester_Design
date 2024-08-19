# Remote Attestation Framework
Ensemble Modelling based verifier-like Attestation Framework designed for IoT Network Security aiding in multilabel and multiclass malware detection.

## About
Attestation entails presenting verifiable evidence to an evaluator to substantiate claims regarding a target’s characteristics, ensuring that the firmware and configuration are reliable, verifying that the hardware is genuine. This [paper](https://github.com/lazybug19/Attester_Design/blob/main/Draft.pdf) proposes attestation solutions based on optimized ensemble learning and neural networks to bridge the existing gaps, enhancing security in the device lifecycle.

![verifier](https://github.com/user-attachments/assets/ad87bf6d-131e-4754-82e0-b9c8649f1222)

## Tech Stack Used
Ensemble models with bayesian hyperparameter tuning:

- Maximum Soft Voting Ensemble
  
![vote](https://github.com/user-attachments/assets/cbc8f809-3765-492c-9701-acd038e646b0)

- Stack Ensemble

<img width="581" alt="stack" src="https://github.com/user-attachments/assets/b4eb870f-7e7d-4eba-8ef9-9265fea58a1e">

## Key Features
- ML models were trained on a feature-engineered realistic cyber security [dataset](https://www.kaggle.com/datasets/mohamedamineferrag/edgeiiotset-cyber-security-dataset-of-iot-iiot/data) that covers Ransomware, Man in the middle and SQL Injection attacks, to name a few out of 14 other attacks detected in the IoT and Industrial IoT Perception Layer, gathered from 10 different types of IoT devices.
- Based on the data analysis of testbed and evaluating the performance of the proposed approaches, the framework promises an accuracy of 93% with 92% precision for detection of compromised IoT device and attack type.
- Stacking ensemble’s accuracy outperformed CNN model’s accuracy with early stopping callback in terms of multi-label classification which resulted in an accuracy of 81% with 80% precision.
