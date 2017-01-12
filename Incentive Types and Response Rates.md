#Incentive Types and Response Rates
An empirical experiment on the effect of different types of incentives on survey response rates and effort
* Gopala Stemerding 
* Joeri Verlinden 601536

**Assignment for Python course Applied Econonomic Analysis 1.**

##Research Question##
Do Response rates differ by using different types of incentives?

## _Motivation_
Surveys are an important source for firms to discover information about consumers. This information can therefore be used to improve their current products in a way that the demands of these consumers will be fulfilled more efficiently. In this assignment the incentive types conditional, unconditional, large uncertain payments and small certain payments will be discussed. According to the experiment of [Castiglioni, Pforr & Krieger (2008)](https://ojs.ub.uni-konstanz.de/srm/article/view/599/2137) response rates in panel data will be higher when unconditional incentives are used than when conditional incentives are used. [Singer et al (1999)](http://www.jos.nu/Articles/article.asp) found that monetary incentives are more effective than non-monetary incentives in increasing response rates. However on the trade-off between large uncertain and small certain payments is little literature. Therefore we designed an experiment where we investigate the four different types and their effect on response rates. We wanted to combine also the conditional-unconditional trade-off in a one-shot way instead of panel data. Moreover it is important to know the level of effort exerted by the respondents because if a firm is using open-questions for example more effort will most likely increase the value of an answer. As we can see in the next section we also included a way to compare monetary incentives with non-monetary incentives in a one-shot way. 

## _Method_
We conducted a randomized controlled field experiment to discover if an unconditional gift is better than a conditional gift and if a small certain payment is better than a large uncertain payment in a one-shot way. We therefore created a questionnaire which consisted of questions about the opinions of certain facilities of the University of Tilburg. The level of effort was measured by counting the amount of words people used to give an answer on the open questions. To reduce selection bias all our respondents were students who were sitting behind a computer in the library of Tilburg University.

As already noted we use four different groups in our experiment. Group A represented the small certain payment group since we asked the respondents if they wanted to fill in our survey for 50 eurocents. Group B represented the large uncertain payment group because we asked the respondents if they wanted to fill in the survey for a chance (2,5%) of winning 20 euro's. Group C represented the conditional group since we asked the respondnets if they wanted to fill in our survey for a chocolate letter. Group D represented the unconditional group since we asked if they wanted a chocolate letter and afterwards, regardless their answer, we asked them if they wanted to fill in our survey. 

To reduce selection bias even further we maintained the same interviewer for every group. Moreover we made sure that no selection bias arised from different places or different days since we contact the control and treatment groups on the same day and based on the part of the library they were. 

## _Answer_
When comparing the conditional with the unconditional group we found, through a Fisher Exact Test a significant p-value of 0.048. This means that an unconditional incentive leads to a higher response rate than a conditional incentive in a one-shot way. Moreover we found that even if people did not want to have the 50 eurocents they still wanted to fill in the survey. This could be explained by the fact of positive reciprocity (misschien hier een paper gebruiken?). 

When comparing the small certain payments with the large uncertain payments we found no statistically significant effect. However when we divided the groups between men and women we found that there is a significantly difference in response rates for women when they receive a small certain payment. This can be explained by the fact that women are more risk averse [Dohmen et al (2005)](http://ftp.iza.org/dp1730.pdf). 

Finally when comparing effort between the groups we did not found a significant effect. However we did find that women exert significantly more effort into answering than men over all groups. 

Misschien hier paper dingen gebruiken? Hoe we het ook in het assignment hebben gedaan?

|   Version 2   | Niet ingevuld | Ingevuld       | Total      |     
| ------------  | :-----------: |-------------:  | ---------- |
| 0             | 1             | 39             | 12         |  
| 1             | 6             | 30             | 36         | 
 
(table of comparing conditional group with the unconditional group)

|   Version 2   | Obs           | Rank sum       | Expected   |     
| ------------- |:-------------:| --------------:| -----------
| 0             | 39            | 1210           | 1365       |  
| 1             | 30            | 1205           | 1050       | 
| combined      | 69            | 2415           | 2415       |

(table of measuring effort if their is any difference)

