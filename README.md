# Statistical
Analysis
This work is licensed under the Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License. To view a copy of this license, visit
http://creativecommons.org/licenses/by-nc-nd/4.0/.

CHAPTER 4

1. Introduction
This cross-sectional study examined teachers' responses to work-related stress and its impact on their personal relationship satisfaction. It was hypothesized that teachers would be less satisfied with their relationships when there are high levels of work-related stress. Further hypotheses surmised that teachers with more teaching experience would have less work-related stress and greater personal relationship satisfaction than their less experienced peers. The results include a statistical analysis of the Couples Satisfaction index and the Teacher Stress Inventory score.  

2. Materials&Methods

2.1. Research questions and statistical hypotheses

RQ1: Is there a significant correlation between stress teachers experience on the job and their personal relationship satisfaction according to the Teacher Stress Inventory score and Couples Satisfaction Index?

H1: Teacher Stress Inventory score and Couples Satisfaction index are not correlated, that is, relationship satisfaction is independent of the stress teachers experience at work.

RQ1.1: Is there a significant correlation between the Time Management, Work-related stressors, Professional distress, Discipline and Motivation, and Professional Investment related stress teachers experience on the job and their personal relationship satisfaction according to the Teacher Stress Inventory subscores and Couples Satisfaction Index?

H1.1: Teacher Stress Inventory subscores and Couples Satisfaction index are not correlated, that is, relationship satisfaction is independent of the Teacher Stress Inventory subscores related stress teachers experience at work.


2.2. Questionnaire
A questionnaire was sent to work emails of certificated teachers in two Orangeburg County Schools. As agreed upon by the district superintendent, the surveys were sent to maintain anonymity by school administrators. The questionnaire contained questions regarding the socio-demographic characteristics as well as the Couples Satisfaction Index (CSI-16) and Teacher Stress Inventory.


2.3. Statistical Analysis
Continuous variables are expressed as means with standard deviations or as medians with lower and upper quartiles, and categorical variables as frequencies (percentages). The χ2 test was used to assess whether the proportions of survey respondents in each of the socio-demographic categories are equal. To test the existence of a correlation between the two survey scores, we used Pearson’s correlation coefficient. For continuous variables, independent samples t-test or one-way analysis of variance (ANOVA) were used to assess if there were significant differences between the groups according to socio-demographic characteristics. The level of significance was set at 0.05. Statistical analyses were performed using R - A language and environment for statistical computing (R Foundation for Statistical Computing, Vienna, Austria) [reference if needed].
 

3. Results

The questionnaire was sent to work emails of 184 certificated teachers in two Orangeburg County Schools. There were 137 completed surveys which represented a 74% return rate. From this group of 137 teachers, 44.5% were elementary teachers, 40.1% taught at the middle school level, and 9.5% taught at the high school level. Regarding the level of education, 38.7% have a bachelor’s degree, 46% have a master’s degree, and 11.7% have a doctorate. Finally, 24.8% have 0-5 years of teaching experience, 30.7% have 6-10 years of teaching experience, 18.2% have 11-15 years of teaching experience, 10.9%  have 16-20 years of teaching experience and 8.6% have 21 or more years of teaching experience. Table 1 displays the demographic data of survey participants.

Table 1. Characteristics of survey respondents
Variable	Frequency (percentage)
Gender	
Female	68 (49.6%)
Male	60 (43.8%)
Non-binary/ Non-conforming	2 (1.5%)
Transgender	2 (1.5%)
Missing	5 (3.6%)
	
Relationship status	
Cohabitating	11 (8%)
Divorced	9 (6.6%)
In a committed relationship	13 (9.5%)
Married	41 (29.9%)
Separated	4 (2.9%)
Single and dating	52 (38%)
Missing	7 (5.1%)
	
Teaching level	
Elementary school	61 (44.5%)
High school	13 (9.5%)
Middle school	55 (40.1%)
Missing	8 (5.8%)
	
Level of education	
Bachelor’s degree	53 (38.7%)
Master’s degree	63 (46%)
Doctorate	16 (11.7%)
Missing	5 (3.6%)
	
