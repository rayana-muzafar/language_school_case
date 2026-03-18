<h1>Operations Analysis for a Language School</h1>

<h2>Business case</h2>
<p>The company consists of 4 branches in Kyrgyzstan, 2 branches in the capital city and two more in regions. They faced a problem with students retention: for a language level A2 there are 47 groups and for a level C1 - only 5 groups. The head of the company wants to underastand the efficiency of branches, sales-managers and teachers. Key questions are:</p>
<ol>
  <li>Why are some branches growing while others lagging?</li>
  <li>Who fails to adhere to the plan?</li>
  <li>Where do we lose students?</li>
  <li>Which KPIs should be implemented?</li>
</ol>

<h2>Scope of the projects</h2>
<p>There are five worksheets available for an analysis:</p>
<ul>
  <li>branches (Branch_ID, Branch_Name, Plan_Revenue_Month, Plan_New_Students)</li>
  <li>managers (Manager_ID, Branch_ID, Name, Plan_Sales)</li>
  <li>leads from CRM (Lead_ID, Branch_ID, Manager_ID, Status, Course_Level, Payment_Amount, Month)</li>
  <li>students retention (Student_ID, Branch_ID, Start_Month, Still_Studying, Months_Studied)</li>
  <li>teachers (Teacher_ID, Branch_ID, Groups, Avg_Student_Score, Retention_Rate)</li>
</ul>

<h2>Calculations and Formulas</h2>

<h3>Sales Performance Analysis:</h3>
<ol>
  <li>Number of leads per manager:</li>
  <img width="605" height="37" alt="Leads per manager" src="https://github.com/user-attachments/assets/562052db-e304-4f0a-b6e6-f52d81d982e0" />

  <li>Number of paid leads:</li>
  <img width="600" height="38" alt="paid leads" src="https://github.com/user-attachments/assets/0f7e10a1-1fbf-4a86-938d-dc4e91e754b4" />

  <li>Conversion:</li>
  <img width="605" height="39" alt="Conversion" src="https://github.com/user-attachments/assets/e0dde112-23fe-43ed-b31e-d502af357f22" />

  <li>Revenue per manager:</li>
  <img width="607" height="38" alt="Revenue" src="https://github.com/user-attachments/assets/959650c2-f025-4cb9-9464-647fea6ca9a8" />

  <li>Plan execution:</li>
  <img width="607" height="35" alt="Plan execution" src="https://github.com/user-attachments/assets/5e80dca7-11fd-418e-b12c-99cc18b1111e" />

  <li>Average bill:</li>
  <img width="607" height="35" alt="Avg bill" src="https://github.com/user-attachments/assets/b93ab46e-9d43-4375-89cb-43281390504c" />

</ol>

<p><b>The Result:</b></p>
<img width="872" height="113" alt="man_tbl" src="https://github.com/user-attachments/assets/35e9cea1-2c2d-4c51-b53d-021c3d4df2f1" />

<h3>Branch Performance Analysis</h3>
<ol>
  <li>Branch revenue:</li>
  <img width="602" height="35" alt="B_revenue" src="https://github.com/user-attachments/assets/e49e1870-e302-4bdd-975a-642444bcf325" />

  <li>New students:</li>
  <img width="603" height="35" alt="B_new_st" src="https://github.com/user-attachments/assets/0de788ae-2134-4475-9417-5bf905737896" />

  <li>Revenue plan execution:</li>
  <img width="604" height="37" alt="B_rev_pl_ex" src="https://github.com/user-attachments/assets/c63b26b3-3ef0-4576-9f26-b8b9173ff48e" />

  <li>New students plan execution:</li>
  <img width="601" height="37" alt="B_new_st_pl_ex" src="https://github.com/user-attachments/assets/c7a3a46f-60ab-4174-91ad-0225baf611cc" />

  <li>Average check:</li>
  <img width="602" height="36" alt="B_avg_check" src="https://github.com/user-attachments/assets/7d156f81-1045-4a8c-a841-e7572f86a136" />

  <li>Retention by branch:</li>
  <img width="1007" height="36" alt="B_retention" src="https://github.com/user-attachments/assets/e8d590ac-b63d-4a6a-910a-5d855b0516f4" />

