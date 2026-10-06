# Global-AI-Adoption-in-Education-A-Comprehensive-Global-Performance-Intelligence-Report
Skillwallet  project Om Kadam
Global AI Adoption in Education: A Comprehensive Global Analysis

Author: Om Kadam Program: Data Analytics with Tableau (Skill Wallet capstone, individual project) Tools: Tableau Public, GitHub, GitHub Pages

Live Links
Item	Link
Tableau Public dashboard and story	[https://public.tableau.com/views/GlobalAIAdoptioninEducationAComprehensiveGlobalPerformanceIntelligenceReport/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link]
Problem Statement

AI use in education is growing quickly across students, teachers and institutions, but it is not growing evenly. Adoption differs between countries and regions, between urban and rural areas, and between places with and without government AI policies. Without a clear picture of this, it is hard to decide where to invest, which tools to build for, or which policies work.

This project cleans and analyzes a global dataset on AI use in education and presents the results as an interactive Tableau dashboard and a data story that answers questions for three audiences.

Personas
Dr. Sarah Chen, Educational Technology Director. Needs to compare how regions adopt AI, see which policy frameworks work, and judge the effect of AI in the curriculum, so she can give evidence-based recommendations to school boards and education agencies.
Marcus Williams, EdTech Entrepreneur and Product Manager. Needs to see which AI tools are gaining traction, where usage is highest, and how it changes over time, so he can prioritize product development and market entry.
Professor Elena Rodriguez, AI in Education Researcher. Needs to understand how internet access, government policy and education level relate to adoption, so she can publish findings and advise on educational equity.
Dataset

File: Global AI in Education.csv

1,360 records
10 countries: Australia, Brazil, Canada, China, Germany, India, Nigeria, Pakistan, United Kingdom, United States
6 regions: Africa, Asia, Europe, North America, Oceania, South America
Monthly data (months 1 to 12) with a Year field
Field	Description
Country, Region	Location of the record
Month, Year	Time period
Ai In Curriculum	Whether AI is part of the curriculum (Yes / No)
Government Ai Policy	Policy status (Active / Draft / None)
Top Ai Tool	Most-used AI tool in that record
Schools Ai Adoption Pct	Percentage of schools using AI
Student Ai Usage Pct	Percentage of students using AI
Teacher Ai Usage Pct	Percentage of teachers using AI
Urban Ai Usage Pct / Rural Ai Usage Pct	AI usage in urban and rural areas
Gender Gap Ai Usage Pct	Gender gap in AI usage
Internet Penetration Pct	Share of the population with internet access
Education Index	Education development index for the country
Avg Daily Ai Usage Min	Average minutes of AI use per day
What Was Built

Dashboard with:

KPI cards: schools AI adoption, average daily AI usage, gender gap in usage and the urban-rural gap
Schools AI adoption by country, split by AI in curriculum and government policy
Average daily AI usage by region across the months
Urban vs rural AI usage by country
Government AI policy status by region (bubble chart)
Student vs teacher AI usage by region
A map of schools AI adoption by country
Filters and interactive actions across the sheets

Data story (5 story points):

[Title of story point 1]
Growth over time
Does policy matter?
Daily AI usage by region across the year
The rural AI gap: urban vs rural AI usage by country
Key Insights

Replace the placeholders with the final numbers from your charts before submitting.

Urban vs rural: Urban AI usage is higher than rural usage in every country, at roughly 33% vs 21% on average (a gap of about 12 points), and the gap is almost the same across countries. This points to an urban-rural divide itself and not to any single country.
Policy and curriculum: [Describe how adoption differs between countries with Active, Draft and no policy, and with or without AI in the curriculum, with numbers.]
Growth over time: [Adoption grew from X% in the first year to Y% in the latest year.]
Usage across the year: [Daily usage stays around X minutes with / without clear seasonal changes. Name the region with the highest and lowest usage.]
Tools: [Name the top AI tool and its share, and how close the other tools are.]
Recommendations
Invest in rural connectivity and access, since the urban-rural gap appears in every country.
Support AI-in-curriculum and clear policy frameworks, where the data shows higher adoption.
Focus product and training efforts on the leading AI tools and the regions with the lowest usage.
Performance and Testing
Data loaded as a Tableau extract for faster loading
Unused fields hidden and unused sheets removed
All filters and dashboard actions tested
Layout checked with Device Preview (desktop, tablet, phone)
Repository Contents
.
├── Global AI in Education.csv    # dataset
├── Global AI Adoption.twbx       # Tableau workbook
├── index.html                    # page with embedded Tableau Public dashboard
├── screenshots/                  # dashboard and story images
└── README.md
How to View
Open the live dashboard using the Tableau Public link above, or open the GitHub Pages site.
Use the filters and click on countries or regions to explore the data.
To open the workbook locally, download Global AI Adoption.twbx and open it in Tableau Public or Tableau Desktop.
Author

Om Kadam Artificial intelligence and Data Science Indira College of Engineering And Management SPPU 
