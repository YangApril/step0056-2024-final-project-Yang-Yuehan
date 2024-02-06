# step0056-2024-final-project-Yang-Yuehan
Dataset_Proposal
# Dataset Introduction
This dataset is the result of a three-year continuous observation by Johns Hopkins University on COVID-19 data. The data spans from January 22, 2020, to March 10, 2023, and includes information on cases, deaths, vaccines, testing, and demographics. 

This public dataset can be accessed on GitHub at the links: 
  https://github.com/CSSEGISandData/COVID-19/tree/master and 
  https://github.com/govex/COVID-19?tab=readme-ov-file 

# What is the issue you are addressing?
The issue addressed is understanding the global impact of COVID-19, focusing on the effectiveness of different interventions (lockdowns, vaccination campaigns) in controlling the spread and mortality of the virus.

# Why is this issue important?
The significance of this issue is manifested in how, during the COVID-19 pandemic, global public health systems can leverage data analysis to play a crucial role in reflecting on the effectiveness of decision-making and preventive measures. Especially for policymakers, this data analysis process can guide future epidemic preparedness efforts and help in the efficient allocation of resources to mitigate their impact.

# What data are you using to explore this issue?
I am using COVID-19 case counts, mortality data, recover rate, vaccination rates, and policy intervention records from the CSSEGISandData/COVID-19 and govex/COVID-19 repositories.

# What has already been done with this data?
Previous analyses have focused on descriptive statistics of cases and deaths, trends over time, geographic spread patterns, and initial correlations between intervention strategies and case reduction.
1. Trend analysis concerning COVID-19 case and death growth rates. Stier et al. (2021) showed a correlation between city size and epidemic dynamics.
2. Geographical distribution. de Oliveira Otto et al. (2022) utilized local community and hospital data from a diverse U.S. metropolitan area to detect new outbreak waves and characterize specific wave periods among community residents.
3. Forecast future trends of COVID-19 cases and deaths. A BMC Infectious Diseases article discussed the use of time series forecasting and machine learning models for predicting daily new cases and cumulative cases (Wang et al., 2022). 

# What questions are you trying to answer? 
1. How do different public health interventions impact the spread and mortality rate of COVID-19 within and across countries?
2. What is the relationship between vaccination rates and case numbers/mortality over time, adjusting for public health interventions?
3. How do socioeconomic factors influence the effectiveness of different interventions?

# Why is what you are doing different from other analyses and visualizations you have found? How does this data exploration contribute to answering your questions (again relative to other work)?
I mainly want to supplement the data analysis by adding financial data such as the global GDP to explore the impact of the New Crown Pneumonia on the global economic development. And using the United States as an example, focusing on the analysis of that country.

# Reference List
Wang, Y., Yan, Z., Wang, D. et al. (2022). 'Prediction and analysis of COVID-19 daily new cases and cumulative cases: times series forecasting and machine learning models.', BMC Infectious Diseases 22(1), pp.495. doi. 10.1186/s12879-022-07472-6

de Oliveira Otto, M.C., Brito, F.A., Tark, J.Y. et al. (2022). 'Case growth analysis to inform local response to COVID-19 epidemic in a diverse U.S community.', Scientific Reports, 12(1), pp.16217. doi. 10.1038/s41598-022-20502-2 

Stier, A.J., Berman, M.G. & Bettencourt, L.M.A. (2021). 'Early pandemic COVID-19 case growth rates increase with city size.', Urban Sustain, 31(1), pp.1-6. doi. 10.1038/s42949-021-00030-0 

