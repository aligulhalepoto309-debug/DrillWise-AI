# ⚓ DrillWise-AI: Total Drilling Lost Time (TDLT) Dashboard

An AI-based decision-support framework and interactive Streamlit web dashboard designed to quantify, analyze, and mitigate **Total Drilling Lost Time (TDLT)**—comprising **Non-Productive Time (NPT)** and **Inefficient Time (ILT)**—in onshore drilling operations across the Lower Indus Basin.

---

## 📌 Features

* **Real-Time TDLT Metrics:** Tracks TDLT, NPT, ILT, and TDLT percentage of total drilling time with period-over-period trend indicators.
* **NPT & ILT Breakdown:** Categorizes top operational time loss contributors (Stuck Pipe, Lost Circulation, Equipment Failure, Connection Time, Tripping Time, etc.).
* **AI Prediction & Feature Importance:** Integrates **XGBoost** model outputs and parameter feature importances (Formation, ROP, Torque, WOB, RPM) to detect risk before events occur.
* **Real-Time Decision Support:** High-priority alert panel providing actionable recommendations, risk level estimates, and prospective cost/time savings.
* **Root Cause & Remedy Matrix:** Structured operational guidance mapping causes to expected time impact and remedial actions.

---

## 📁 Repository Structure

```text
tdlt-dashboard/
│
├── app.py              # Main Streamlit dashboard application
├── requirements.txt    # Python package dependencies
├── README.md           # Project documentation
└── LICENSE             # MIT License
