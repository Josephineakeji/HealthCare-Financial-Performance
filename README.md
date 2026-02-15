# Healthcare Financial Performance Dashboard 

<img width="1344" height="700" alt="cover photo" src="https://github.com/user-attachments/assets/621baff2-37d0-4fe5-88e1-7cb898418cb2" />

--- 

## Project Summary

This project is an interactive Healthcare Financial Performance Dashboard built in Power BI to analyze hospital billing, cost drivers, insurance coverage, and provider performance. Using structured data modeling, DAX measures, and custom UI design, the dashboard provides decision-makers with a clear view of revenue composition, patient cost burden, departmental performance, and procedure trends. The solution combines data transformation, analytical modeling, and presentation design to produce a decision-ready reporting tool.

---


## Project Overview

The dashboard explores the financial and operational performance of a healthcare center by transforming visit-level data into actionable metrics and KPIs. It focuses on billing structure, treatment and medication costs, insurance contributions, and patient out-of-pocket expenses. Interactive visuals allow slicing by geography, time, race, department, procedure, and service type.

The project emphasizes:

* Financial transparency across cost components
* Department and procedure-level performance tracking
* Diagnosis and service type analysis
* Interactive geographic and time-based exploration

---

## Tools Used

* Power BI Desktop — Data modeling, visualization, and reporting
* Power Query — Data cleaning and transformation
* DAX — Measures, calculated columns, calculated tables, KPI logic
* PowerPoint — Custom dashboard background and UI layout design

---

## Dataset

Healthcare dataset contain the following tables:

* cities
* DateTable
* departments
* diagnoses
* insurance
* Patient Location Switch
* patients
* procedures
* providers
* visits

---

## Technical Flow

**Data Preparation**

Healthcare visit and reference tables were imported into Power BI and prepared for analysis. Key date fields were standardized, numeric cost fields were validated, and data quality checks were performed to ensure accurate downstream calculations.

**Data Modeling**

A structured analytical model was developed using a fact-and-dimension approach. A dedicated calendar table was created to enable time intelligence and consistent date slicing. Relationships were established across clinical, financial, provider, and geographic tables. A separate measures table was introduced to centralize KPIs and improve model organization.

**Feature Engineering**

Additional calculated fields were introduced to deepen the analysis, including stay-duration indicators and derived cost elements. These enhancements improved billing accuracy and strengthened operational insight generation.

**KPI & Measure Development**

Primary financial metrics were developed to monitor overall and component-level costs, insurance contributions, and patient out-of-pocket responsibility. Complementary KPIs were added to show both aggregate values and per-visit averages, supporting benchmarking and trend analysis.

**Visualization & Analytics Layer**

Interactive visuals were designed to analyze billing across procedures, departments, diagnoses, service types, geography, race and time. Percentage-of-total metrics were incorporated to highlight contribution shares and relative performance across categories.

**Interaction & User Experience Design**

The dashboard interface was enhanced with custom layout elements and a structured visual theme. Interactive controls were added to support dynamic filtering and parameter-driven geographic views. A toggleable filter panel was implemented to keep the report clean while preserving advanced exploration capability.

**Key KPI Outputs**

The completed model provides a unified set of financial KPIs, including total billing, detailed cost components, insurance contributions, patient out-of-pocket burden, and average metrics per visit.

---

## Data Model 

<img width="816" height="377" alt="Model view" src="https://github.com/user-attachments/assets/80d1fd09-a6a8-45db-9976-078d8866d499" />

---

## Dashboard Preview

