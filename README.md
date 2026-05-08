# Share of the population using the Internet

**Goal:**

This project examines how internet access has evolved globally from 2000 to 2025, with a focus on the gap between income groups and world regions — and whether that gap is closing. I chose 2000 as it the point where data becomes more reliable as prior to 2000, data coverage of low-income countries is quite sparse.

---

## Data Source

- [Our World in Data – Share of the population using the Internet](https://ourworldindata.org/grapher/share-of-individuals-using-the-internet?country=WB_SA~WB_NA~WB_SSA~WB_EAP)

---

## Objectives

- How has global internet adoption evolved between 2000 and 2025?
- What are the internet adoption differences between socioeconomic groups?
- What are the internet adoption differences between regions?
- Is the adoption gap narrowing between regions and socioeconomic groups?
- What was the state of global internet adoption in 2025?

---

## Project Structure

| Folder | Contents |
| --- | --- |
| `data/raw/` | Original dataset from Our World in Data | No mising or mismatched values, hence no data cleaning required
| `notebooks/` | Jupyter notebooks for exploration and EDA |
| `visualizations/` | Final visualizations used in the report |

---

## Key Findings

- Global internet adoption has grown steadily, increasing by 58 percentage points from ~15.6% in 2000 to ~73.6% in 2025, at a consistent rate of 2 or 3% per year.
- The gap between high-income and low-income countries has widened over the two decades covered by this analysis, while upper-middle-income countries saw the fastest growth, nearly closing the gap with high-income countries.
- Regional inequality has narrowed more than income inequality, though significant differences remain.
- At the country level in 2023, the top 10 countries are predominantly wealthy, oil-rich, or Nordic nations, while the bottom 10 are largely poverty-stricken countries prioritising basic infrastructure, healthcare, and security over internet investment.
- The digital divide risks widening further as emerging technologies like AI require infrastructure and capital concentrated in wealthier countries, and climate change may force low-income countries to divert resources away from internet investment.

---

## Tools Used

- Python (pandas, matplotlib, seaborn, plotly)
- Excel (initial data exploration)
- Jupyter Notebooks
