# Community Support of the LGBTQ+ Community: Love Data Week 2023
This project was done as part of ICPSR's 2023 [International Love Data Week](https://www.icpsr.umich.edu/web/about/cms/3799?utm_source=all&utm_medium=all&utm_campaign=LDW23&utm_id=LDW23) Adopt A Dataset program. 

<p align="center">
<img src="https://github.com/user-attachments/assets/d3c6969e-bacc-4729-a711-11171a1da7d2" width=25% height=25%>
</p>

## Navigation
- **:computer: code:** .Rmd file used to generate final report
- **:file_folder: data:** Generations dataset used for analysis (see desciption and citation in "Data" below)
- **:mag_right: documentation:** Documentation files provided with the original data download (see desciption and citation in "Data" below)
- **:bar_chart: final-report:** Final R Markdown generated PDF report

## Data
The dataset used for this project are public-use files from "Generations: A Study of the Life and Health of LGB People in a Changing Society, United States, 2016-2019." This study explored a variety of health factors for a multi-generational cohort of lesbians, gay men, and bisexuals.

### Citation
Meyer, Ilan H. Generations: A Study of the Life and Health of LGB People in a Changing Society, United States, 2016-2019. Inter-university Consortium for Political and Social Research [distributor], 2023-01-05. https://doi.org/10.3886/ICPSR37166.v2

## Methods
This project used the baseline data (Wave 1) collected in the Generations study to examine similarities and differences across demographic groups for two questions related to community support networks:
1. I can talk about my problems with my family.
2. I can talk about my problems with my friends.

Participants were able to respond with (7) “Very Strongly Agree,” (6) “Strongly Agree,” (5) “Mildly Agree,” (4) “Neutral,” (3) “Mildly Disagree,” (2) “Strongly Disagree,” or (1) “Very Strongly Disagree.”

This was then compared to respondent's overall Satisfaction with Life score, which is a composite measure based on five different questions:
1. In most ways, my life is close to my ideal.
2. The conditions of my life are excellent.
3. I am satisfied with life.
4. So far I have gotten the important things I want in life.
5. If I could live my life over, I would change almost nothing.

Participants were given the same seven likert scale options and a final Satisfaction with Life score is the average of these five responses.

### Programs
All analysis was conducted in R with a final report generated using R Markdown.

The association plot was created using the [vcd package](https://cran.r-project.org/web/packages/vcd/index.html). The ridge graphs were created using the [ggridges package](https://cran.r-project.org/web/packages/ggridges/index.html) in conjunction with [ggplot2](https://cran.r-project.org/web/packages/ggplot2/index.html) and colored with [viridis](https://cran.r-project.org/web/packages/viridis/index.html).

## Results
The majority of participants seem to have both family and friend support systems, or neither. Additionally, those with stronger support systems tended to also have higher Satisfaction with Life scores. However, when looking at different demographic breakdowns, these satisfaction scores were more polarized when looking at just family support compared to friend support. This may suggest that having a strong family support system is a better indicator of overall life satisfaction than a friend support system. 

Given that approximately one third of participants are not able to discuss their problems with their families, improving family support structures could pose an important opportunity to improve overall life satisfaction among the LGBTQ+ community.
