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

