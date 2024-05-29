---
title: "Projects"
permalink: /projects/
author_profile: true
---
## Academic/Professional Projects:

### Machine Learning-Based Malware Detection and Attack Challenge

**Overview:**
This project involved a multi-stage challenge focused on developing and testing machine learning models for malware detection and creating evasive malware binaries to test the robustness of these models. The challenge was divided into defensive and offensive roles, with teams of three members each participating in both.

**Defender's Challenge Specifications:**

**Deliverable:** 
- A self-contained Docker image with a model that can be queried via HTTP requests.

**Goals:**
- False Positive Rate (FPR): 1%
- True Positive Rate (TPR): 95%

**Constraints:**
- Maximum memory usage: 1 GB RAM
- Response time: 5 seconds per sample
- Timeouts will be considered evasions.

**Attacker's Challenge Specifications:**

**Deliverable:**
- Evasive malware binaries designed to bypass detection models.

**Goals:**
- Evade as many models as possible.

**Constraints:**
- Maximum file size for appended data: 5MB
- The evasive sample's execution in the sandbox must be equivalent to the original sample.

**Project Stages:**

1. **Black Box Defense:**
   - Teams developed machine learning models without any knowledge of the attack strategies used by the attackers. These models were then tested against a variety of malware samples to measure their effectiveness.

2. **White Box Defense:**
   - Teams refined their models with full knowledge of the attack strategies. This allowed for more targeted improvements in detection capabilities.

3. **Black Box Attack:**
   - Teams created evasive malware binaries without knowing the specifics of the defense models. The goal was to evade as many detection models as possible with these binaries.

4. **White Box Attack:**
   - Teams developed evasive strategies with full knowledge of the defense models' architecture and methods. This stage tested the limits of model robustness and adaptability.

**Team Composition and Challenge Execution:**
- Seven teams participated, each consisting of three members.
- The challenge required a balance of innovation in machine learning model development and creativity in devising effective evasion techniques.

**Results:**
The challenge successfully demonstrated the dynamic interplay between malware detection and evasion tactics, highlighting the importance of continuous improvement in cybersecurity measures. Teams showcased their ability to develop sophisticated models and adaptive evasion strategies within the given constraints, contributing valuable insights to the field of machine learning-based malware detection.

**Project URL:** [Machine Learning-Based Malware Detection and Attack Challenge](https://github.com/gnat-n/-ml-based-malware-defender-and-attack)

### Configuring Hadoop Cluster and Executing Big Data Applications with Apache Spark
***
- This project aims to configure a Hadoop cluster with Apache Hadoop as the underlying file system and Apache Spark as the execution engine. The main objective is to develop and run various small-scale applications utilizing the power of Hadoop and Spark. The project involves setting up the necessary infrastructure, configuring the cluster, and implementing several applications to leverage the capabilities of these technologies for handling big data efficiently.

### User Folder Migration
***
- Created a user folder migration functionality enabling 200 clients to seamlessly transition their thousands of user reports, graphs, imports, and other user components to a new folder structure. This transition occurred without any disruptions to ongoing scheduled tasks, batch processes, and favorite items. 

- Employing a Blue-green deployment strategy, we initially launched the feature within our internal system, meticulously assessing its impact due to its magnitude. Subsequently, we executed a gradual release for clients, ensuring a controlled and effective integration.

### Enhancing Vending Machine Application with Microservices and Containerization
***
- This project uses microservices architecture and containerization to improve a vending machine application. By replacing the weather selection mechanism, creating a new microservice for beverage preferences, and updating relevant functions, the project aims to optimize the vending machine application. The utilization of containerization, specifically Docker, facilitates seamless deployment and management of the application, enabling easier scaling and maintenance.

### AI-Powered Reversi Game
***
- This project focuses on developing an Artificial Intelligence (AI)-based Reversi game, featuring a visually appealing and interactive game interface created using Java Swing. The game employs the powerful alpha-beta pruning algorithm, enabling the computer player to intelligently determine its next move, resulting in a challenging and strategic gameplay experience for users.

### 4-bit Computer System Design
***
- We designed a 4-bit Computer System based on Simple As Possible (SAP) architecture. The computer system could run 28 assembly instructions. I was involved in designing the assembly instructions and implementing the system in Proteus Design Suite for simulating the system.

### Hall Management System
***
- The project involved the development of a comprehensive system for the university hall office, which included a desktop application with a Java Swing interface for efficient information management. In addition, a web application was created using the Laravel framework ensuring seamless accessibility and advanced features. Both applications were integrated with a MySQL database to ensure reliable data storage and retrieval, facilitating streamlined administrative processes and enhancing overall efficiency.

### 29 Card Game
***
- The project involved implementing a 29-card game using Java Multi-threading, enabling concurrent execution of multiple tasks and efficient gameplay. The game’s server-client communication was implemented using Java Socket Programming, ensuring reliable and real-time interaction between players. This approach facilitated seamless communication and synchronization between the game server and connected clients, enhancing the overall multiplayer gaming experience.