Teaching experience	
0-5 years	34 (24.8%)
6-10 years	42 (30.7%)
11-15 years	25 (18.2%)
16-20 years	15 (10.9%)
21 or more years	12 (8.8%)
Missing	9 (6.6%)
	
Teaching created stress in the relationship	
Yes	106 (77.4%)
No	24 (17.5%)
Missing	7 (5.1%)
Total	137 (100%)
Data are presented as frequency (percentage).


3.1. Assessing the distribution of participants in the categorical groupings according to the socio-demographic characteristics

Using the chi-square goodness-of-fit test, we tested whether the proportions of survey respondents in each of the categorical variable outcomes are equal. 

3.1.1. Gender
Across gender, our test statistic was statistically significant: χ2(2) = 117.45, p < 0.001. Therefore, we rejected the null hypothesis and concluded that there are statistically significant differences in the gender distribution of our survey respondents, with fewer people identifying as “Non-binary/ Non-conforming” (n = 2) or “Transgender” (n = 2) compared to either "Male" (n = 60) or  "Female" (n = 68). 

3.1.2. Relationship status
Across relationship status, our test statistic was statistically significant: χ2(2) = 90.25, p < 0.001. Therefore, we rejected the null hypothesis and concluded that there are statistically significant differences in the distribution of relationship status, with less people “Separated” (n = 4), “Divorced” (n = 9), “In a committed relationship” (n = 13) or “Cohabitating” (n = 11) compared to either "Married" (n = 41) or "Single and dating" (n = 52). 

3.1.3. Teaching level
Across the teaching level, our test statistic was statistically significant: χ2(2) = 31.81, p < 0.001. Therefore, we rejected the null hypothesis and concluded that there are statistically significant differences in the distribution of teaching level, with fewer people teaching in high school (n = 13) compared to middle school (n = 55) and elementary school (n = 61).

3.1.4. Level of education
Across the level of education, our test statistic was statistically significant: χ2(2) = 27.9, p < 0.001. Therefore, we rejected the null hypothesis and concluded that there are statistically significant differences in the distribution of education levels, with fewer people having a doctorate (n = 16) compared to those having a master’s degree (n = 63) and bachelor’s degree (n = 53). 

3.1.5. Teaching experience
Across the teaching experience, our test statistic was statistically significant: χ2(2) = 24.9, p < 0.001. Therefore, we rejected the null hypothesis and concluded that there are statistically significant differences in the distribution of teaching experience, with fewer people teaching 16-20 years (n =15) or 21 or more years (n = 12) compared to teaching less than 15 years. 

3.1.6. Teaching-created relationship stress
Finally, for teaching-created relationship stress, our test statistic was statistically significant: χ2(2) = 51.7, p < 0.001. Therefore, we rejected the null hypothesis and concluded that there are statistically significant differences in the distribution of teaching-created relationship stress, with fewer people answering “No” (n =24) compared to the vast majority answering “Yes” (n = 106).


3.2. Assessing the distribution of participants according to two categorical groupings (cross tabulation)

Table 2. Cross tabulation of teaching level across gender 
	Teaching level	Total
	Missing (NA)	Elementary	High	Middle	
Gender	Missing (NA)	1	1	0	3	5
	Female	3	26	6	33	68
	Male	4	33	7	16	60
	Non-binary	0	0	0	2	2
	Transgender	0	1	0	1	2
Total		8	61	13	55	137

Majority of study participants taught Elementary school (44.5%), and 33 out of 61 of them were male. Regarding middle school, the majority of teachers teaching in middle schools were female (33 out of 55). High school teachers were equally male or female, while there were no non-binary or transgender teachers teaching in high schools.





Table 3. Crosstabulation of relationship status across gender
	Gender	Total
	Missing (NA)	Female	Male	Non-binary	Transgender	
Relationship status	Missing (NA)	1	4	2	0	0	7
	Cohabitating 	1	10	0	0	0	11
	Divorced 	0	4	5	0	0	9
	In a comitted relationship 	2	6	3	0	2	13
	Married 	1	32	6	2	0	41
	Separated 	0	3	1	0	0	4
	Single and dating	0	9	43	0	0	52
Total		5	68	60	2	2	137

