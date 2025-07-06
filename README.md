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

## 🏗️ Architecture Diagram (Mermaid)

```mermaid
graph TD
    A[CSV Dataset (Historical Parking Data)] --> B[Pathway Data Ingestion]
    B --> C[Preprocessing: Timestamp + Features]
    C --> D1[Model 1: Linear Pricing]
    C --> D2[Model 2: Demand-Based Pricing]
    C --> D3[Model 3: Competitive Pricing]
    D3 --> E[Real-Time Price Adjustment + Rerouting]
    E --> F[Bokeh + Panel Visualizations]
