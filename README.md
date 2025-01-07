# Punchlist Analysis for a Large-Scale Mall Project

## 📅 Overview 

This project focuses on analyzing the punchlist for a large-scale mall project worth approximately **EGP 2 billion**. The mall consists of five main zones:  
1. **Retail Section**  
2. **Common Areas**  
3. **Food Court & Dining Areas**  
4. **Entertainment & Leisure Areas**  
5. **Parking & Services Areas**  

The analysis examines the punchlist after remedial work, showcasing the final status in terms of saved and deducted values. Additionally, insights into the negotiation outcomes and cost efficiency of the punchlist remediation process are provided.

---

## 🛠️ Tools Used 

- **Power BI**: For data visualization and dashboard creation.  
- **DAX (Data Analysis Expressions)**: For advanced calculations and measures.  
- **Power Query**: For data cleaning and transformation.

---

## 🌐 Data Source 

The data used in this analysis was provided by the Facility Management (FM) team and includes:
- The **primary punchlist** and its updates during progress tracking.
- Cost sheets detailing the remedial expenses.
- Continuous updates on progress milestones and inspection results.

---

## 🧹  Cleaning and Preparing Process 
Data preparation steps were performed using **Power Query**:
1. Removed redundant or duplicate entries to ensure data consistency.  
2. Transformed columns into their appropriate data types.  
3. Normalized data for uniformity and easier integration into the model.  
4. Merged relevant datasets to streamline analysis.  

---

## 🔗 Data Modeling 

- **Separate Tables**: Created for **Dates**, **Zones**, **Disciplines**, and **MEP Classifications**.  
- **Relationships**: Established one-to-many relationships between these tables and the punchlist items and cost tables.  
- **Calculated Columns**: Used to derive the rectified cost from the primary punchlist value.  
- **DAX Calculations**: Implemented advanced measures for cost efficiency, completion percentages, and deduction analysis.

---

## 🔍 Analysis Process 

1. **Inspection Progress**:  
   - **Rev. 1 Phase**: Completion of 48% of punchlist items.  
   - **Final Inspection**: Completion increased to 86%.  

2. **Additional Items**: Identified 20 new items (2.21% of the primary punchlist), shown in a detailed table in the dashboard.  

3. **Remedial Costs**:  
   - Total remedial cost: **EGP 7.6 million** (0.38% of total revenue).  
   - Categorized into:
     - Direct POs  
     - Material POs  
     - Manpower  
     - Indirect Expenses  

4.**Zone-Wise Analysis**:  
   - An area chart displays the **primary punchlist value**, **rectified value**, and **remaining value** for each zone.  
   - A **tooltip report** has been added to provide detailed insights, showing:  
     - **Primary Value** per discipline and MEP Classification.  
     - **Rectified Value** per discipline and MEP Classification.  
     - **Remaining Value** per discipline and MEP Classification.

5. **Timeline**:  
   - The project remediation spanned **91 days**, from **1/10/2024 to 1/12/2024**.  
   - A Gantt chart in the dashboard highlights:
     - Start and end dates for each zone.  
     - Progress tracking and milestones.  

6. **Negotiation Results**:  
   - Deduction factors applied during the negotiation meeting:
     - **20% of Civil items' value**  
     - **15% of Architecture items' value**  
     - **EGP 300,000 per zone** for MEP items (9.32% of deductions).  
   - Total deductions: **EGP 3.674 million**.  

7. **On-Site vs. Negotiation Results**:  
   - Savings difference: **EGP 394.73K** (1.52% more savings in the negotiation case).  

8. **Cost Efficiency**:  
   - Remedial costs of **EGP 7.5 million** resulted in savings of **EGP 26 million**, demonstrating a cost efficiency of **347%**.

---

## 📑 Sidebar and Navigation 

The Power BI dashboard includes an intuitive sidebar for navigation:  
1. **Icons for Dashboards**:  
   - 📊 On-Site Analysis  
   - 🤝 Final Status  

2. **Filter Menu**:  
   - Timeline Filter  
   - Filters for Zones, Discipline, and MEP Classification  
   - Actions include **Open**, **Close**, and **Clear Filters**.  

**Bookmarks** were used to enable smooth navigation and dynamic filtering.

---

## 📌 Key Findings 

This analysis yielded the following key insights:  
1. **Inspection Results**:  
   - Initial progress (Rev. 1) completed **48%** of the punchlist items.  
   - Final inspection completion reached **86%**.  

2. **Cost Distribution**:  
   - Total punchlist value: **EGP 30 million** (1.5% of total revenue).  
   - Rectified value after remedial work: **EGP 26 million**.  
   - Remaining punchlist value: **EGP 4 million** (0.2% of total revenue).  

3. **Additional Items**:  
   - 20 new items (2.21% of primary punchlist) were identified and added during the final inspection.  

4. **Remedial Cost Breakdown**:  
   - Total remedial cost: **EGP 7.5 million**, distributed as:
     - **75.87% Direct Costs**  
     - **24.13% Indirect Costs**  

5. **Negotiation Outcomes**:  
   - Final deduction applied: **EGP 3.674 million**.  
   - Savings from negotiation: **EGP 26 million** (87.75% of the punchlist value).  
   - Negotiation achieved a **1.52% higher saving** compared to the on-site analysis.  

6. **Cost Efficiency**:  
   - Every **EGP 1** spent resulted in a **EGP 3.47 saving**, demonstrating a cost efficiency of **347%**.  

---

## 💡 Conclusion 

This analysis highlights the importance of structured punchlist tracking, timely remediation, and negotiation in achieving cost savings and efficient project handing-over. The Power BI dashboards, advanced DAX measures, and robust data modeling contributed to actionable insights and efficient decision-making for this large-scale project.

---

## 📊 Dashboard
