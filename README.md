# Traffic-Violation-Dashboard

This project analyzes traffic violation data collected from multiple devices across different cities to understand compliance levels, violation types, and resolution effectiveness. The analysis is visualized using an interactive Excel dashboard with supporting charts and metrics.

---


🎯 **Business Objectives**  
- Analyze overall traffic violation trends by severity and type  
- Identify high-risk violation types and cities with frequent offenses  
- Track active, solved, and ignored violations over time  
- Enable interactive filtering to support faster, data-driven enforcement decisions  

---
**Dataset Description**
The dataset contains device-level traffic violation records with the following fields:  

- Device Name  
- Compliance (Severe, Medium, Light, Compliant)  
- Violation Type (Speeding, Red Light Violation, Seatbelt Violation, No License, Illegal U-turn, No Helmet)  
- Violation Date  
- City  
- Total Rules  
- Total Violations  
- Active Violations  
- Solved Violations  
- Ignored Violations  
- Solving Time  
- Environment Managed  
- Environment Disabled  

📅 **Time Period:** 2023–2024  
📈 **Data Type:** Traffic Violation Device Records  

---
**Data Cleaning Methodology**
The following steps were performed to clean and prepare the dataset for analysis:

- **Duplicate Removal**  
  Removed any duplicate device entries to ensure accurate violation counts.  


- **Formated Total Rules Column**  
  Some data in this column were string,so it's converted to number.  

- **Date Formatting**  
  Converted all Violation Date entries into a consistent `DD/MM/YYYY` format.  

- **Validated Final Dataset**  
  Confirmed that all rows were complete, readable, and ready for dashboard visualization without missing or inconsistent values.

---

🛠 **Tools & Techniques Used**  
- Microsoft Excel  
- Pivot Tables & Pivot Charts  
- Slicers & Timelines  
- Data Cleaning & Formatting  
- Calculated Fields (KPIs: Active, Solved, Ignored Violations, Resolution Efficiency)  
- Interactive Dashboard Design

---


📊 **Dashboard Features**  

**Key Performance Indicators (KPIs):**  
- Total Violations  
- Active Violations  
- Solved Violations  
- Ignored Violations  

**Analysis & Visualizations:**  
- Total Violations by it's Type  
- Active Violations and Helper Distribution by City  
- No. of Active and Solved Violation Analysis  
- Trend of Solved Violations by Compilance
- Actived,Solved and Ignored Viloation treds Analysis
- Interactive Filters: Device Year, Violation Type, Compliance Level and City.

---




## Key Insights

### Violation type Analysis
- Red Light Violations are the most frequent traffic offense, accounting for 517 out of 2,307 total violations (~22.4%), followed closely by No Helmet violations (~20%). This indicates that intersections and areas where red-light compliance and helmet usage are critical should be prioritized for enforcement and awareness campaigns.

### Violations Over City Analysis
- New York has the highest number of active violations (167 out of 720, ~23%), followed by London (147) and Sydney (126). This suggests that these cities may require increased monitoring or faster resolution processes to reduce pending violations, while cities like Tokyo (37) and Singapore (54) have better current compliance or resolution effectiveness.
- While New York has the highest number of active violations (167), its “Helper” value (33) is the lowest among all cities, suggesting that despite high violation counts, the proportion of issues yet to be addressed is relatively small.
  
### Active and Resolved Violation Over Time Analysis
- Violations resolved within <1 Week account for the highest number of solved cases (338 out of 1,041, ~32%), while also having the largest number of active violations (283 out of 720, ~39%). This indicates that although many violations are being resolved within a week, there is still a significant backlog of active cases in this TAT range.

### Total Violation by Compilance Analysis
- Severe Violations account for the majority of traffic violations (1,158 out of 2,307, ~50%), indicating that half of all violations are of high severity and likely require immediate enforcement or stricter monitoring. In comparison, Compliant devices and Light Violations have similar totals (~406–409 each), while Medium Violations are lower (~334), showing that moderate and minor issues are less frequent.
  
### Active,Resolved  and Ignored Violation Analysis based on Copilance type
- Severe Violations have the highest counts across all categories: 310 active, 471 solved, and 217 ignored, highlighting that these high-severity violations not only dominate the dataset but also represent the biggest enforcement challenge.
- Medium Violations show a relatively balanced distribution between active (190) and solved (191), but still have a significant number ignored (106), suggesting moderate issues may be slipping through.
- Light Violations have more solved cases (235) than active (131) or ignored (114), indicating effective resolution for minor issues.
- Compliant devices naturally have fewer active (89) and ignored (94) cases, showing that proper compliance reduces enforcement burden.



### Overall Takeaways
- **Severe Violations dominate:** ~50% of total violations; highest active, solved, and ignored counts.
- **High-risk cities:** New York, London, Sydney need increased monitoring and faster resolution.
- **Top violation types:** Red Light (~22%) and No Helmet (~20%) should be prioritized for enforcement.

- **Resolution efficiency matters:** Most violations resolved within <1 week; faster resolution (<12 hours) reduces backlog.

- **Compliance reduces burden:** Compliant devices have fewer active and ignored violations.

- **Medium and Light Violations:** Generally well-managed but ignored cases still need attention.

- **Strategic focus:** Target high-severity violations, critical cities, and major violation types to improve road safety.