Majority of respondents were single and dating (38%), most of them being male (43 out of 52). Next followed married participants (30%), most of them being female (32 out of 41). Female participants were the only one cohabitating, while divorced participants were equally male or female.


Table 4. Crosstabulation of education level across gender
	Gender	Total
	Missing (NA)	Female	Male	Non-binary	Transgender	
Education level	Missing (NA)	1	2	2	0	0	5
	Bachelor’s degree 	1	17	35	0	1	53
	Master’s degree 	2	39	19	2	1	63
	Doctorate	1	10	4	0	1	16
Total		5	68	60	2	2	137


Majority of respondents had a Master’s degree (46%), most of them being female (39 out of 63). Next followed participants with a Bachelor’s degree (39%), most of them being male (35 out of 53). Participants with a doctorate were mainly women (10 out of 16).



3.3. Assesing teaching-created stress in the relationship across socio-demographic characteristics of survey respondents 

3.3.1. Gender

Table 5. Crosstabulation of teaching-created stress in the relationship across gender
	Teaching created stress in the relationship	Total
	Missing (NA)	No	Yes	
Gender	Missing (NA)	0	2	3	5
	Female 	7	18	43	68
	Male 	0	3	57	60
	Non-binary	0	1	1	2
	Transgender	0	0	2	2
Total		7	24	106	137

H1: Proportions of the teaching-created stress in the relationship are the same across gender, that is, teaching-created stress is independent of gender.

Using Fisher-Freeman-Halton test, we checked the plausibility of hypothesis H1 stating that the proportions of the teaching-created stress in the relationship are the same across gender. Given that the p-value of Fisher-Freeman-Halton test was <0.001, we rejected the null hypothesis H1. Therefore, there is statistically significant association between teaching-created stress in the relationship and gender.

From Table 5, we can see that all transgender participants reported that teaching created stress in their relationship, but this results should be interpreted with caution since there were only two transgender participants in the sample. We can also see that majority of men (57 out of 50, which is 95%) reported that teaching created stress in their relationship. This result was not so extreme in women, where 63% reported that teaching created stress in their relationship. Non-binary participants answered Yes/No in equal proportions.








3.3.2. Relationship status

Table 6. Crosstabulation of teaching-created stress in the relationship across relationship status
	Teaching created stress in the relationship	Total
	Missing (NA)	No	Yes	
Relationship status	Missing (NA)	1	3	3	7
	Cohabitating	1	7	3	11
	Divorced	0	1	8	9
	In a comitted relationship	0	3	10	13
	Married	5	8	28	41
	Separated	0	1	3	4
	Single and dating	0	1	51	52
Total		7	24	106	137


H1: Proportions of the teaching-created stress in the relationship are the same across relationship status, that is, teaching-created stress is independent of the relationship status.

Using Fisher-Freeman-Halton test, we checked the plausibility of hypothesis H1 stating that the proportions of the teaching-created stress in the relationship are the same across different relationship statuses. Given that the p-value of Fisher-Freeman-Halton test was <0.001, we rejected the null hypothesis H1. Therefore, there is statistically significant association between teaching-created stress in the relationship and relationship status.

From Table 6, we can see that all relationship status groups except ‘Cohabitating’ mainly reported that teaching created stress in their relationship. The cohabitating group was the only one in which more participants (63%) reported that teaching did not create stress in their relationship.
An interesting result is that teaching created stress in 98% of single and dating participants, and in 88% of divorced ones.





3.3.3. Teaching level

Table 7. Crosstabulation of teaching-created stress in the relationship across teaching level
	Teaching created stress in the relationship	Total
	Missing (NA)	No	Yes	
Teaching level	Missing (NA)	1	2	5	8
	Elementary school	2	4	55	61
	Middle school	2	3	8	13
	High school	2	15	38	55
Total		7	24	106	137

H1: Proportions of the teaching-created stress in the relationship are the same across teaching level, that is, teaching-created stress is independent of the teaching level.

Using Fisher-Freeman-Halton test, we checked the plausibility of hypothesis H1 stating that the proportions of the teaching-created stress in the relationship are the same across different teaching levels. Given that the p-value of Fisher-Freeman-Halton test was 0.034<0.05, we rejected the null hypothesis H1. Therefore, there is statistically significant association between teaching-created stress in the relationship and teaching level.

