# Automated XSS Vulnerability Detection using SVM

![Project Status](https://img.shields.io/badge/status-completed-green.svg)

## Overview
Cross-Site Scripting (XSS) attacks are one of the most common and dangerous vulnerabilities in web applications, allowing attackers to inject malicious scripts into websites. This project leverages machine learning to classify websites as vulnerable or not to XSS attacks, enabling proactive defense mechanisms and enhancing web security.

## Features
- **Machine Learning Algorithms**: The project uses Support Vector Machines (SVM) as the primary model for classification.
- **Datasets**: Trained and evaluated on three datasets containing labeled URLs and their features, indicating vulnerability to XSS attacks.
- **Evaluation Metrics**: The model is evaluated using Accuracy, Precision, Recall, and F1 Score.

## Motivation
As web applications become more prevalent, the need for robust security measures grows. XSS attacks pose a significant threat to user data and website security. This project aims to provide an automated solution for detecting XSS vulnerabilities, saving time and resources for security analysts and developers.

## Datasets
The project uses the following datasets:
1. **Cross-Site Scripting XSS Dataset** (https://github.com/fmereani/Cross-Site-Scripting-XSS/tree/master):
   - Features: Parameter count, presence of script tags, special characters, etc.
   - Applications: Used in research papers for XSS vulnerability classification.
2. **XSS Dataset** (https://github.com/fawaz2015/XSS-dataset):
   - Features: URL length, special characters, query parameter structures, etc.
   - Applications: Used in academic studies focused on web security.
3. **XSS Dataset from Figshare** (https://figshare.com/articles/dataset/XSS_dataset1_csv/13046138):
   - Features: Number of parameters in the URL, types of characters, special symbols, etc.
   - Applications: Utilized for vulnerability detection and classification tasks.

## Methodology
1. **Task**: Classify whether a website is vulnerable to XSS attacks or not.
2. **Experience**: Train the model on labeled datasets containing URLs and their features.
3. **Performance**: Evaluate the model using classification accuracy, precision, recall, and F1 score.

## Benefits of the Solution
- Automated detection of XSS vulnerabilities, reducing the workload for security analysts.
- Can be integrated into security tools for continuous monitoring and threat assessment.
- Helps developers and security teams proactively secure web applications.

## Usage
The solution is designed for:
- Developers and security teams to assess the risk of XSS attacks.
- Integration into automated vulnerability scanning tools.
- Real-time scanning in web development platforms.

## Results
The model was trained and evaluated on the three datasets, achieving high accuracy and robust performance across all evaluation metrics. The SVM model demonstrated strong classification capabilities, making it a reliable choice for detecting XSS vulnerabilities.
