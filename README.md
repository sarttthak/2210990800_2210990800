# 2210990800_2210990801
# Digital Behaviour-Based Risk Detection Using Machine Learning

> A research paper submitted in partial fulfillment of the B.E. degree in Computer Science and Engineering, Chitkara University, Punjab, India.

---

## 📄 Abstract

This paper investigates the deployment of **Digital Behaviour-Based Risk Detection** using advanced Machine Learning (ML) methodologies. It examines the critical paradigm shift from static, perimeter-focused defenses toward dynamic, context-aware **User and Entity Behavior Analytics (UEBA)** — and how models ranging from ensemble methods (Random Forest, XGBoost) to deep sequential architectures (LSTM, BiLSTM-VAE) enable continuous, high-precision anomaly detection across enterprise, financial, and clinical domains.

The paper also addresses cross-disciplinary applications in cybersecurity, financial fraud prevention, and proactive mental health risk identification via digital phenotyping, while highlighting the indispensable role of **Explainable AI (XAI)** in bridging algorithmic output and human analyst trust.

---

## 👥 Authors

| Name | Email | Institution |
|---|---|---|
| Sarthak Gupta | sarthak800.be22@chitkara.edu.in | Chitkara University, Punjab |
| Sarthak Jyoti Mishra | sarthak801.be22@chitkara.edu.in | Chitkara University, Punjab |
| Shikha Tuteja | shikha.1290@chitkara.edu.in | Chitkara University, Punjab |

---


## 🔑 Keywords

`Machine Learning` `Digital Behavior Analytics` `UEBA` `Insider Threat Detection` `Deep Learning` `Explainable AI (XAI)` `Cybersecurity` `Anomaly Detection` `Behavioral Biometrics` `LSTM` `Digital Phenotyping` `Fraud Detection` `Risk Management`

---

## 📚 Topics Covered

### Core Areas
- **User and Entity Behavior Analytics (UEBA)** — continuous behavioral baselining and deviation scoring
- **Anomaly Detection** — supervised and unsupervised approaches for identifying malicious activity
- **Behavioral Biometrics** — keystroke dynamics, mouse trajectories, touchscreen pressure analysis
- **Digital Phenotyping** — leveraging smartphone and social media data for mental health risk prediction

### Machine Learning Architectures Evaluated
| Model | Use Case | Strength |
|---|---|---|
| Random Forest | Real-time classification | High precision, low latency |
| XGBoost | Tabular enterprise data | Robustness against overfitting |
| LSTM / BiLSTM | Sequential anomaly detection | Temporal context retention |
| Deep Autoencoders | Unsupervised anomaly detection | Handles class imbalance |
| BiLSTM-VAE | Adversarial environments | Generative robustness |
| SVM | Behavioral biometrics | Strong margin-based classification |

### Key Challenges Addressed
- High false-positive rates and SOC alert fatigue
- Severe class imbalance in anomaly datasets
- "Black box" interpretability of deep learning models
- Data privacy constraints (GDPR, CCPA compliance)
- Adversarial AI and model poisoning attacks

---

## 📊 Research Methodology

- **Mixed-methods** paradigm combining quantitative statistical analysis with systematic literature review (2017–2026)
- **SMOTE** applied for class imbalance mitigation in training datasets
- **Chi-Square feature selection** and **PCA** for dimensionality reduction
- **k-fold cross-validation** to prevent data leakage
- Primary metrics: Precision, Recall, F1-Score, ROC-AUC (with Recall prioritized over raw accuracy)

---

## 📈 Key Findings

1. **Signature-based defenses are obsolete** — up to 80% of modern cyberattacks are entirely malware-free, making behavioral ML a mandatory enterprise security layer.
2. **Ensemble models** (RF, XGBoost) are optimal for real-time classification — accuracy rates of 89–99.7% on benchmark datasets.
3. **LSTM autoencoders** reduce false positives by up to 38% while achieving 94.7% detection accuracy on imbalanced datasets.
4. **XAI is a prerequisite** — SHAP and LIME integration is critical for analyst trust and automated incident response.
5. **Behavioral biometrics** achieve F1-scores of 95.1% and prove highly resilient against AI-generated spoofing attacks.
6. **Advanced UEBA maturity** correlates strongly with faster breach detection (5–12 days vs. 55–82 days for basic systems).

---

## 🧪 Statistical Validation (Chi-Square Results)

| Hypothesis | χ² Statistic | p-value | Decision |
|---|---|---|---|
| H1: Ensemble models reduce false positives | 8.49 | 0.0036 | Reject H0 ✅ |
| H2: LSTM reduces breach detection time | 14.22 | 0.0008 | Reject H0 ✅ |
| H3: XAI increases analyst response speed | 6.75 | 0.0093 | Reject H0 ✅ |
| H4: Behavioral biometrics improve ATO detection | 32.88 | <0.0001 | Reject H0 ✅ |

All four alternative hypotheses confirmed at α = 0.05.

---

## 🔭 Future Scope

- **Federated Learning** — privacy-preserving distributed model training at the edge
- **Agentic AI systems** — autonomous, multi-agent UEBA platforms for real-time threat hunting
- **Multimodal behavioral fusion** — combining digital phenotyping with wearable physiological biometrics
- **Quantum Machine Learning (QML)** — for instantaneous anomaly detection at global network scale

---


## 📜 License

This research paper is submitted as part of an academic requirement at Chitkara University. All cited works belong to their respective authors and publishers. Please cite this work appropriately if referenced.

---

## 🙏 Acknowledgment

The authors acknowledge the guidance of faculty at Chitkara University, Punjab, and the authors of the 21 peer-reviewed sources that form the scholarly foundation of this research.