From Table 7, we can see that 90% of elementary school teachers reported that teaching created stress in their relationship, as opposed to 61% of middle school and 69% of high school teachers reporting the same outcome.


3.3.4. Level of education

Table 8. Crosstabulation of teaching-created stress in the relationship across level of education
	Teaching created stress in the relationship	Total
	Missing (NA)	No	Yes	
Teaching level	Missing (NA)	0	3	2	5
	Bachelor’s degree	2	3	48	53
	Master’s degree	2	16	45	63
	Doctorate	3	2	11	16
Total		7	24	106	137

H1: Proportions of the teaching-created stress in the relationship are the same across level of education, that is, teaching-created stress is independent of the education level.

Using Fisher-Freeman-Halton test, we checked the plausibility of hypothesis H1 stating that the proportions of the teaching-created stress in the relationship are the same across different levels of education. Given that the p-value of Fisher-Freeman-Halton test was 0.002<0.05, we rejected the null hypothesis H1. Therefore, there is statistically significant association between teaching-created stress in the relationship and level of education.

From Table 8, we can see that majority (90.5%) of teachers holding a Bachelor’s degree reported that teaching created stress in their relationship, as opposed to 71% of Master’s degree and 68% of doctoral degree teachers reporting the same outcome.


3.3.5. Teaching experience

Table 9. Crosstabulation of teaching-created stress in the relationship across teaching experience
	Teaching created stress in the relationship	Total
	Missing (NA)	No	Yes	
Teaching experience	Missing (NA)	4	2	3	9
	0-5 years	0	1	33	34
	6-10 years	0	9	33	42
	11-15 years	2	7	16	25
	16-20 years	1	2	12	15
	21 or more years	0	3	9	12
Total		7	24	106	137

H1: Proportions of the teaching-created stress in the relationship are the same across teaching experience, that is, teaching-created stress is independent of the teaching experience.

Using Fisher-Freeman-Halton test, we checked the plausibility of hypothesis H1 stating that the proportions of the teaching-created stress in the relationship are the same across different levels of teaching experience. Given that the p-value of Fisher-Freeman-Halton test was <0.001, we rejected the null hypothesis H1. Therefore, there is statistically significant association between teaching-created stress in the relationship and teaching experience.

From Table 9, we can see that a vast majority (97%) of teachers having only 0-5 years of teaching experience reported that teaching created stress in their relationship, as opposed to more experienced teachers, a result which is expected.




3.4. Descriptive statistics of the Couples Satisfaction Index and Teacher Stress Inventory questionnaires

Out of the 137 surveyed teachers for whom the researcher was able to calculate a Couples' Satisfaction Index (CSI-16), 93 had a score under the cutoff of 51.5, meaning that they reported notable relationship dissatisfaction. This corresponds to 68% of respondents. 


Table 10. Descriptive statistics of the CSI-16 score and Teacher Stress Inventory scores
Score	Mean	SD	Minimum	Maximum	Min. possible score	Max. possible score
CSI-16 score	47.15	14.41	2	81	0	81
Teacher Stress Inventory score	2.81	0.6	1	4.2	1	5
Teacher Stress Inventory Time Management subscore	2.95	0.69	1	4.4	1	5
Teacher Stress Inventory Work-related stressors subscore	3.04	0.75	1	5	1	5
Teacher Stress Inventory Professional distress subscore	3.02	0.71	1	5	1	5
Teacher Stress Inventory Discipline and Motivation subscore	2.93	0.69	1	4.83	1	5
Teacher Stress Inventory Professional investment subscore	2.85	0.82	1	5	1	5
Teacher Stress Inventory Emotional manifestations subscore	2.72	0.82	1	5	1	5
Teacher Stress Inventory Cardiovascular manifestations subscore	2.58	0.88	1	5	1	5
Teacher Stress Inventory Fatigue manifestations subscore	2.8	0.83	1	4.8	1	5
Teacher Stress Inventory Gastronomical manifestations subscore	2.64	1.01	1	5	1	5
Teacher Stress Inventory Behavioral manifestations subscore	2.56	0.91	1	4	1	5