</ol>

<p><b>The Result:</b></p>
<img width="1295" height="103" alt="Branch_tbl" src="https://github.com/user-attachments/assets/059c1e91-0dca-4894-b103-3e41c946638e" />

<h3>Teachers' KPIs Analysis</h3>
<p>For KPI calculations was used weighted model with formula: <i>Score = w1X1 + w2X2 + w3X3</i>, where "X" stands for an indicator, "w" stands for a weight and the sum of weights equals 100%.</p>
<img width="604" height="32" alt="Teachers_KPI" src="https://github.com/user-attachments/assets/7b10eb58-21a9-4f95-b197-b50a6360ed01" />


<p><b>The Result:</b></p>
<img width="624" height="185" alt="Teachers_tbl" src="https://github.com/user-attachments/assets/d5b9c256-51af-4024-810e-fe7ff5579e59" />

Overall Students Retention Rate is 77%, accordingly to the following calculation:
<img width="601" height="37" alt="Overall students retention formula" src="https://github.com/user-attachments/assets/ae73223c-c73f-49f9-be9f-eb4f6f7409c6" />

<h2>Creating Pivot Tables and the Final Dashboard</h2>
<img width="835" height="254" alt="Pivot Tables" src="https://github.com/user-attachments/assets/35838c10-3d2d-41e6-91ab-c34f5f1367ac" />

<img width="845" height="388" alt="Final Dashboard" src="https://github.com/user-attachments/assets/24c9c181-1ccb-4e2b-82af-02408ced7400" />

<h2>Data Analysis Results & Recommendations</h2>

<h3>Overview</h3>
<b>Branches:</b>
Jalal-Abad shows the highest KPI fulfillment, while the Bishkek Central branch is currently underperforming.

<b>Courses:</b>
The primary revenue drivers are Beginner, Elementary, and Pre-Intermediate levels. Revenue from advanced courses remains relatively low; a detailed customer retention analysis is recommended for these segments.

<b>Sales Performance:</b>
Top performers by sales-to-target ratio are Ruslan (156%), Alina (123%), and Diana (95%).
Action Plan: Analyze the performance of Timur (77%) and Aizada (39%) to identify bottlenecks. Implement targeted training programs and develop an incentive scheme for high-performing managers.

<b>Conversion:</b>
The highest conversion rates were achieved by Timur (53%) and Alina (43%), while Aizada (33%) and Diana (35%) showed the lowest results.

<h3>Branch Performance Analysis</h3>

<b>Revenue & Student Acquisition:</b>
Bishkek Central is underperforming across key metrics, achieving only 39% of the revenue target and 35% of the new student acquisition goal.
Jalal-Abad leads the performance ranking, reaching 69% of its revenue target and 54% in student acquisition.

<b>KPI Discrepancy Insight:</b>
A significant gap exists between individual and branch-wide performance: while sales managers achieve an average of 98% of their individual targets, overall branch revenue and acquisition goals remain largely unmet.
Hypothesis: This suggests a potential misalignment between sales team KPIs and branch-level strategic objectives, requiring a review of the current quota-setting methodology.

<b>Market Context:</b>
Regional branches consistently outperform the capital. This trend may indicate market saturation and high competition in Bishkek, or suggests that the targets set for the capital offices are overly aggressive.

<h3>Key Insights & Recommendations: Branch Performance</h3>

<b>Core Facts:</b>
<ul>
  <li>Central Branch (B1): Critical target underperformance, reaching only 39% of revenue goals and 35% of new student acquisition targets</li>
  <li>Jalal-Abad: Leads in relative operational efficiency with 69% revenue target fulfillment.</li>
