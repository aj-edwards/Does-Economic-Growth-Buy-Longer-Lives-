# GDP and Life Expectancy Exploratory Data Analysis (EDA)

An exploratory data analysis examining the relationship between economic output (GDP) and human longevity (life expectancy) across six nations between 2000 and 2015 using Python, Pandas, Matplotlib, and Seaborn.

## 📝 Read the Article
For a narrative-driven, storytelling breakdown of these findings, check out the full blog post on Medium:
👉 [Does Economic Growth Buy Longer Lives? A 15-Year Look at GDP and Life Expectancy Across Six Nations](https://medium.com/@edwards.anna.j/does-economic-growth-buy-longer-lives-a-15-year-look-at-gdp-and-life-expectancy-across-six-nations-eefab7939113?postPublishedType=initial)

---

## Project Overview
This project investigates the historical relationship between national wealth and public health outcomes using World Bank and World Health Organization (WHO) datasets. The analysis spans six diverse countries: **Chile, China, Germany, Mexico, the United States, and Zimbabwe**.

### Key Research Questions Addressed:
* Has life expectancy increased over time across the six nations?
* Has GDP increased over time across the six nations?
* Is there a correlation between a country's GDP and its life expectancy?
* What are the underlying distributions and averages of global life expectancy?

---

## Key Findings
* **Bimodal Distribution:** Global life expectancy records reveal a bimodal split rather than a normal distribution, driven by high-income clustering (75–81 years) and historical lower-income outlier tails.
* **Diminishing Returns:** While economic growth heavily impacts developing regions by funding critical health infrastructure, wealthier nations experience diminishing marginal returns where additional wealth yields smaller gains in longevity.
* **Country-Specific Turnarounds:** Longitudinal tracking highlights dramatic recoveries, most notably Zimbabwe's sharp rebound past age 60 following mid-2000s health and economic disruptions.

---

## Repository Structure
* `all_data.csv`: The underlying World Bank and WHO dataset used for analysis.
* `life_expectancy_gdp 11_13.ipynb`: The complete technical Jupyter notebook containing data cleaning, statistical analysis, and generated visualizations.
* Exported Visualizations: High-resolution PNG exports used to support the research.

---

## Technologies Used
* **Python 3**
* **Pandas** for data manipulation and aggregation
* **Matplotlib & Seaborn** for data visualization and multi-panel FacetGrids
