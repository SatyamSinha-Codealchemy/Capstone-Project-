# Capstone-Project-
Capstone Project IIT GUWAHATI
# 🚘 Dynamic Parking Pricing Model (Real-Time Simulation with Pathway)

This project simulates and implements dynamic pricing models for 14 urban parking spaces over a span of 73 days, with real-time ingestion and processing using [Pathway](https://pathway.com/). The core objective is to dynamically adjust parking prices based on demand patterns, real-time congestion, competition proximity, and rerouting decisions.

---

## 📦 Tech Stack Used

| Component        | Tech                          |
|------------------|-------------------------------|
| Language         | Python 3                      |
| Libraries        | Pandas, Numpy, Bokeh, Panel   |
| Real-time Engine | Pathway                       |
| Visualization    | Bokeh (interactive)           |
| Version Control  | Git, GitHub                   |

---
ARCHITECTURE DIAGRAM

![ARCHITECTURE DIAGRAM](https://github.com/user-attachments/assets/98944615-563e-4544-a9ef-1e41b78ff0a8)


🧠 Project Architecture & Workflow

This diagram outlines the architecture and workflow of our Dynamic Parking Pricing Model:

CSV Dataset (Parking Data)
Historical parking data is used as the foundation of the model.

Pathway Data Ingestion
The raw dataset is imported and validated for structure and consistency.

Preprocessing: Clean timestamps and features

Timestamps are standardized.

Missing or noisy values are handled.

Features relevant to pricing are engineered.

Model 1: Linear Pricing

A basic pricing model based on fixed time-based increments.

Model 2: Demand-Based Pricing

Adjusts prices dynamically depending on demand levels at different hours/days.

Model 3: Competitive Pricing

Simulates competition by factoring in nearby parking prices or theoretical competitors.

Final Price Calculation

Combines outputs of the models to determine optimal price using weighted logic.

Bokeh Visualization

Interactive plots are generated to visualize pricing trends and model outputs.

Display Adjusted Prices in Notebook

Final prices are output in a Jupyter Notebook for quick inspection and further analysis.

