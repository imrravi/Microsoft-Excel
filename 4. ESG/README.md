## Carbon Crunch
![dataset-cover](https://github.com/user-attachments/assets/89252c01-310d-464d-8c84-3f11b06ae712)

You are an ESG analyst tasked with evaluating a manufacturing company's environmental performance over multiple reporting periods. Using the provided dataset-covering emissions, operational data, supplier details, and regulatory benchmarks-your goal is to clean, analyze, and interpret the data. You will then use your findings to propose a comprehensive sustainability strategy to help the company meet its Net Zero goal by 2050, while integrating Life Cycle Assessment (LCA) best practices.

**Link to Excel Sheet - [Dataset](https://docs.google.com/spreadsheets/d/1a8qcWA0u_1d8shB5PQhgMoO1_yhFG0krnj96ZByRy58/edit?gid=1760822406#gid=1760822406)**

**Dataset Details:**

**Sheet 1: Emission Data**
- Contains quarterly GHG emissions (CO2, CH4, N2O) for 10 facilities over two years (2022-2023) across multiple scopes.

**Sheet 2: Operational Data**
- Provides facility-level data on production volume, energy consumption, and waste, matched by reporting period.

**Sheet 3: Supplier Data**
- Lists key suppliers with estimated carbon footprints, primary product categories and financial involvement with each company.

**Sheet 4: Regulatory Benchmarks**
- Outlines the company's GHG reduction target, Net Zero milestone, emission reporting standard, renewable energy usage, and LCA integration goals.

**Task Instructions:**

**Part 1: Data Preparation & Analysis (Excel)**

**1. Data Cleaning & Validation:**
- Import each table into separate Excel sheets.
- Check for and resolve any data inconsistencies (e.g., mismatched
facility IDs, duplicate entries, or missing values).

**2. Data Aggregation & Visualization:**
- **Pivot Tables:** Create pivot tables to summarize emissions by facility, reporting period, and emission scope. Extend your analysis to compare trends across the two years.
- **Charts & Graphs:** Build visualizations (e.g., line charts for quarterly trends, bar charts for facility comparisons) to highlight emission trends and operational performance.
- **Advanced Functions:** Use VLOOKUP/INDEX-MATCH to merge data between sheets (e.g., linking operational data with emissions) and employ conditional formatting to flag any outliers or unusual data points.

**3. Dashboard Development:**
- Develop a concise dashboard that presents key metrics (total emissions, production efficiency, energy consumption trends) alongside visual charts.
- Ensure the dashboard is clear and interpretable by non-technical stakeholders.

**Part 2: Strategic Reasoning & Recommendations**

**1. Identifying Key Challenges:**
- Based on your data analysis, identify and explain three critical challenges the company faces in achieving its Net Zero target by 2050. Consider challenges such as:
High emissions in specific facilities or quarters.
- Operational inefficiencies leading to increased energy use.
- Supplier sustainability risks affecting overall performance.

**2. Research & Best Practices:**
- Conduct brief research (using reputable sources) to identify industry best practices in GHG reduction, renewable energy integration, and LCA.
- Summarize how these practices can be adapted to address the challenges you identified.

**3. Strategic Recommendations:**
Propose actionable strategies to overcome the challenges. Your recommendations should be data-driven and may include:
- Process optimizations or operational changes.
- Investment in renewable energy or energy efficiency improvements.
- Enhanced supplier engagement and stricter sustainability criteria.
- Steps to fully integrate LCA into product development and operational assessments.
Support your recommendations with key findings from your Excel analysis and external research.

**Deliverables:**

- **Excel Workbook:**
Containing:
- Cleaned and organized data across separate sheets.
- Pivot tables, advanced formulas, and visualizations.
- A user-friendly dashboard summarizing the key metrics.

**Written Report (1-2 pages):**
Summarize:
- Your approach to data cleaning and analysis.
- Key findings from the dataset.
- The three challenges identified and their potential impact.
- Your research insights and detailed strategic recommendations.

---
### Report

**1. Approach to Data Cleaning and Analysis**
**Data Cleaning:**
- Changed Data format.
- Removed duplicates.
- Parsed the Income Distribution (%) field into separate columns for analysis.
- Handled missing values where applicable.
**Data Analysis:**
- Merged Emission, Operational and Supplier data using INDEX-MATCH for efficiency analysis.
- Calculated emissions and applied IQR for outlier detection but there is no anomalies in the dataset.
- Created pivot tables to summarize emissions by facility, reporting period, and scope.
- Built visualizations (line charts, bar charts) to explore emission trends, facility comparisons, and energy consumption patterns.

<img width="449" height="253" alt="image" src="https://github.com/user-attachments/assets/ed42a234-ac2d-457e-a07a-d91861523548" />

<img width="950" height="281" alt="image" src="https://github.com/user-attachments/assets/82182899-0bca-406d-9c17-ec9acbf62ec7" />

<img width="399" height="169" alt="image" src="https://github.com/user-attachments/assets/2fa58844-c480-44f6-9fa2-5ecec3d57f5d" />

---
## Dashboard																				
<img width="2497" height="953" alt="image" src="https://github.com/user-attachments/assets/028ae93d-d26c-46a8-9960-02922b49a855" />

---

**1. Key Challenges**

Based on the data analysis, three major challenges prevent the company from achieving its Net-Zero 2050 goal:

- **High Facility Emissions**
Total emissions were slightly lower in 2023 compared to 2022 for some facilities.Adani Green consistently recorded the highest annual emissions, followed by Tata Steel.

- **Operational Inefficiencies**

<img width="1018" height="169" alt="image" src="https://github.com/user-attachments/assets/aaf7dd9b-dd83-40fe-bafd-6aebb9eb8b28" />


Analysis of production and energy data shows that some facilities, like L&T and JSW Energy, use more energy per unit of production compared to others. For example, L&T has the lowest production but the highest energy per unit, while Adani Green achieves the best energy efficiency with the lowest energy per unit. This indicates that certain facilities have less efficient processes that need improvement.

- **Supplier Sustainability Risks**

<img width="741" height="436" alt="image" src="https://github.com/user-attachments/assets/1de69342-ca41-4e00-b3be-b0aafc4b762a" />

<img width="752" height="452" alt="image" src="https://github.com/user-attachments/assets/098bf34b-4f4d-446d-8c52-920f1da08d2e" />

The data shows that Scope 3 emissions (1,766,860 tons CO2e) from suppliers are the largest share of total emissions, even higher than Scope 1 or Scope 2. Among suppliers, Tata Steel and Adani Green have the highest carbon footprints (over 250,000 tons each). This indicates that supplier-related emissions are a major challenge and need stronger engagement and data transparency to reduce overall carbon impact.


Source: Emissions - [wikipedia](https://en.wikipedia.org/wiki/Carbon_footprint)
- Scope 1 = Direct emissions from our facilities (like fuel burning).
- Scope 2 = Indirect emissions from purchased electricity.
- Scope 3 = All other indirect emissions in the value chain (suppliers, logistics, product use, etc.).

**2. Research & Best Practices**
Industry research suggests three proven approaches for emission reduction and sustainability improvement:
- **Energy Efficiency & Digital Controls:** Implementing real-time energy monitoring, predictive maintenance, and process optimization can cut energy use by 10–20%.
- **Renewable Energy Adoption:** On-site solar, Power Purchase Agreements (PPAs), and renewable energy credits (RECs) help transition to clean electricity quickly.
- **Supplier Collaboration & Scope 3 Reporting:** Leading companies like Tata Steel, Adani Group etc.  have started requiring suppliers to disclose emissions data and align with science-based targets through initiatives such as the Science Based Targets initiative and CDP Supply Chain program. This approach helps reduce Scope 3 emissions and ensures transparency across the value chain.

**3. Strategic Recommendations**
A. Process Optimization & Operational Efficiency
- Conduct energy audits at top 3 emitting sites.
- Install real-time energy dashboards to track energy intensity per production unit.
- Upgrade equipment (e.g., boilers, motors, lighting) to energy-efficient models.
- Implement predictive maintenance to avoid energy losses and downtime.

B. Renewable Energy & Energy Improvements
- Target 50% renewable energy by 2030 through on-site solar and PPAs.
- Electrify process heat and replace fossil fuels where feasible.
- Set up energy storage systems to balance renewable supply and demand.
- Monitor Scope 2 emissions quarterly to ensure steady progress.

C. Supplier Engagement & Sustainability Standards
- Create a supplier sustainability code requiring emissions data from top suppliers.
- Provide training and tools to suppliers for carbon reporting and reduction projects.
- Prioritize suppliers with Science-Based Targets and renewable energy commitments.
- Include carbon performance criteria in procurement decisions.

4. Life Cycle Assessment (LCA) 
- To fully integrate LCA into product development and operations:
- Define Goal & Scope: Decide product boundaries and impacts to measure (e.g., raw materials, manufacturing, transport).
- Collect Data: Use primary data from facilities; fill gaps with secondary databases.
- Impact Assessment: Calculate carbon, energy, and resource impacts for each life cycle stage.
- Hotspot Analysis: Identify materials, processes, or suppliers with the biggest emissions.
- Design Improvements: Redesign products to use lower-impact materials or processes.
- Decision Integration: Link LCA results to procurement, R&D, and sustainability reporting.
- Continuous Updates: Re-run LCAs as product designs or supplier data improve.

**5. Net-Zero Roadmap (2025–2050)**
Near-Term (2025–2030)
- 25–30% emission cut
- Energy audits & efficiency upgrades
- 50% renewable energy target
- Supplier data pilot program

**Mid-Term (2030–2040)**
- 60–70% emission cut
- Full process electrification where possible
- Supplier science-based targets adoption
- Digital energy management scaling

**Long-Term (2040–2050)**
- 90–100% emission cut
- Carbon capture for residual emissions
- 100% renewable energy across operations
- Full supplier alignment on Net-Zero goals

**6. KPIs to Track Progress**
- Emissions per unit production (tCO₂e/ton output)
- % renewable energy used per facility
- Supplier emissions coverage (% suppliers reporting GHGs)
- Scope 1, 2, 3 emissions reduction vs baseline year

---
- For the complete measure, with data preprocessing and all previous steps, download the file I have [provided](https://github.com/imrravi/Microsoft-Excel/blob/main/4.%20ESG/ESG%20Analytics.xlsx).
