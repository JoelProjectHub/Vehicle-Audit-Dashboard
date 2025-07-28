# 🚗 Vehicle Audit Dashboard (Power BI + Power Apps)

An interactive dashboard and audit entry system designed to track, analyze, and improve vehicle inspection processes. Combines Power BI for reporting and Power Apps for real-time defect entry, integrated with automated workflows to streamline operations.

## ✨ Features
- 📊 **Defect Tracking & Scoring**:
  - Captures audit data with severity-based scoring (A/B/C scale).
  - Tracks defect trends over time to identify recurring issues.
- 🛠️ **Category Segmentation**:
  - Separates *Delivery* and *Procedure* defects for targeted analysis.
  - Highlights high-frequency and high-severity issues.
- 🔍 **Drillthrough Analytics**:
  - Ability to drill into individual vehicles or defect types for root cause analysis.
- 📈 **Productivity KPIs**:
  - Concern points per day, model-based defect rates, and goal rates.

## 🛠️ Tech Stack
- **Power BI**: Data visualization, DAX calculations, KPI design.
- **Power Apps**: Connects to custom audit entry system with multi-defect submission.
- **SharePoint / Excel**: Backend data storage.
- **DAX / Power Query**: ETL, custom measures, and time intelligence.

## 📂 Dashboard Highlights
- **Overview Page**: Audit KPIs and scoring summaries.
- **Defect Trends Page**: Time-based defect patterns and severity breakdown.
- **Vehicle Drillthrough**: Vehicle-specific defect history.
- **Model Analysis**: Average concern points per model for pattern detection.

## 🚀 How It Works
1. Auditors submit defect entries through the Power App.
2. Power BI pulls and transforms the data via Power Query.
3. DAX measures calculate KPIs like:
   - Average Daily Concern Points
   - Defect Rates by Model
   - Category-Specific Scoring (Delivery vs. Procedure)

## 📊 Business Impact
- Reduced manual data entry and reporting time.
- Improved defect visibility across vehicle models and categories.
- Enabled management to quickly identify operational issues and take corrective action.

## 🔮 Future Enhancements
- Implement mobile-responsive Power App UI for field auditing.
- Add predictive defect analysis using historical data.
- Integrate with live SQL backend for higher data volume.

---

## 👤 Author
**Joel Perez**  
- 🌐 [GitHub](https://github.com/JoelProjectHub)  
- 💼 [LinkedIn](https://linkedin.com/in/YOUR-LINK)  
