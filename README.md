📘 Project: Chernobyl Radiation Data Analysis
1. Overview
This project analyzes radiation measurements (I-131, Cs-134, Cs-137) collected across Europe following the Chernobyl disaster in April 1986. The dataset contains 2051 records across 24 countries, with location, date, and isotope concentration details.

2. Dataset
Source: Chernobyl Chemical Radiation dataset

Shape: 2051 rows × 9 columns

Key Columns:

PAYS – Country code

Location – Measurement site

Longitude, Latitude – Geographic coordinates

Date – Measurement date

I_131_(Bq/m3), Cs_134_(Bq/m3), Cs_137_(Bq/m3) – Isotope concentrations

3. Data Cleaning
Converted isotope columns to numeric values.

Handled missing values using mode imputation.

Verified dataset integrity (df.info(), df.describe()).

4. Exploratory Data Analysis (EDA)
Temporal Trends:

Sharp spikes in I-131 immediately after the accident, followed by rapid decline.

Cs-134 and Cs-137 persisted longer, with Cs-137 being the most critical long-term pollutant.

Geographic Spread:

Scatter plots show contamination spread across Europe.

Higher levels recorded closer to the accident site.

Country-Level Analysis:

Boxplots reveal variation in isotope concentrations across countries.

Outliers highlight localized contamination events.

Correlation Analysis:

Strong correlation between Cs-134 and Cs-137, reflecting similar dispersion patterns.

5. Visualizations
Line plots of isotope levels over time.

Scatter plots showing geographic distribution.

Boxplots comparing isotope levels across countries.

Heatmap of correlations between isotopes.

6. Key Insights
I-131: Short-lived but highly concentrated immediately after the accident.

Cs-134 & Cs-137: Longer persistence, with Cs-137 being the most concerning pollutant.

Geographic impact: Widespread contamination across Europe, with hotspots near the accident site.

Data quality: Missing values handled effectively; strong patterns observed despite gaps.

7. Tools & Libraries
Python: pandas, numpy, matplotlib, seaborn

Profiling: ydata_profiling for automated EDA report

8. Output
Interactive EDA_report.html generated for detailed profiling.

Visualizations highlight contamination trends, geographic spread, and isotope correlations.