Table 11. Descriptive statistics of the CSI-16 questionnaire

Question		Mean	SD	Minimum	Maximum	Min. possible value	Max. possible value
1. Please indicate the degree of happiness, all things considered, of your relationship.		3.85	1.42	1	6	0	6
2. In general, how often do you think that things between you and your partner are going well?		3.18	0.96	1	5	0	5
3. Our relationship is strong		2.5	1.2	0	5	0	5
4. My relationship with my partner makes me happy		2.59	1.3	0	5	0	5
5. I have a warm and comfortable relationship with my partner		2.57	1.4	0	5	0	5
6. I really feel like part of a team with my partner		2.51	1.5	0	5	0	5
7. How rewarding is your relationship with your partner?		3.07	1.16	0	5	0	5
8. How well does your partner meet your needs?		2.85	1.18	0	5	0	5
9. To what extent has your relationship met your original expectations?		2.58	1.4	0	5	0	5
10. In general, how satisfied are you with your relationship?		2.53	1.27	0	5	0	5


3.5. Correlation between stress teachers experience on the job and their personal relationship satisfaction
				
RQ1: Is there a significant correlation between stress teachers experience on the job and their personal relationship satisfaction according to the Teacher Stress Inventory score and Couples Satisfaction Index?

H1: Teacher Stress Inventory score and Couples Satisfaction index are not correlated, that is, relationship satisfaction is independent of the stress teachers experience at work.
 
Figure 1. Scatter plot of the Teacher Stress Inventory score across Couples Satisfaction Index. The red line represents the line of best fit (obtained using the linear method) and the green area represents the 95% confidence interval (CI) of the best-fit line.

Correlation analysis revealed that there was a statistically significant negative association between the Teacher Stress Inventory score and Couples Satisfaction Index (r=-0.21, p-value=0.014). Given that the p-value is less than 0.05, we can reject the null hypothesis of zero correlation and conclude that, as the stress teachers experience on the job increases, their satisfaction with their personal relationship significantly decreases.

3.6. Analyses according to the subscores of the Teacher Stress Inventory

 
Figure 2. Scatter plot of the Teacher Stress Inventory Time Management subscore, Work-related stressors subscore, Professional distress subscore, Discipline, and Motivation subscore, and Professional Investment subscore across Couples Satisfaction Index. The red line represents the line of best fit (obtained using the linear method) and the green area represents the 95% confidence interval (CI) of the best-fit line.

RQ1.1: Is there a significant correlation between the Time Management, Work-related stressors, Professional distress, Discipline and Motivation, and Professional Investment related stress teachers experience on the job and their personal relationship satisfaction according to the Teacher Stress Inventory subscores and Couples Satisfaction Index?

H1.1: Teacher Stress Inventory subscores and Couples Satisfaction index are not correlated, that is, relationship satisfaction is independent of the Teacher Stress Inventory subscores  related stress teachers experience at work.

3.6.1. Teacher Stress Inventory Time Management subscore

Correlation analysis revealed that there was a statistically significant negative association between the Teacher Stress Inventory Time Management subscore and Couples Satisfaction Index (r=-0.22, p-value=0.008). Given that the p-value is less than 0.05, we can reject the null hypothesis of zero correlation and conclude that, as the time management-related stress teachers experience on the job increases, their satisfaction with their personal relationship significantly decreases.
3.6.2. Teacher Stress Inventory Work-related stressors subscore
Correlation analysis revealed that there was a statistically significant negative association between the Teacher Stress Inventory Work-related stressors subscore score and Couples Satisfaction Index (r=-0.18, p-value=0.03). Given that the p-value is less than 0.05, we can reject the null hypothesis of zero correlation and conclude that, as the work-related stressors teachers experience on the job increase, their satisfaction with their personal relationship significantly decreases.
3.6.3. Teacher Stress Inventory Professional distress subscore
Correlation analysis revealed that there was a statistically significant negative association between Teacher Stress Inventory Professional distress subscore and the Couples Satisfaction Index (r=-0.18, p-value=0.03). Given that the p-value is less than 0.05, we can reject the null hypothesis of zero correlation and conclude that, as the professional distress teachers experience on the job increases, their satisfaction with their personal relationship significantly decreases.
3.6.4. Teacher Stress Inventory Discipline & Motivation subscore

