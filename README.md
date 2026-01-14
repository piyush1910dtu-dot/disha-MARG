# DishaMARG Lite 🚦
### Traffic Signal Strategy Exploration Platform (Digital Twin)

DishaMARG Lite is a software-based traffic simulation platform that allows users to
explore and compare different traffic signal strategies using simulated and
AI-assisted real-world data.

## 🎯 Problem
Traffic signal strategies cannot be freely tested on live roads due to safety and
stability constraints. This limits experimentation and learning.

## 💡 Solution
A digital twin–based traffic simulator that enables:
- Visual traffic flow simulation
- Fixed-time vs adaptive signal strategy comparison
- Strategy Memory to learn from past simulations

## 🧠 Key Features
- Single-intersection traffic simulation
- AI-assisted vehicle density estimation from real traffic videos
- Strategy Memory for scenario comparison
- Clean visual dashboard for analysis

## 🛠 Tech Stack
- Frontend: HTML / CSS / JavaScript
- Backend: Python
- AI: YOLOv8 (pretrained) + OpenCV
- Data Storage: JSON / SQLite

## 📊 How It Works
1. Real traffic video is analyzed to estimate vehicle density
2. Density is converted into simulation parameters
3. Signal strategies are simulated
4. Performance metrics are stored and compared

## 🚀 Demo
## 📸 Screenshots

### Landing Page
![Landing Page](s)
### Simulator Dashboard
![Simulator Dashboard](https://github.com/piyush1910dtu-dot/disha-MARG/blob/52d9504e011896fc3b7dade47271ffa8dafa8c3d/Screenshots/Simulation%20log.png)
### Strategy Memory
![Strategy Memory](https://github.com/piyush1910dtu-dot/disha-MARG/blob/acdb5731a187277e7cfa6cc1ffdf2bdb9d903eed/Screenshots/Strategy%20Logs.png)

## ⚠️ Disclaimer
This project is a conceptual simulation tool and does not control real traffic systems.

---
Built for Smart Mobility Hackathon 2026
