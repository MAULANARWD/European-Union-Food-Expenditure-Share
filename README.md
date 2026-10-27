# European-Union-Food-Expenditure-Share
Analysis of food expenditure share across European Countries.

## 📌 Project Overview
A classic economic theory states that lower-income households spend a higher proportion of their income on food. This project aims to prove this theory through EU context by analysing the average of food expenditure share based on employment status, the trends of food expenditure share over the decades, the cross-country comparisons of food expenditure share per worker type, and the disparity of food expenditure share among EU countries.

## 🛠️ Tools Used
*   **Python (Google Colaboratory):** Data cleansing and exploratory data analysis (EDA).
*   **Pandas & Matplotlib:** Data manipulation and static chart generation.
*   **Looker Studio:** Interactive dashboard creation.
*   **GitHub:** Version control and portfolio hosting.

## ⚙️ Data Cleansing
1.  **Integrating Data:** Collected five separate datasets of food expenditure share from Eurostat, and combined them into a single and unified long-format table to enable cross-status analysis.
2.  **Handling Missing Values:** Identified missing values represented as colons (:) and filtered them out during analysis to prevent them from being calculated as zero.
3.  **Removing Irrelevant Data:** Filtered out non-data rows, such as footnotes and observation flags, and removed EU aggregate rows to avoid double-counting during country-level analysis.
4.  **Standardising Data:** Converted the unit of measurement from per mille (‰) to percentages (%) for clearer interpretation.

## 📊 Key Insights
1.  **Validating Economic Theory:** Vulnerable groups, such as unemployed and retired people, spend a larger portion of their budget on food, leaving them with less disposable income for other necessities.
2.  **The 2005 Anomaly:** The sudden increase of share in 2005 was correlated with EU Enlargement in 2004, where new member states with high food shares joined the union.
3.  **Geographical Divide:** In 2020, Eastern and Southern European countries show drastically higher food expenditure share compared to Western and Northern Europe.
4.  **The Belgian Paradox:** A small gap does not mean a country has better welfare. Belgium became the country with the smallest gap because all of its employment groups allocated 14–14.5% on food.

## 🔗 Links
*   **Raw Data:** [Eurostat hbs_str_t221](https://ec.europa.eu/eurostat/databrowser/view/hbs_str_t221/default/table)
*   **Cleaned Dataset:** [Google Sheets](https://docs.google.com/spreadsheets/d/1CeDnlYCyS4F6he9F1pvRTUYANRsW1Spy/edit?usp=sharing&ouid=113664157326504328531&rtpof=true&sd=true)
*   **Dashboard:** [Looker Studio](https://datastudio.google.com/u/0/reporting/968215f5-ead4-48be-acdc-6386aadaa41f/page/d7gBG)
