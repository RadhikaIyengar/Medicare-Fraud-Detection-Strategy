# Medicare Fraud Detection: A Data-Driven Strategy

A machine learning and analytics project that detects and prevents Medicare fraud using CMS Open Payments data, OIG Exclusion Lists, and advanced predictive modeling techniques.

## 📋 Project Overview

Medicare fraud costs the U.S. healthcare system over **$100 billion annually**. This project presents a comprehensive data-driven strategy to proactively identify, detect, and prevent fraudulent billing practices across the healthcare system.

Built as a group project for the **Data Driven Organization** course at Yeshiva University.

## 👥 Team

| Name | Role |
|------|------|
| **Radhika Pujari** | Project Lead & Data Analyst |
| **Drashti Patel** | Data Analyst |
| **Mihir Sachdev** | Data Analyst |
| **Jinrong Chen** | Data Analyst |
| **Nikhil Anand** | Data Analyst |

## 🎯 Key Results

| Metric | Value |
|--------|-------|
| Data Sources Analyzed | **333M+ Open Payments records**, **77K+ OIG Exclusion records** |
| ML Models Compared | **4** (Logistic Regression, XGBoost, LightGBM, CatBoost) |
| Model Accuracy | **85%** with optimized XGBoost |
| Estimated Annual Savings | **$50M** in preventable fraud losses |
| False Positive Reduction | **25%** through risk-tiered approach |

## 📊 Project Structure

```
GroupA_Project_Medicare_Fraud_Detection/
├── Medicare Fraud Detection_ A Data-Driven Strategy.pptx   # Presentation slides
├── Medicare_Fraud_Dashboards.pbix                            # Power BI dashboards
├── Medicare_Fraud_Report.pdf                                 # Full project report
├── Datasets_Medicare.zip                                     # Source data (Open Payments + OIG)
├── Dashboard_Demo.zip                                        # Dashboard demo files
└── README.md                                                 # This file
```

## 🛠️ Tools & Technologies

- **Languages:** Python (Pandas, Scikit-learn, XGBoost, LightGBM, CatBoost)
- **Visualization:** Power BI, Matplotlib, Seaborn
- **Data Sources:** CMS Open Payments, OIG Exclusion Database
- **Techniques:** Data Integration, Machine Learning, Anomaly Detection, Risk Scoring

## 📈 Methodology

1. **Data Collection** — Merged CMS Open Payments (333M+ records) with OIG Exclusion List (77K+ records)
2. **Data Integration** — Linked payment and exclusion data via NPI and provider attributes
3. **Feature Engineering** — Extracted temporal patterns, provider risk indicators, and payment anomalies
4. **Model Training** — Compared Logistic Regression, XGBoost, LightGBM, and CatBoost
5. **Dashboard Development** — Built interactive Power BI dashboards for real-time monitoring
6. **Strategic Recommendations** — Proposed phased implementation with measurable KPIs

## 🚀 Strategic Recommendations

1. **Phased Rollout** — Start with high-risk specialties (Pain Management, Cardiology, Oncology)
2. **Automated Monitoring** — Implement real-time predictive dashboards
3. **Cross-Agency Collaboration** — Partner with CMS, OIG, and state Medicaid offices
4. **Continuous Improvement** — Regular model retraining and threshold optimization

## 📄 Files Description

| File | Description |
|------|-------------|
| `Medicare_Fraud_Report.pdf` | Complete project report with data sources, methodology, models, and recommendations |
| `Medicare Fraud Detection_ A Data-Driven Strategy.pptx` | Presentation slides summarizing the project |
| `Medicare_Fraud_Dashboards.pbix` | Power BI dashboard files for provider risk profiling and anomaly detection |
| `Datasets_Medicare.zip` | Compiled datasets from CMS Open Payments and OIG Exclusion databases |
| `Dashboard_Demo.zip` | Demo files showcasing the Power BI dashboard capabilities |

## 📜 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

## ⚠️ Disclaimer

This project is for **academic and educational purposes only**. It uses publicly available CMS data and does not contain any personally identifiable information (PII) or protected health information (PHI).
