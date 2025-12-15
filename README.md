# Plastic-Waste-Recycling-Efficiency-Analytics-2000-2023-Python-EDA
### A data-driven exploration of global plastic generation, recycling performance, and mismanaged plastic risk (country × region × city granularity).
Why relevant: Improper waste management is a global crisis.

### Dataset- plastic_waste_recycling_analytics.csv (≈7.2k rows)
### Tools: Python, pandas, matplotlib, seaborn, scikit-learn, plotly,Jupyter

# Abstract
This project performs exploratory data analysis on a global plastic waste dataset (2000–2023, country/region/city granularity) to uncover trends in plastic generation, recycling efficiency, and mismanaged plastic risk. Using time series, correlation analysis, clustering, and counterfactual policy simulations, the analysis quantifies where mismanaged plastic is concentrated, the relationships between GDP/coastal population and recycling, and the potential impact of targeted recycling improvements.

# Introduction
* Background on plastic pollution: global scale, ecological & marine impacts, link to coastal populations.

* Why recycling efficiency matters: reducing mismanaged plastic, circular economy.

* Dataset overview & project goals: analyze trends, identify hotspots, propose data-backed recommendations for improving recycling and reducing mismanaged plastic.
  
# Problem Statement
* Quantify trends in plastic waste generation (2000–2023) across countries, regions, and cities.

* Identify countries/regions/cities with low recycling efficiency and high mismanaged-plastic share.

* Understand drivers (GDP per capita, coastal population) behind mismanagement.

* Simulate policy interventions (e.g., increasing recycling rates) and estimate tonnes of mismanaged plastic avoided.
  
  # Data Description
* Source: plastic_waste_recycling_analytics.csv

* Rows: ~7,200 (country × year × region × city)

* Columns: Country, Year, Region, City, Plastic_Waste_Tonnes, Recycling_Rate_Pct, Mismanaged_Plastic_Pct, Coastal_Population, GDP_per_Capita

* Preprocessing notes: synthetic/realistic row generation; no missing values; some derived features recommended below.


   # Recommendations (policy + practical)
  ### High priority

* Scale municipal recycling infrastructure in coastal megacities (quantify estimated tonnes avoided).

* Implement deposit-return schemes and extended producer responsibility (EPR) in top mismanaged countries.

### Medium priority

* Public awareness campaigns targeted by region/city clusters found in clustering analysis.

* Incentives for circular packaging and investment in local mechanical recycling (countries with low GDP but high waste).

### Low priority / Long term

* Invest in advanced sorting & chemical recycling pilots in countries with high absolute waste; pair with economic incentives.

* Establish transnational data-sharing and monitoring for marine plastic leakage (use coastal population + mismanaged tonnage).

# Conclusion
* Global plastic waste has grown rapidly from 2000–2023, while recycling improvements have not kept pace.

* A small group of countries and coastal regions account for the majority of mismanaged plastic.

* Higher GDP helps improve recycling rates, but infrastructure quality and policy enforcement matter even more.

* Mismanaged plastic strongly correlates with low recycling efficiency, highlighting an urgent need for system upgrades.

* A 10-percentage-point improvement in recycling could prevent millions of tonnes of plastic leakage annually.

* Targeting high-waste countries and coastal cities offers the highest environmental impact.
