# 🏥 AI-Based Hospital Resource Management System

An intelligent decision-support system developed to optimize hospital operations by efficiently managing patient flow, resource allocation, task prioritization, and staff scheduling using classical algorithms and an interactive graphical interface.

---

## 📌 Project Description

Efficient hospital management is critical to ensure timely patient care, optimal utilization of medical resources, and smooth operational workflows. Hospitals often struggle with:

- Department congestion
- Resource shortages
- Scheduling conflicts
- Poor patient routing

This project addresses these challenges by integrating multiple **algorithmic optimization techniques** into a single **AI-based Hospital Resource Management System**, supported by a **Tkinter-based GUI** for real-time visualization and interaction.

---

## 🎯 Objectives

- Optimize patient movement between hospital departments
- Maximize utilization of limited hospital resources
- Prioritize patients and tasks based on urgency
- Ensure conflict-free staff and room scheduling
- Provide an easy-to-use graphical dashboard for hospital administrators

---

## 🚀 System Features & Algorithms

### 📍 Patient Flow Optimization  
**Algorithm Used:** Multistage Graph + Dijkstra’s Algorithm  
- Hospital departments are modeled as graph nodes
- Edge weights represent time or cost between departments
- Finds the shortest and most efficient route for patient transfers
- Reduces congestion and waiting time

---

### 🧮 Resource Allocation  
**Algorithm Used:** Fractional Knapsack Algorithm  
- Optimally allocates limited resources such as beds, nurses, doctors, and medications
- Allows fractional allocation during high-demand situations
- Maximizes total priority benefit under capacity constraints

---

### ⚡ Patient & Task Prioritization  
**Algorithm Used:** Merge Sort  
- Sorts patients based on priority, severity, or treatment time
- Ensures critical cases are handled first
- Stable and efficient even for large datasets

---

### 👥 Staff Scheduling & Conflict Resolution  
**Algorithm Used:** 8 Queens Algorithm  
- Models scheduling as a constraint satisfaction problem
- Prevents conflicts such as overlapping shifts or double-booked rooms
- Visualized using a chessboard representation

---

### 🖥️ Interactive GUI  
**Technology:** Tkinter  
- Tab-based interface for each system module
- Real-time input and output within the same window
- Visual dashboards and charts using Matplotlib
- Designed for non-technical hospital staff

---

## 🛠️ Technologies Used

- **Programming Language:** Python  
- **GUI Framework:** Tkinter  
- **Visualization:** Matplotlib  
- **Image Processing:** PIL (Python Imaging Library)  
- **Algorithms Implemented:**
  - Multistage Graph
  - Dijkstra’s Algorithm
  - Fractional Knapsack
  - Merge Sort
  - 8 Queens Algorithm

---
🖥️ Dashboard Overview

<img width="1188" height="828" alt="image" src="https://github.com/user-attachments/assets/c2b45a1d-3b83-4cc8-8801-108e78bcd258" />

🧮 Resource Allocation – Fractional Knapsack

<img width="1193" height="663" alt="image" src="https://github.com/user-attachments/assets/09b2cbe0-23d8-4079-adc9-6feb33a87ed5" />
<img width="1194" height="163" alt="image" src="https://github.com/user-attachments/assets/62b11a42-a3e8-4b24-842d-66b80056f725" />
<img width="1201" height="169" alt="image" src="https://github.com/user-attachments/assets/acf6501f-ae25-49e0-aafe-a9f412eadb89" />
<img width="1193" height="139" alt="image" src="https://github.com/user-attachments/assets/ddeeaaf4-7108-445e-91e8-eb78583f5409" />

⚡ Patient Prioritization – Merge Sort

<img width="1196" height="842" alt="image" src="https://github.com/user-attachments/assets/b35d0eb0-59c6-4c5e-875f-3a061973d459" />

👥 Staff Scheduling – 8 Queens Algorithm

<img width="1196" height="831" alt="image" src="https://github.com/user-attachments/assets/32415c07-a9fd-48b1-a208-2c738491ca0f" />

📍 Patient Flow Optimization – Multistage Graph

<img width="1195" height="829" alt="image" src="https://github.com/user-attachments/assets/975215e6-5f32-41c2-bc7a-2d53aa3a7645" />

## ⚙️ How the System Works

- Hospital data such as patients, staff, resources, and departments is generated and modeled within the system.
- Each optimization algorithm operates independently on its relevant data.
- User interactions in the GUI trigger the execution of corresponding algorithms.
- Results are displayed instantly through tables, charts, and graphical visualizations.
- The system enables real-time analysis and supports effective decision-making.

---

## 🧪 Testing & Validation

- Tested with varying hospital sizes and department layouts.
- Simulated multiple resource availability scenarios.
- Verified correct patient prioritization and conflict-free scheduling.
- Ensured GUI responsiveness and overall usability.

---

## 📈 Future Enhancements

- Integration with real hospital databases.
- Machine learning–based patient demand prediction.
- Web-based or mobile application support.
- IoT-based real-time resource monitoring.

