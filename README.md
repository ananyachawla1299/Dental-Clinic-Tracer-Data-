# Bundled Care Approach Benchmarking Dashboard

> **Translating clinical audit data into actionable quality improvement insights**

**[View Interactive Dashboard →](https://ananyachawla1299.github.io/Dental-Clinic-Tracer-Data-/)**

---

## What This Demonstrates

Quality improvement in pediatric healthcare requires more than collecting data. It requires making that data accessible, interpretable, and actionable for frontline providers. This interactive dashboard transforms clinical audit findings into visual insights that drive targeted improvement in family-centered procedural care.

This project showcases how health informatics principles can bridge the gap between QI findings and clinical practice change. I built this visualization to support a two-phase quality improvement initiative in a pediatric dental clinic, demonstrating my ability to translate complex compliance data into stakeholder-ready decision-support tools.

---

## The Project

**Context:** Clinical audit and quality improvement initiative  
**Setting:** Pediatric dental clinic  
**Sample:** 22 direct observations of dental procedures (extractions, restorations, hygiene, new patient exams)  
**Focus:** Benchmarking baseline compliance with bundled care approach (BCA) elements before targeted education interventions

**Note:** In the interactive dashboard, the bundled care approach is branded as "Comfort PACT" for clinical stakeholder familiarity. The underlying methodology and BCA framework remain the same.

This dashboard visualizes Phase 1 baseline data from a larger two-phase improvement initiative. The goal is to identify specific gaps in family-centered procedural care and inform tailored staff education.

---

## My Contributions

**Methodology Design:**  
Developed the benchmarking framework and observation protocol. This required translating five validated BCA elements (Preparation, Communication, Comfort Positions, Alternate Focus, Medication) into 23 observable, behavior-based indicators that research staff could reliably assess during live clinical procedures.

**Data Analysis & Reporting:**  
Analyzed compliance patterns across elements, demographics, and procedure types. Created the clinical audit report with tiered compliance categorization (High ≥80%, Medium 50-79%, Low <50%) and contextual interpretation linking observed gaps to systemic barriers (limited Child Life access, space constraints, communication barriers).

**Interactive Dashboard Development:**  
Built the GitHub-hosted visualization to make audit findings accessible beyond the written report. The dashboard enables stakeholders to filter by element, compliance level, and patient demographics, supporting data-driven discussions about where to focus improvement efforts.

---

## The Clinical Challenge

Pediatric dental procedures can be distressing for children, especially those who are neurodivergent or have communication barriers. Evidence-based bundled care approaches (BCA) reduce procedural anxiety and improve patient experience, but implementation varies widely.

**The audit revealed:**
- Overall compliance: 52.4%
- Strong performance: Comfort positioning (avoiding restraints, using soft language)
- Critical gaps: Preparation measures (asking about questions, exploring coping strategies), Alternate Focus strategies (distraction techniques), acknowledging changes in patient state during procedures

**The stakes:** Without systematic measurement and targeted improvement, procedural care quality remains inconsistent, affecting patient outcomes and family satisfaction.

---

## Key Informatics Principles Applied

**Observational Data Translation:**  
Clinical behaviors aren't naturally quantifiable. The methodology translates abstract concepts like "family-centered care" into specific, observable indicators (e.g., "Did staff introduce themselves?", "Did providers acknowledge non-verbal cues of discomfort?"). This demonstrates the informatics principle that measurement frameworks must be both clinically meaningful and operationally feasible.

**Tiered Compliance Categorization:**  
Rather than treating all gaps equally, the framework stratifies compliance (High/Medium/Low) to prioritize where improvement efforts will have the greatest impact. This reflects resource-constrained reality in healthcare improvement work.

**Stakeholder-Centered Visualization:**  
The dashboard design acknowledges different stakeholders need different views of the same data. Administrators care about overall compliance trends. Clinical educators need element-level breakdowns. Quality improvement teams need to identify outliers. The filtering functionality serves all these use cases.

**Contextual Analysis:**  
Data without context doesn't drive change. The audit report explicitly links compliance patterns to systemic factors (limited Child Life support, space constraints, interpreter service gaps). This demonstrates understanding that quality improvement requires addressing root causes, not just training deficits.

---

## From Audit to Action

This project demonstrates the full cycle of health informatics work in quality improvement:

**1. Measurement Framework Development**  
Translated validated BCA elements into 23 behavior-based indicators suitable for direct observation.

**2. Baseline Data Collection**  
Coordinated research staff observations across 22 procedures, capturing demographic context (neurodivergent vs. neurotypical, verbal vs. non-verbal communication, age groups, procedure types).

**3. Analysis & Interpretation**  
Calculated element-level and indicator-level compliance, identified high-performers and critical gaps, contextualized findings with environmental and systemic barriers.

**4. Visualization for Dissemination**  
Built interactive dashboard enabling stakeholders to explore data dynamically rather than consuming static reports.

**5. Actionable Recommendations**  
Provided specific, evidence-based improvement strategies tied directly to observed gaps (e.g., "First point-of-contact providers should consistently introduce themselves alongside dentists, who already demonstrate strong adherence").

**The transfer to Phase 2:** This baseline dashboard will be mirrored with post-education data, enabling pre-post comparison to assess intervention effectiveness. The visualization framework I built is reusable for ongoing audit cycles.

---

## Technical Execution

**Built with:** HTML/CSS/JavaScript  
**Hosted on:** GitHub Pages  
**Design principle:** Filterable, interactive exploration over static reporting

The dashboard allows users to:
- Filter behavioral indicators by BCA element (Preparation, Communication, Comfort Positions, Alternate Focus, Medication)
- Filter by compliance level (High/Medium/Low)
- View demographic breakdowns (developmental status, communication method, age groups, procedure types)
- Identify specific strengths (100% compliance indicators) and critical gaps (<20% compliance)

This interactivity matters because quality improvement discussions benefit from being able to drill down into specific subgroups or elements in real time during team meetings.

---

## Reflections

**What I'd do differently:**  
If starting fresh, I'd add a "confidence interval" or "sample size" indicator for each compliance percentage. With only 22 observations, some metrics may not be statistically stable. Making uncertainty visible would strengthen the scientific rigor.

**What surprised me:**  
The variance across BCA elements was striking. Comfort positioning compliance was strong (providers avoided restraints, used soft language), but Preparation and Alternate Focus were inconsistent. This reinforced that quality improvement can't assume uniform implementation across related practices. Staff may excel at some aspects of family-centered care while struggling with others.

**What I'd emphasize in different contexts:**  
For other clinical settings, I'd adapt the dashboard to show compliance by individual provider or shift rather than just aggregate trends. This would enable peer comparison and targeted coaching without public shaming (show data privately to individuals, not on shared dashboards).

---

## Technical Notes

The visualization balances detail with accessibility. Healthcare providers don't need complex analytics tools. They need clear answers to: "Where are we doing well?" and "Where should we focus improvement efforts?" The dashboard answers both questions at a glance while allowing deeper exploration for those who want it.

---

*This project was completed as part of a quality improvement initiative in a pediatric dental clinic. Patient data has been de-identified to protect privacy.*
