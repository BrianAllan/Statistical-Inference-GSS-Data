## Statistical Inference with Data from the General Social Survey

### Project Description

This project was produced in 2019 for the course **"Inferential Statistics"**, the second in the five course sequence of courses for the Coursera Specialization **Statistics with R** produced by Duke University.

Data was provided from the General Social Survey (GSS) of 2012.  The GSS gathers data on contemporary American society in order to monitor and explain trends and constants in attitudes, behaviors, and attributes.  The project tasks were to:

- develop a research question and a hypothesis to address that question
- explore and analyze the data using tables and plots
- use statistical inference techniques to address whether to accept the alternative, versus the null, hypothesis

The research question chosen was: In the year 2012, was there a statistically significant difference in degree of confidence toward the scientific community based on one’s political stance – left-leaning, moderate, or right-leaning?  A Chi-Squared test was used and a p-value of 0.089 was obtained leading to the conclusion that the null hypothesis (that there was no difference) should not be rejected at the standard significance level of 0.05.

Coding and documentation were done using `R` and an `R` Markdown file to produce the [project report](https://brianallan.github.io/Statistical-Inference-GSS-Data/).

### Files Used

BAW_stat_inf_project.Rmd    
gss.Rdata    

### Tools Used

`R` with `ggplot2`, `dplyr`, and `statsr` libraries in RStudio.