</ul>
<b>Key Findings:</b>
<ul>
  <li>KPI Imbalance: Current branch-level KPIs appear misaligned with actual market conditions.</li>
  <li>Market Dynamics: The capital shows declining efficiency despite high market capacity, indicating potential saturation or positioning issues.</li>
</ul>
<b>Strategic Recommendations:</b>
<ul>
  <li>Target Calibration: Re-evaluate and adjust performance targets for the Central Branch (B1), as current expectations may be overly ambitious.</li>
  <li>Market Analysis: Conduct a comprehensive competitor and positioning audit specifically for the Bishkek market.</li>
  <li>Budget Reallocation: Optimize marketing spend by reallocating resources to support and revitalize the Central Branch's performance.</li>
</ul>

<h3>Courses & Revenue Analysis</h3>

<b>Top Revenue Drivers:</b>
Beginner, Elementary, and Pre-Intermediate levels generate the highest revenue. This indicates high conversion rates and strong initial interest from new language learners (entry-level segment).

<b>Segment Performance Gap:</b>
Revenue from Intermediate, Upper-Intermediate, and Advanced (3%) levels is significantly lower compared to lower levels.
Hypothesis: This suggests either low customer retention (churn after the first modules) or marketing strategies that are exclusively optimized for beginners, neglecting the advanced segment.

<b>Strategic Recommendations:</b>
Retention Focus: Conduct a deep dive into the Retention Rate and refine the customer journey to encourage progression to higher levels.
Advanced Segment Growth: Revamp marketing strategies to target high-level learners.
Consumer Insights: Perform targeted market research to identify the unique motivations and pain points of the advanced student segment to improve group enrollment.

<h3>Key Insights & Recommendations: Courses</h3>

<b>Core Facts:</b>
<ul>
  <li>Revenue Concentration: Over 70% of total revenue is generated by Beginner–Pre-Intermediate levels.</li>
  <li>Advanced Segment Gap: The Advanced level accounts for only ~3% of the portfolio.</li>
</ul>
<b>Key Findings:</b>
<ul>
  <li>Acquisition Bias: The current business model is heavily skewed towards initial lead acquisition (new learners).</li>
  <li>Strategic Gap: There is a lack of a structured marketing and sales framework for the High-Level segment.</li>
</ul>
<b>Strategic Recommendations:</b>
<ul>
  <li>Advanced Segment Audit: Launch a comprehensive market research project to identify the specific needs and motivations of Advanced-level students.</li>
  <li>Upsell Strategy: Develop and implement a robust Upsell framework to increase the lifetime value (LTV) of current students.</li>
  <li>Retention KPI: Introduce Student Progression KPIs to measure and incentivize the transition of learners to higher levels.</li>
</ul>

<h3>Sales Performance & Conversion Analysis</h3>

<b>Top Performers & Goal Setting:</b>
Ruslan and Alina demonstrate the highest target achievement. However, their current sales quotas are set lower than those of their peers.
Recommendation: Consider increasing their performance targets (KPIs) to align with their potential, while implementing a formal recognition and incentive program for their outstanding results.

<b>Underperformance & Bottleneck Identification:</b>
Aizada and Timur show the lowest sales-to-target ratios.
Aizada: It is recommended to recalibrate her KPI thresholds, conduct a performance audit, and provide targeted sales training to improve her core metrics.
Timur: Despite missing sales targets, Timur achieved the highest conversion rate (53%). This paradox suggests high professional competence but a potential shortage of qualified leads.
Action Plan: Audit the volume and quality of leads assigned to Timur; consider increasing his lead flow to leverage his high closing efficiency.

<b>Conversion Optimization:</b>
Strategic Training: Conduct a deep-dive analysis of the sales processes for Aizada, Diana, and Ruslan. Implement a specialized training program focused on improving conversion techniques across these specific portfolios.


<h3>Key Insights & Recommendations: Sales Efficiency</h3>