Correlation analysis revealed that there was a negative association between Teacher Stress Inventory Discipline & Motivation subscore and the Couples Satisfaction Index, but the association was not statistically significant (r=-0.14, p-value=0.1). Given that the p-value is larger than 0.05, we can not reject the null hypothesis of zero correlation. We conclude that Discipline & Motivation related stress teachers experience at work is not associated with satisfaction with their personal relationships.
3.6.5. Teacher Stress Inventory Professional investment subscore
Correlation analysis revealed that there was a statistically significant negative association between the Teacher Stress Inventory Professional investment subscore and the Couples Satisfaction Index (r=-0.22, p-value=0.008). Given that the p-value is less than 0.05, we can reject the null hypothesis of zero correlation and conclude that, as the professional investment-related stress teachers experience on the job increases, their satisfaction with their personal relationship significantly decreases.

 Figure 3. Scatter plot of the Teacher Stress Inventory Emotional manifestations subscore, Fatigue manifestations subscore, Cardiovascular manifestations subscore, Gastronomical manifestations subscore, and Behavioral manifestations subscore across Couples Satisfaction Index. The red line represents the line of best fit (obtained using the linear method) and the green area represents the 95% confidence interval (CI) of the best-fit line.
3.6.6. Teacher Stress Inventory Emotional manifestations subscore
Correlation analysis revealed that there was a negative association between Teacher Stress Inventory Emotional manifestations subscore and the Couples Satisfaction Index, but the association was not statistically significant (r=-0.11, p-value=0.18). Given that the p-value is larger than 0.05, we can not reject the null hypothesis of zero correlation. We conclude that Emotional manifestations-related stress teachers experience at work is not associated with satisfaction with their personal relationships.
3.6.7. Teacher Stress Inventory Fatigue manifestations subscore
Correlation analysis revealed that there was a statistically significant negative association between the Teacher Stress Inventory Fatigue manifestations subscore and the Couples Satisfaction Index (r=-0.19, p-value=0.03). Given that the p-value is less than 0.05, we can reject the null hypothesis of zero correlation and conclude that, as the fatigue-related stress teachers experience on the job increases, their satisfaction with their personal relationship significantly decreases.
3.6.8. Teacher Stress Inventory Cardiovascular manifestations subscore
Correlation analysis revealed that there was a negative association between Teacher Stress Inventory Cardiovascular manifestations subscore and the Couples Satisfaction Index, but the association was not statistically significant (r=-0.09, p-value=0.29). Given that the p-value is larger than 0.05, we can not reject the null hypothesis of zero correlation. We conclude that Cardiovascular manifestations related stress teachers experience at work is not associated with satisfaction with their personal relationship.
3.6.9. Teacher Stress Inventory Gastronomical manifestations subscore
Correlation analysis revealed that there was a negative association between Teacher Stress Inventory Gastronomical manifestations subscore and the Couples Satisfaction Index, but the association was not statistically significant (r=-0.09, p-value=0.32). Given that the p-value is larger than 0.05, we can not reject the null hypothesis of zero correlation. We conclude that Gastronomical manifestations related stress teachers experience at work is not associated with satisfaction with their personal relationship.
3.6.10. Teacher Stress Inventory Behavioral manifestations subscore
Correlation analysis revealed that there was a negative association between Teacher Stress Inventory Behavioral manifestations subscore and the Couples Satisfaction Index, but the association was not statistically significant (r=-0.16, p-value=0.06). Given that the p-value is larger than 0.05, we can not reject the null hypothesis of zero correlation. We conclude that Behavioral manifestations related stress teachers experience at work is not associated with satisfaction with their personal relationship.

3.7. CSI-16 across socio-demographic characteristics of survey respondents
In order to explore the effects of socio-demographic characteristics on participants’ level of satisfaction with their personal relationships, we used a one-way analysis of variance (ANOVA). The dependent variable was the level of satisfaction (CSI-16 Index), whereas the subsequent analyses’ independent variables were the socio-demographic characteristics of participants (such as gender, relationship status, teaching level, education level, and teaching experience).

