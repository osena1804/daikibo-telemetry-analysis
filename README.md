# 🏭 Daikibo Telemetry Analysis

This project analyzes machine breakdowns across Daikibo’s four global factories using telemetry data collected in May 2021. Visualized using Tableau, the dashboard identifies the most failure-prone locations and devices.

# 🔍 Key Questions
1. Which factory experienced the most machine breakdowns?
2. Which machine types were most unreliable in that factory?

# 📊 Findings
- **Factory with Most Downtime**: Daikibo Factory Seiko (Osaka, Japan)
- **Most Unreliable Machine**: Laser Welder Machine

# 🛠 Tools Used
- Tableau Desktop 
- JSON data import
- Calculated Fields (`Unhealthy` = 10 mins per unhealthy status)
- Interactive Dashboard with filtering

# 📸 Dashboard
<img width="540" height="329" alt="image" src="https://github.com/user-attachments/assets/7966d97f-6db7-4acb-9183-edc9b9040be0" />


# 📈 Future Work
- Automate downtime tracking with Power BI
- Predictive modeling for machine failure
- Expand analysis to include maintenance logs