<b>Core Facts:</b>
<ul>
  <li>KPI Disconnect: Managers achieve an average of 98% of their individual targets, yet branch-level goals remain unmet.</li>
  <li>High Efficiency/Low Volume: Timur shows a high conversion rate (53%) but only 77% target achievement.</li>
  <li>Critical Underperformance: Aizada demonstrates both low conversion (33%) and low target fulfillment (39%).</li>
</ul>
<b>Key Findings:</b>
<ul>
  <li>Inconsistent Goal Setting: Individual sales KPIs are not synchronized with branch-level strategic objectives.</li>
  <li>Lead Distribution Bias: Data suggests an uneven distribution of leads across the sales team.</li>
  <li>Underutilized Potential: Current quotas are established without considering individual historical performance and potential.</li>
</ul>
<b>Strategic Recommendations:</b>
<ul>
  <li>Implement Weighted KPIs: Transition to a more sophisticated model including Conversion Rate + Revenue + Lead Volume to ensure a balanced performance evaluation.</li>
  <li>Lead Distribution Audit: Conduct a technical audit of the CRM lead-routing logic to ensure equity and maximize ROI.</li>
  <li>Quota Optimization: Increase targets for high-performers (Ruslan and Alina) to match their actual capacity.</li>
  <li>Performance Recovery: Provide specialized sales training for Aizada to address conversion bottlenecks.</li>
</ul>

<h3>Teachers Performance & Student Retention</h3>

<b>Retention Benchmarking:</b>
The company-wide average Retention Rate (RR) stands at 77%, with significant variance among individual instructors, ranging from 67% to 92%

<b>Top vs. Bottom Performance:</b>
Top Performer (T2): Achieved the highest KPI score (73.8) while maintaining a maximum workload of 9 groups. T2 demonstrates an exceptional 92% Retention Rate alongside high student satisfaction scores.
Underperformer (T8): Despite a full workload (9 groups), T8 shows the lowest Retention (67%) and KPI (61.0), indicating a critical student churn issue.

<b>Teaching Style & Student Perception:</b>
Instructor T5: High Retention (88%) but low student satisfaction scores (78). This suggests a perceived lack of academic rigor or an overly lenient teaching style.
Instructor T4: High satisfaction scores (94%) but lower Retention (73%). This indicates a high-pressure environment or excessive strictness, leading to student attrition despite the perceived quality.

<b>Branch-Level Insights:</b>
Branch B1: Displays high educational inconsistency, housing both the strongest (T2) and one of the lowest-rated (T5) instructors.
Branch B2: Shows a systemic retention failure specifically in high-capacity groups (linked to T8’s performance), requiring urgent managerial intervention.

<h3>Key Insights & Recommendations: Teacher Performance</h3>

<b>Core Facts:</b>
<ul>
  <li>Retention Benchmark: The average Retention Rate (RR) is 77%, with a significant variance between 67% and 92% across the faculty.</li>
  <li>Performance Extremes: Instructor T2 leads across all key metrics, while Instructor T8 shows critically low retention despite a high workload.</li>
</ul>
<b>Key Findings:</b>
<ul>
  <li>Quality Inconsistency: Significant disparity in teaching standards across branches, creating a fragmented student experience.</li>
  <li>Financial Risk: Underperforming instructors (high churn/attrition) represent a direct threat to recurring revenue.</li>
  <li>Workload Impact: Data suggests a correlation between workload distribution and the ability to maintain high retention standards.</li>
</ul>

<b>Strategic Recommendations:</b>
<ul>
  <li>Instructor Rating System: Implement a transparent, data-driven Faculty Performance Index to standardize quality.</li>
  <li>Load Balancing: Immediately redistribute groups from Instructor T8 to prevent further student churn.</li>
  <li>Methodological Audit: Conduct a comprehensive pedagogical review to align teaching styles with student expectations.</li>
  <li>Instructional Balance: Develop guidelines to balance academic rigor and student engagement (addressing the "strictness vs. leniency" gap).</li>
</ul>
