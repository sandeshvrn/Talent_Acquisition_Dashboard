Talent Acquisition_Dashboard:

1. Project Title / Headline:
Recruitment Performance: Analyze key hiring metrics, uncover skill gaps, and explore individual candidate profiles to drive smarter talent decisions.

2. Short Description / Purpose:
The Recruitment Analytics Platform is a dynamic decision-support tool designed to streamline and optimize the entire hiring process. It provides actionable insights into the talent pipeline, enabling data-driven decisions to identify and shortlist top candidates with greater speed and accuracy.

3. Tech Stack:
• 📊 Power BI Desktop – The primary tool used for data modeling, analysis, and creating all visuals and reports.
• 📂 Power Query – Data transformation and cleaning layer for reshaping and preparing the data.
• 🧠 DAX (Data Analysis Expressions) – Used for calculated measures, dynamic visuals, and conditional logic.
• 📝 Data Modeling – A star schema data model was implemented with relationships established among Candidates, Skills, and a bridge table Candidate_Skills to enable robust cross-filtering and accurate analysis.
• 📁 File Format – .pbix for development, .pbit (Power BI Template) for sharing the report structure without data, and .png for dashboard previews.

4. Data Source:
The data used for this project is a set of anonymized CSV files representing a fictional recruitment database. The primary tables include candidate profiles, their respective skills, and application details.

5. Features & Highlights:

A)Business Problem.
Hiring managers and HR teams often struggle with a disconnected view of the recruitment process. They lack a centralized tool to track applicant quality, monitor the effectiveness of different sourcing channels, and strategically identify which skills are abundant versus which are critically lacking in their talent pool.

B)Goal of the Dashboard.
To design and build a dynamic, user-friendly dashboard that centralizes recruitment data and provides actionable insights to streamline the hiring process, from initial application to final shortlisting.

C)Dashboard Walkthrough & Key Insights.
Page 1: Executive Overview.
This page provides a high-level summary of the entire recruitment landscape.
Key KPIs: At a glance, users can track Total Candidates, Overall Shortlisting Rate, Average ATS Score, Average Years of Experience, and the Percentage of Certified Candidates.
Most In-Demand Skills: A bar chart quickly identifies the skills most frequently listed in job requirements, helping to understand market trends.
Candidate Demographics: Visuals like "Candidates by Industry" and "Shortlisting Rate by Education Level" help segment the candidate pool and identify where the most qualified applicants are coming from.

Page 2: Skill Landscape Analysis.
This is the core analytical page, designed to perform a deep dive into skill gaps.
Candidate Funnel: A funnel chart visualizes the candidate journey from "Total Applicants" down to "High ATS Shortlisted," immediately showing the conversion rate at each stage.
Skill Gap Analysis (Quadrant Chart): This powerful visual plots skills based on their market demand vs. the available supply in the candidate pool, segmenting them into four zones:
Healthy Zone (High Demand, High Supply): Key skills that are readily available.
Priority Zone (High Demand, Low Supply): Critical skill gaps that require immediate sourcing attention.
Surplus Zone (Low Demand, High Supply): Skills that are easy to fill.
Low Priority (Low Demand, Low Supply): Niche skills that are not a current focus.
Candidate Segmentation: A decomposition tree allows users to perform root-cause analysis, breaking down the candidate count by industry and skill category to uncover hidden patterns.

Page 3: Candidate Profile Explore.
This page serves as a detailed, searchable database for granular analysis.
Drill-Down Capability: Users can navigate to this page to see a detailed, row-level view of every candidate and their associated skills, qualifications, and status.
Interactive Filtering: Slicers for Industry and Education Level allow recruiters to quickly narrow down the list to find candidates that match specific criteria.
Business Impact & Insights

This dashboard empowers the recruitment team to:
Prioritize Sourcing Efforts by focusing on skills identified in the "Priority Zone."
Improve Hiring Strategy by understanding which industries and education levels yield the highest quality candidates.
Increase Efficiency by using the funnel analysis to identify and address bottlenecks in the hiring process.
Facilitate Data-Driven Discussions with stakeholders by providing a clear, interactive, and up-to-date view of recruitment performance.

6. Screenshots:
<img width="1383" height="801" alt="image" src="https://github.com/user-attachments/assets/cacae544-0aab-439c-8408-d154d4199d42" />

<img width="1376" height="805" alt="Skills   Trends_Page 2_Image" src="https://github.com/user-attachments/assets/b2357244-7aff-429d-81b5-2619c77e9f07" />

<img width="1392" height="772" alt="Candidate Deep Dive_Page 3_Image" src="https://github.com/user-attachments/assets/9cad31db-5beb-40a2-b222-07f727ff6233" />


