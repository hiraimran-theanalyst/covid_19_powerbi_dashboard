# covid_19_powerbi_dashboard
The repository contains an interactive Power BI dashboard analyzing the impact of COVID-19. It highlights key metrics such as confirmed cases, deaths, recoveries, mortality rate, regional comparison, population outbreak patterns and trend analysis. The project demonstrates skills in data cleaning, data modeling, visual design, and storytelling


📊 COVID-19 Global Analysis Dashboard – Power BI Project

An interactive dashboard analyzing the global spread and impact of COVID-19 using publicly available datasets. The project demonstrates expertise in Power BI, data modeling, visual storytelling, and business insights.

✅ Project Goals

Provide a clear global overview of COVID-19 situation

Identify high-risk regions with severe death outcomes

Understand active vs recovered case patterns

Discover trends over time using visual analytics

Build a professional Data Analyst portfolio project ✅

📁 Dataset Information
Attribute	Details
Source	Worldometer COVID-19 Data
Format	CSV (multiple files merged)
Rows	~200 countries
Updated	Static dataset for portfolio

Cleaning done using:
✔ Power Query (null removal, data typing, transformation)
✔ Calculated Measures using DAX

🧮 Key DAX Measures Used
Total Cases = SUM('COVID Data'[Total Cases])
Total Deaths = SUM('COVID Data'[Total Deaths])
Total Recovered = SUM('COVID Data'[Total Recovered])
Active Cases = [Total Cases] - [Total Recovered] - [Total Deaths]
Mortality Rate = DIVIDE([Total Deaths], [Total Cases], 0)

📌 Key Metrics (KPIs)

✅ Total Cases

✅ Total Deaths

✅ Active Cases

✅ Recovered Cases

✅ CFR % (Case Fatality Rate)

✅ Mortality Rate (%)

📍 Dashboard Pages & Insights

1️⃣ Key Indicators Page 

Provides an executive summary of the global COVID situation using KPI Cards including CFR %
📸 ![Key Indicators Page](https://github.com/hiraimran-theanalyst/covid_19_powerbi_dashboard/blob/d59160e0e60bd5c69b4763a835ba0d7ddaeb2773/Screenshot/Key%20Matrics%20Overview.JPG?raw=true)


2️⃣ Regional Comparison Page

Shows mortality, active cases, and testing correlations by country
📸 (https://github.com/hiraimran-theanalyst/covid_19_powerbi_dashboard/blob/d59160e0e60bd5c69b4763a835ba0d7ddaeb2773/Screenshot/Regional%20Comparison.JPG)

3️⃣ Trends Over Time Page

Analyzes how cases & deaths evolved during the pandemic history
📸 (https://github.com/hiraimran-theanalyst/covid_19_powerbi_dashboard/blob/d59160e0e60bd5c69b4763a835ba0d7ddaeb2773/Screenshot/Trend%20Over%20Time.JPG)

⚙️ Project Architecture
CSV Data → Power Query → DAX Measures → Report Design → Dashboard Deployment

✅ Outcome / What I Learned

✔ Real-world data cleaning & transformation
✔ Designing professional BI dashboards
✔ Using DAX for custom calculations
✔ Sharing data insights clearly
✔ Confidence for Data Analyst interviews ✅

🚀 Future Enhancements

Add real-time automated data refresh

Deploy to Power BI Service

Add additional drill-down navigation

Include vaccination data comparisons

📂 Files in This Repository
File Name	Description
COVID_Dashboard.pbix	Power BI Dashboard
README.md	Documentation
/images/	Dashboard Screenshots
👩‍💻 Author

Hira Imran
Aspiring Data Analyst | Power BI Developer
📍 Pakistan

📫 Contact: (imranhira26@gmail.com)
🔗 LinkedIn: (www.LinkedIn.com/in/ms-hira-imran)

⭐ Support

If you like this project, consider giving it a ⭐ on GitHub!