Table 12. Results of the one-way ANOVA test: Couples Satisfaction Index across Gender
Variable	Sum of squares of deviation	Sum of squares	Degrees of freedom	F-statistics	p-value
Couples Satisfaction Index	Between groups	358.8	3	20.58	0.63
	Within groups	26424.11	128	
	Total	26782.9	131	

In the case of gender, analysis of variance was used to check the plausibility of the assumption of no significant difference in the levels of satisfaction with their personal relationships between participants of a different gender. Since the p-value of the ANOVA test was 0.63>0.05, we failed to reject the null hypothesis and conclude that there is no statistically significant difference in the levels of satisfaction with the personal relationships between participants of different gender (Table 12).


Table 13. Results of the one-way ANOVA test: Couples Satisfaction Index across relationship status
Variable	Sum of squares of deviation	Sum of squares	Degrees of freedom	F-statistics	p-value
Couples Satisfaction Index	Between groups	1000.23	5	0.9	0.45
	Within groups	26140.08	124	
	Total	27140.31	129	

In the case of relationship status, analysis of variance was used to check the plausibility of the assumption of no significant difference in the levels of satisfaction with their personal relationships between participants of different relationship statuses. Since the p-value of the ANOVA test was 0.45>0.05, we failed to reject the null hypothesis and conclude that there is no statistically significant difference in the levels of satisfaction with the personal relationships between participants of different relationship statuses (Table 13).

Table 14. Results of the one-way ANOVA test: Couples Satisfaction Index across teaching level
Variable	Sum of squares of deviation	Sum of squares	Degrees of freedom	F-statistics	p-value
Couples Satisfaction Index	Between groups	631.15	2	1.48	0.23
	Within groups	26891.7	126	
	Total	27522.8	128	

In the case of teaching level, analysis of variance was used to check the plausibility of the assumption of no significant difference in the levels of satisfaction with their personal relationships between participants of different teaching levels. Since the p-value of the ANOVA test was 0.45>0.05, we failed to reject the null hypothesis and conclude that there is no statistically significant difference in the levels of satisfaction with the personal relationships between participants of different teaching levels (Table 14).


Table 15. Results of the one-way ANOVA test: Couples Satisfaction Index across the level of education
Variable	Sum of squares of deviation	Sum of squares	Degrees of freedom	F-statistics	p-value
Couples Satisfaction Index	Between groups	584.9	2	1.38	0.25
	Within groups	27264.9	129	
	Total	27849.9	131	

In the case of education level, analysis of variance was used to check the plausibility of the assumption of no significant difference in the levels of satisfaction with their personal relationships between participants of different levels of education. Since the p-value of the ANOVA test was 0.45>0,05, we failed to reject the null hypothesis and conclude that there is no statistically significant difference in the levels of satisfaction with the personal relationships between participants of different levels of education (Table 15).


Table 16. Results of the one-way ANOVA test: Couples Satisfaction Index across teaching experience
Variable	Sum of squares of deviation	Sum of squares	Degrees of freedom	F-statistics	p-value
Couples Satisfaction Index	Between groups	2263.8	4	2.73	0.03
	Within groups	25532.1	123	
	Total	27795.9	127	

In the case of teaching experience, analysis of variance was used to check the plausibility of the assumption of no significant difference in the levels of satisfaction with their personal relationships between participants of different teaching experiences. Since the p-value of the ANOVA test was 0.03<0.05, we reject the null hypothesis and conclude that there is a statistically significant difference in the participant’s levels of satisfaction with their personal relationships between participants of different teaching experiences (Table 16). Furthermore, using post-hoc Tukey test, we found that the main cause of the statistically significant difference is the difference in the levels of satisfaction between 6-10 years and 21 or more years of teaching experience (p-value=0.03), and 11-15 years and 21 or more years of teaching experience (p-value=0.02), where, in both cases, teachers with 21 or more years of experience had higher CSI-16 score than their less experienced peers.

