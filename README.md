# Global-Compliance-Compensation-Equity-Culture-Analytics
Global people analytics project analyzing compensation equity, compliance risk, and cultural dimensions to assess engagement and turnover patterns using Tableau.

Global Compliance, Compensation Equity & Culture Analytics

A people analytics case study examining how compensation equity, compliance gaps, and cultural dimensions influence engagement and turnover across global workforces.

Project Overview

This project analyzes how compensation equity, compliance gaps, and national cultural dimensions shape employee engagement and turnover across international workforces. Using synthetic HRIS data anchored to verified global labor statistics and cultural indices, the analysis demonstrates how predictive analytics can help HR leaders identify equity risks early and design culturally informed workforce strategies.

The study compares workforce dynamics across Brazil, Germany, India, Japan, South Africa, Sweden, and the United States using Tableau-based visual analytics.

Business Problem

Global organizations often manage similar roles across countries but experience uneven engagement and turnover outcomes. These disparities are frequently attributed to compensation, compliance complexity, or culture, yet are rarely analyzed together.

This project addresses:

How pay equity and compliance gaps relate to engagement and turnover

How cultural dimensions influence employee reactions to inequity

How HR teams can use analytics to proactively identify risk

Data Sources & Methods
Data Design & Preparation

Synthetic HRIS data was generated using public benchmarks from the OECD, World Bank, ILO, and Eurostat, aligned by country to ensure realistic distributions while protecting privacy.

Missing values were handled using median imputation to reduce cross-country outlier bias.

Figure 1. Identification and treatment of missing values using median-based imputation.
![Missing Data Handling](Visuals/Missing_Data_Cultural_Dimensions.png)

Cultural Logic & Calculated Fields

Cultural dimensions were operationalized using Tableau calculated fields. Countries were categorized into Individualism tiers using conditional logic consistent with Python-style IF/ELSE structures.

Figure 2. Tableau calculated field used to categorize countries by Individualism level.
![Calculated Field Logic](Visuals/Calculated_Feild_Tablaeu_Cultural_Dimensions.png)

Visual Analysis
Global Turnover Overview (Anchor Visual)

Figure 3. Global turnover rates by country, visualized using a geographic map and comparative bar chart.
![Turnover by Country](Visuals/Turn_Over_By_Country_Cultural_Dimensions.png)
Engagement, Pay Ratio & Compliance Gaps

Figure 4. Relationship between engagement, pay ratio, and compliance gaps across countries.
![Compliance Gap Scatter Plot](Visuals/Complaince_Gap_Scatter_Plot_Cultural_Dimensions.png)
Cultural Dimensions & Engagement Correlation

Figure 5. Engagement correlation with Individualism and Power Distance, illustrating cultural moderation effects.
![Engagement Correlation](Visuals/Engagement_Correlation_Cultural_Dimensions.png)
Key Insights

Countries with lower pay ratios and larger compliance gaps tend to show lower engagement

Low Power Distance cultures experience sharper engagement declines when inequities arise

High Power Distance cultures exhibit more stable engagement despite wider pay disparities

Individualism shows a strong positive relationship with engagement

Cultural context significantly moderates the impact of compensation inequity

Business Impact

This analysis demonstrates how HR leaders can integrate compensation, compliance, and cultural context to:

Identify equity risks before they result in disengagement or turnover

Tailor global compensation strategies to local expectations

Support leadership decisions with transparent, data-driven insights

Strengthen trust and retention across international teams

Ethics & Data Privacy

All employee data used in this project is synthetic and based on publicly available labor statistics. No real employee data or proprietary organizational information is included.
