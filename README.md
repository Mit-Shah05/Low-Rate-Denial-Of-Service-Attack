# Low-Rate-Denial-Of-Service-Attack
# Overview
This repository focuses on the study and analysis of Low and Slow Denial of Service (LDOS) attacks, which exploit prolonged low-rate requests to exhaust server resources without triggering traditional detection mechanisms. The project explores LDOS behavior using multiple independent approaches to understand traffic patterns, system impact, and detection challenges.

# Project Structure
The project is divided into three independent modules, each analyzing LDOS attacks from a different technical perspective:

Binary Classification-Based Detection:
Implements a binary classification approach to differentiate between normal traffic and LDOS attack traffic based on observed network features.

t-SNE Traffic Visualization:
Uses t-SNE dimensionality reduction to visualize high-dimensional traffic data and identify hidden patterns and clustering between normal and malicious traffic.

Multithreaded LDOS Attack Simulation: 
Simulates LDOS attacks using multithreading to analyze how concurrent low-rate requests can degrade server performance over time.
Each module is implemented and evaluated separately to provide a comprehensive understanding of LDOS attack behavior.

# Technologies Used
Python

Multithreading

Data Analysis & Visualization

Computer Networks & Network Security

# Objectives
Understand the working principles of Low and Slow DoS attacks

Analyze traffic behavior and system impact of LDOS

Explore multiple detection and analysis techniques

Strengthen practical understanding of network security concepts

# Usage
Each module is organized into separate directories with instructions provided within the respective folders. Modules can be executed independently based on the analysis or simulation required.

Academic Note
This project was developed as part of an academic study to explore LDOS attack behavior and analysis techniques. It is intended for educational and research purposes only.