![Healthcare Financial Performance](https://github.com/user-attachments/assets/c2cc0731-c5cb-44fc-b1ab-6db24cd00dc1)

---

## Key Insights 

The dashboard highlights major billing drivers, high-impact procedures and departments, service-type cost distribution, insurance offset effects, and geographic concentration patterns, enabling faster financial and operational assessment.

**Department Billing Distribution**

<img width="636" height="404" alt="Billing by department" src="https://github.com/user-attachments/assets/b8561ba5-2b4e-42b7-a935-d66cbc37e9f5" />

* Cardiology is the top revenue-generating department, contributing £846,925 (25%) of total billing.

* Orthopedics closely follows with £813,253 (24%), showing that musculoskeletal and cardiac services together account for nearly half of all billing.

* General Surgery contributes £783,247 (23%), placing the top three departments at a combined 72% of total billing, indicating strong revenue concentration.

* Neurology (£478,200 — 14%) and Pediatrics (£434,450 — 13%) form a significantly smaller share, suggesting lower visit volume, lower procedure cost, or shorter stays compared to the top three departments.

Insight: Revenue is highly concentrated in Cardiology, Orthopedics, and General Surgery, making them priority areas for cost control and resource optimization.

**Procedure Billing Contribution**

<img width="632" height="404" alt="Billing by procedure" src="https://github.com/user-attachments/assets/5b78bcca-6473-464f-af76-07ddff899e56" />

* X-Ray is the highest billing procedure at £1,053,529 (31%), making it the single largest contributor.

* CT Scan generates £805,508 (24%), confirming diagnostic imaging as a major revenue driver.

* MRI Scan contributes £600,739 (18%).

* Ultrasound (£481,347 — 14%) and Blood Test (£414,952 — 12%) contribute smaller but still meaningful shares.

* The top two procedures (X-Ray + CT Scan) together account for 55% of total procedure billing.

Insight: Diagnostic imaging dominates procedure revenue, with X-Ray and CT scans alone generating over half of procedure billing, indicating heavy utilization and/or higher unit pricing.

**Diagnosis vs Service Type Mix**

<img width="634" height="401" alt="Billing by diagnosis" src="https://github.com/user-attachments/assets/4503b886-94bd-4da6-af61-6ad6834204be" />

* Outpatient services represent the largest billing share across most diagnoses, indicating that a majority of cases are managed without extended admission.

* Emergency billing share is strongest for Asthma and Fracture, suggesting more acute care patterns.

* Inpatient contribution is more pronounced in Fracture and Asthma compared to Hypertension and Appendicitis.

* Hypertension and Appendicitis skew more toward outpatient care distribution.

Insight: The majority of diagnoses are managed mainly through outpatient services, while Asthma and Fracture have a larger share of emergency and inpatient costs, indicating higher case severity and greater resource utilization.

---

## Key Analytical Questions Answered

The solution enables assessment of cost composition, revenue distribution, department and procedure performance, service-type patterns, patient financial responsibility, race differences, and KPI trends over time.

some specific questions addressed:

* Which departments and procedures generate the highest share of total billing revenue?

* What are the main cost drivers across treatment, medication, and room charges?

* How is billing distributed across diagnosis categories and service types (Emergency, Inpatient, Outpatient)?

* How much of total cost is covered by insurance versus patient out-of-pocket spending?

* How does billing performance vary across geography and over time?

---

## Strategic Value

The dashboard delivers a decision-focused analytical view that helps guide cost management, resource allocation, coverage planning, and operational performance tracking across healthcare services.

---

## Recommendations

- **Focus on High-Revenue Departments**: Prioritize cost control and operational efficiency in Cardiology, Orthopedics, and General Surgery, as they contribute the largest share of total billing.

- **Optimize Diagnostic Imaging Use**: Review utilization patterns for high-billing procedures such as X-Ray and CT scans to ensure appropriate ordering and reduce unnecessary repeat tests.

- **Strengthen Acute Care Planning**: Improve emergency and inpatient resource readiness for high-acuity diagnoses like asthma and fracture that show heavier emergency and inpatient cost weight.

- **Enhance Insurance Coverage Analysis**: Monitor insurance vs out-of-pocket cost splits to identify patient burden risks and support better coverage planning.

- **Track Outpatient Efficiency**: Since most diagnoses are managed through outpatient services, invest in outpatient workflow optimization to maintain throughput and cost efficiency.

---

## Conclusion

An interactive, executive-ready healthcare financial analytics dashboard that translates raw visit data into actionable operational and financial intelligence.
A fully interactive, executive-ready healthcare financial dashboard that combines strong data modeling, DAX analytics, and UI design to support operational and financial decision-making.

---

## Future Considerations

* Outcome + Cost Integration: Combine clinical outcome metrics with financial data to evaluate value of care, not just cost of care.

* Real-Time Data Refresh: Integrate automated or near real-time data feeds to support continuous performance monitoring.

* Patient Segment Deep Dive: Expand analysis by age group, risk category, and comorbidity to better understand high-cost patient segments.

---

## License
This project is licensed under the MIT License.


