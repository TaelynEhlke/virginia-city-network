# Reconstructing the Social Network of Virginia City, Montana (1880)

An end-to-end data science project using 1880 U.S. Census records to reconstruct the demographic and social structure of Virginia City, Montana. This project combines exploratory data analysis, feature engineering, and graph analytics to transform historical census records into a relationship-based model of a nineteenth-century mining community.

---

## Live Interactive Notebooks

Explore the project interactively on Zerve:

📊 **Exploratory Data Analysis**
> https://app.zerve.ai/report/c136fdf7-0924-4d2e-b725-c7e36db25b72

🕸️ **Historical Network Analysis**
> https://app.zerve.ai/report/61beb0fd-a396-4b20-8032-4a2388f17115

---

## Research Question

Can historical census records be transformed into a social network that reveals patterns of household organization and broader community relationships in Virginia City during the 1880 census?

---

## Project Overview

Historical census records are traditionally analyzed as tabular datasets describing individuals and households. This project demonstrates how those same records can be transformed into graph-based networks, allowing historical communities to be studied through relationships rather than isolated observations.

The project is divided into two complementary analyses:

### Notebook 1 – Exploratory Data Analysis

The first notebook focuses on cleaning and exploring the historical census data through descriptive statistics and visualizations.

Analyses include:

- Data cleaning and preprocessing
- Age distribution
- Sex distribution
- Race distribution
- Marital status analysis
- Occupation frequency
- Birthplace analysis
- Occupation by sex
- Average age by occupation
- Birthplace by occupation

---

### Notebook 2 – Historical Network Analysis

The second notebook reconstructs Virginia City's social structure using graph analysis.

Analyses include:

- Household reconstruction
- Household network creation
- Household size statistics
- Household network visualization
- Degree centrality analysis
- Bipartite community network
- Occupation hubs
- Birthplace hubs
- Community network visualization

---

## Key Findings

- Virginia City was primarily composed of working-age adults, reflecting its role as an active mining community.

- Mining occupations dominated the workforce, although merchants, physicians, hotel keepers, teachers, and other professions demonstrate the presence of a permanent community.

- Household reconstruction successfully transformed census records into a graph-based representation of social relationships.

- Expanding the analysis using occupations and birthplaces revealed broader community connections that are not apparent in traditional tabular census data.

- Bipartite graph modeling provided a cleaner representation of historical relationships than directly connecting every resident with shared characteristics.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- NetworkX
- OpenPyXL
- Jupyter Notebook
- GitHub
- Zerve

---

## Repository Structure

```
Virginia-City-Network/

│
├── README.md
├── requirements.txt
├── LICENSE
│
├── data/
│   └── Virginia City Census Dataset 1880.xlsx
│
├── notebooks/
│   ├── 01_data_exploration.ipynb
│   └── 02_historical_network_analysis.ipynb
│
├── images/
│   ├── age_distribution.png
│   ├── occupation_distribution.png
│   ├── household_network.png
│   └── community_network.png
│
└── requirements.txt
```

---

## Sample Visualizations

*(Insert screenshots here after uploading them to the `images` folder.)*

Example:

```markdown
![Age Distribution](images/age_distribution.png)

![Household Network](images/household_network.png)

![Community Network](images/community_network.png)
```

---

## Future Work

Potential extensions of this project include:

- Incorporating city directories and newspaper archives.
- Linking historical mining company employment records.
- Reconstructing longitudinal social networks across multiple census years.
- Applying community detection algorithms to identify historical social clusters.
- Developing an interactive dashboard for exploring residents and their relationships.

---

## Data Source

1880 United States Census records for Virginia City, Montana.

---

## Author

**Taelyn Ehlke**

Master of Science in Data Analytics (In Progress)

Master of Public Health

Bachelor of Science in Healthcare Administration

LinkedIn: https://www.linkedin.com/in/taelyn-ehlke-b516671b2/