3.8. Teacher Stress Inventory score across socio-demographic characteristics of survey respondents
Table 17. Results of the one-way ANOVA test: Teacher Stress Inventory score across gender
Variable	Sum of squares of deviation	Sum of squares	Degrees of freedom	F-statistics	p-value
Couples Satisfaction Index	Between groups	1.165	3	1.09	0.36
	Within groups	45.82	128	
	Total	47	131	

In the case of gender, analysis of variance was used to check the plausibility of the assumption of no significant difference in the Teacher Stress Inventory score between participants of a different gender. Since the p-value of the ANOVA test was 0.36>0.05, we failed to reject the null hypothesis and conclude that there is no statistically significant difference in the Teacher Stress Inventory score between participants of different levels of education (Table 17).

Table 18. Results of the one-way ANOVA test: Teacher Stress Inventory score across relationship status
Variable	Sum of squares of deviation	Sum of squares	Degrees of freedom	F-statistics	p-value
Couples Satisfaction Index	Between groups	15.62	5	11.65	0.0005
	Within groups	33.24	124	
	Total	48.9	129	

In the case of relationship status, analysis of variance was used to check the plausibility of the assumption of no significant difference in the Teacher Stress Inventory score between participants of different relationship statuses. Since the p-value of the ANOVA test was 0.0005<0.05, we reject the null hypothesis and conclude that there is a statistically significant difference in the participant’s Teacher Stress Inventory score between participants of different relationship statuses (Table 18). Furthermore, using the post-hoc Tukey test, we found that the “Cohabitating” group had a significantly lower Teacher Stress Inventory score than all of the other groups.

Table 19. Results of the one-way ANOVA test: Teacher Stress Inventory score across teaching level
Variable	Sum of squares of deviation	Sum of squares	Degrees of freedom	F-statistics	p-value
Couples Satisfaction Index	Between groups	3.77	2	5.33	0.006
	Within groups	44.59	126	
	Total	48.4	128	

In the case of teaching level, analysis of variance was used to check the plausibility of the assumption of no significant difference in the Teacher Stress Inventory score between participants of different teaching levels. Since the p-value of the ANOVA test was 0.006<0.05, we reject the null hypothesis and conclude that there is a statistically significant difference in the participant Teacher Stress Inventory score between participants of different teaching levels (Table 19). Furthermore, using the post-hoc Tukey test, we found that the Middle school teaching group had a significantly lower Teacher Stress Inventory score than all of the other groups.

Table 20. Results of the one-way ANOVA test: Teacher Stress Inventory score across the level of education
Variable	Sum of squares of deviation	Sum of squares	Degrees of freedom	F-statistics	p-value
Couples Satisfaction Index	Between groups	4.45	2	6.6	0.002
	Within groups	43.5	129	
	Total	47.9	131	

In the case of education level, analysis of variance was used to check the plausibility of the assumption of no significant difference in the Teacher Stress Inventory score between participants of different levels of education. Since the p-value of the ANOVA test was 0.002<0.05, we reject the null hypothesis and conclude that there is a statistically significant difference in the participant Teacher Stress Inventory score between participants of different levels of education (Table 20). Furthermore, using the post-hoc Tukey test, we found that the Master’s degree group had a significantly lower Teacher Stress Inventory score than all of the other groups.

Table 21. Results of the one-way ANOVA test: Teacher Stress Inventory score across years of teaching experience
Variable	Sum of squares of deviation	Sum of squares	Degrees of freedom	F-statistics	p-value
Couples Satisfaction Index	Between groups	3.19	4	1.25	0.067
	Within groups	43.6	123	
	Total	46.8	127	

In the case of teaching experience, analysis of variance was used to check the plausibility of the assumption of no significant difference in the Teacher Stress Inventory score between participants of different teaching experience. Since the p-value of the ANOVA test was 0.067>0.05, we failed to reject the null hypothesis and conclude that there is no statistically significant difference in the Teacher Stress Inventory score between participants of different teaching experience (Table 21).











 
Discussion

To the best of our knowledge, this is the first study to investigate the association between Teacher Stress and satisfaction with their personal relationship.

Interpretation of Survey Findings

Limitations of Study

Recommendations for future research
