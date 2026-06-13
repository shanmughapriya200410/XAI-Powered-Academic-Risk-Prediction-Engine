# XAI-Powered-Academic-Risk-Prediction-Engine
# XAI-Powered Academic Risk Prediction Engine

> **Can we predict when a student is falling behind—and actually explain *why* in time to help them? This project bridges the gap between online engagement data, biological well-being, and transparent AI.**

---

## 📌 What is this project about?
Most modern AI systems in education work like a "black box". They can crunch numbers and guess which students might fail, but they can't tell an educator *why* a student is struggling. On top of that, standard models usually ignore the human side of learning—like whether a student is burnt out or chronically sleep-deprived.

This project solves those exact problems. By combining **Clickstream Analytics** (how a student interacts with online learning platforms) with **Physiological Data** (their sleep quality and habits), we build a 360-degree view of student risk. 

Best of all, we don't just output a risk score. Using Explainable AI (XAI), the system generates an individual "Diagnostic Receipt" for every student, giving teachers a clear, actionable roadmap on how to step in and help.

### 🚀 Key Highlights
* **The "Study Efficiency Index":** A custom feature engineered to weight hard academic study hours against biological recovery (sleep). It proves that studying for 6 hours on 2 hours of sleep is incredibly inefficient.
* **High-Precision Catching:** Built an optimized **XGBoost** model that hits **95.61% classification accuracy** on our evaluation cohort, prioritizing *Recall* so no struggling student gets overlooked.
* **No More Black Boxes:** Integrated **SHAP** and **LIME** to give both a school-wide overview of risk factors and a hyper-local breakdown for individual students.
* **Hybrid Deep Learning Core:** Built a parallel **CNN-LSTM-DNN** network using PyTorch to catch hidden spatial and behavioral patterns that standard algorithms
