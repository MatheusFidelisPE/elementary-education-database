# Elementary Education Database for Public Policy Analysis

This repository contains the datasets used in the research **"A new perspective for longitudinal measurement and analysis of public education in Brazil based on open data and machine learning"** published in ICEGOV 2024. The study focuses on analyzing the relationship between educational, economic, and social well-being characteristics of municipalities and their performance in IDEB for elementary education.

## Research Context

The study utilized Brazilian open data to:
- Investigate correlations between municipal indicators and student performance.
- Predict IDEB scores using machine learning models.
- Support evidence-based decision-making for public education policies.

For more details, refer to the [article](https://dl.acm.org/doi/10.1145/3680127.3680216).

## Dataset Information

The repository includes:
- **IDEB scores:** IDEB-E and IDEB-L indicators (2013–2021).
- **Educational indicators:** Variables related to teacher qualifications, school management, and student performance.
- **Economic indicators:** Investments in education, spending per student, and average teacher salaries.
- **Social well-being indicators:** Municipal HDI components (education, income, and longevity).

### Data Sources

- **INEP**: Educational and performance data.
- **SIOPE**: Financial and investment data.
- **Human Development Atlas in Brazil**: HDI-related indicators.

## Citation

If you use this data in your research, please cite the original article:

```
@inproceedings{10.1145/3680127.3680216,
author = {Silva, Matheus and Ferreira, Abilio and Alves, Karine and Valenca, George and Brito, Kellyton},
title = {A new perspective for longitudinal measurement and analysis of public education in Brazil based on open data and machine learning},
year = {2024},
isbn = {9798400717802},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3680127.3680216},
doi = {10.1145/3680127.3680216},
abstract = {In the mid-2000s, e-government began to be seen as a facilitator of transformation in the public sector, promoting transparency, reducing corruption, and increasing social engagement. One of the first steps towards this is providing access to information for the population. Additionally, the popularization of access to raw data from large-scale assessments has enabled analyses that promote public value in the education sector. Many Brazilian studies use large-scale assessments from high school to predict student or school performance, hindering the use of these analyses at the state and municipal levels. In this context, the objective of this study is to analyze the relationship between educational, economic, and social well-being characteristics of municipalities and their respective performance in IDEB for elementary education to support the decision-making process in the development of public polices for elementary education by public resource managers. For this, we used a method based on CRISP-DM. We began by understanding the business, collecting data from open data portals of the Brazilian government and the Human Development Atlas in Brazil. Among these data were HDI, educational investments, and educational indicators of municipalities. We then cleaned the data and proceeded to perform analyses using Spearman’s coefficient and prediction of IDEB-E and IDEB-L indicators using machine learning algorithms such as Linear Regression, Random Forest, and Artificial Neural Network. Finally, we conducted analyses of the important features identified by the most accurate model. As main results, we found a high positive correlation between IDEB and social well-being variables, as well as the level of education of teachers. The methodology and results of this paper may lead to a new perspective of analyzing elementary education at the municipality level by employing both statistical and machine learning models, supporting the public bodies in their decisions regarding investments.},
booktitle = {Proceedings of the 17th International Conference on Theory and Practice of Electronic Governance},
pages = {130–138},
numpages = {9},
keywords = {Machine Learning, Open Data, Education, Elementary School, Brazil, Municipalities},
location = {
},
series = {ICEGOV '24}
}
```
