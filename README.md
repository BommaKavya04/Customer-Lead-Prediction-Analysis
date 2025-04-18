# Customer-Lead-Prediction-Analysis
This helps to analyse the lead source , converted leads and recommendations

# Final Insights 

# Data Preparation

# ---> Excel & SQL Data Cleaning

1) Imported large CSV using LOAD DATA INFILE in SQL.

2) Ensured date formats (YYYY-MM-DD) and removed special number formats (%, ₹, accounting, etc.) for compatibility.

3) Removed commas from numeric values and ensured clean import.

4) Checked for and removed duplicates via Excel (Remove Duplicates).

5) Analyzed missing values using formula: =COUNTIF(range, "") / COUNTA(range).

6) Dropped columns with >50% missing data (e.g., Tags, Lead Quality, Asymmetrique Scores).

7) Treated remaining nulls using appropriate imputation (mean, median, mode).

8) Exported cleaned dataset for Power BI use.



# 📊 Power BI Processing

1) Reclassified Mumbai, Thane, and Other Cities of Maharashtra under India.

2)Created key measures: Total Leads, Converted Leads, and Conversion Ratio.

3) Used DAX formulas to transform and clean city/country fields.

4) Developed visuals on lead origin, source, conversion performance, specialization, and user behavior.

5) Built a dynamic final dashboard to present insights interactively.



# 📈 Final Insights from Dashboard

1) Lead Overview:

Total Leads: 9,240
Converted Leads: 3,561
Avg Page Views per Visit: 2.37
Avg Time Spent: 487.70 sec

2) Conversion Rate: 38.54%

3) Top Performing Lead Sources:
Google, Direct Traffic, Olark Chat, Organic Search

4) Cities with Most Leads:
Mumbai, Unknown, Thane & Outskirts

5) Top Countries:
India, Unknown, UAE

6) High Conversion Channels:
Lead Add Form: 92.48% conversion (SMS Sent activity, top specializations: Marketing & HRM)
Landing Page Submission: 36.19% conversion, top specs: Finance, HRM

7) Low Lead Channels:
Blog, Live Chat, NC_EDM, PPC Ads, Social Media (only 1–2 leads)

8) Least Performing Lead Origins:
Quick Add Form (1 lead, 100% conversion)
Lead Import (55 leads, 23.64% conversion)

9) Converted Lead Profile:
Avg Page Views: 2.33
Avg Time on Site: 738.55 sec
Top Occupations: Unemployed, Working Professionals
Popular Activities: SMS Sent, Email Opened
Top Specializations: Unknown, Finance, Marketing Management
Top Countries: India, Unknown, UAE


# Recommendations

1) Optimize Key Lead Sources

Top Sources: Google, Direct Traffic, Olark Chat, Organic Search.
Increase Google Ads budget with high-converting keyword focus.
Improve SEO for organic search: target specialization-specific queries.

2) Reduce “Unknown” in Data

Many leads have Unknown in Specialization, Occupation, City.
Make these fields mandatory or pre-filled in lead forms.
Apply default values or drop-downs to guide inputs.

3) Re-Engage Low-Converting Sources

Channels like Blog, Live Chat, PPC Ads have <2 leads.
Review these campaigns: are they targeted well?

4) High conversion activities: SMS Sent, Email Opened.

Set automated campaigns with SMS + email sequences post-form fill.
Personalize email/SMS based on city/country insights.

5) Specialization & Occupation-Based Personalization

Popular specializations: Marketing, Finance, HRM.
Personalize landing pages with course benefits for these fields.
Show student testimonials from these domains.

Occupation insights: Unemployed & Working Professionals dominate.

Promote career outcomes, job assistance, and upskilling benefits.

Offer EMIs or scholarships for unemployed leads.

# KPI CARDS USED FOR VARIOUS METRICS

![Image](https://github.com/user-attachments/assets/1994c633-dd92-4c1a-9304-b01ea8b4fb86)

#Time Trend Analysis of Lead Source vs Total Leads

![Image](https://github.com/user-attachments/assets/c1bb909a-679c-437f-8256-f28c95d09206)

# Lead Converted by City 

![Image](https://github.com/user-attachments/assets/c4f86086-7300-4c39-9172-5e553d38df50)

# Lead Conversion by Country, City vs Conversion Ratio

![Image](https://github.com/user-attachments/assets/9b936f7b-a354-4882-b4a6-b59005cc7f68)

# Table view of Country, City, Lead Origin and Source vs Total Leads 

![Image](https://github.com/user-attachments/assets/c11bc6a3-c02f-4aae-811d-c9f7695987e6)

# Donut Chart to understand occupations

![Image](https://github.com/user-attachments/assets/a346332c-b1ce-4830-94a8-084994f582b8)

# Pie Chart to understand Specialisation

![Image](https://github.com/user-attachments/assets/1c8416b1-680a-4c1f-9e9e-ab5ea91d9914)

# Bar graph to understand last notable activity

![Image](https://github.com/user-attachments/assets/2da4dd5f-509b-4f0c-a896-66dca5b571cc)

# Final Dashboard

![Image](https://github.com/user-attachments/assets/ec1878c6-ee88-4c28-bfdd-68966ae32d54)









