# Security and Privacy in Machine Learning — Homework Implementations

This repository contains my implementations for the **Security and Privacy in Machine Learning** course.  
Each homework focuses on a different aspect of secure and privacy-preserving ML systems — from basic neural network construction to advanced adversarial attacks, defenses, and differential privacy.

---

## 📂 Homeworks

### [HW1 — Introduction & Neural Network from Scratch](./HW1)
- Implemented a simple feed-forward neural network **from scratch** in Python (no ML frameworks).
- Covered:
  - Forward propagation
  - Backpropagation
  - Gradient descent
  - Basic classification tasks

---

### [HW2 — Adversarial Attacks on Neural Networks](./HW2)
- Explored methods to craft **adversarial examples** that fool trained models.
- Implemented:
  - FGSM *(Fast Gradient Sign Method)*
  - PGD *(Projected Gradient Descent)*
  - UAP *(Universal Adversarial Perturbations)*

---

### [HW3 — Robustness & Defenses](./HW3)
- Investigated strategies to make models more robust against adversarial inputs.
- Implemented:
  - Adversarial training
  - Defensive distillation
  - Other defense mechanisms

---

### [HW4 — Adversarial Model Extraction & Data Poisoning](./HW4)
- Studied threats to ML models beyond direct adversarial examples.
- Implemented:
  - **Model extraction attacks** — replicating a target model’s behavior
  - **Data poisoning attacks** — manipulating training data to degrade performance

---

### [HW5 — Differential Privacy in Machine Learning](./HW5)
- Integrated **Differential Privacy** into model training to protect sensitive data.
- Covered:
  - DP-SGD (Differentially Private Stochastic Gradient Descent)
  - Privacy budget & ε, δ parameters
  - Trade-offs between accuracy and privacy

---

## 🛠️ Tech Stack
- **Language:** Python 3.x  
- **Libraries:** NumPy, PyTorch / TensorFlow (where applicable), Matplotlib, SciPy  

---

## ⚠️ Disclaimer
All implementations are for **educational purposes only**.  
Some techniques here can be harmful if misused — please apply them ethically.

---

## 📜 License
This repository is licensed under the [MIT License](./LICENSE).

