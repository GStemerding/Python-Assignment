#Incentive Types and Response Rates
An empirical experiment on the effect of different types of incentives on survey response rates and effort
* Gopala Stemerding 
* Joeri Verlinden 601536

**Assignment for Python course Applied Econonomic Analysis 1.**

##Research Question##
Do Response rates differ by using different types of incentives?

## _Motivation_
Surveys are an important method for firms of acquiring information on their customers. This information can for instance be used to improve their current products in such a way that the demands of their customers are more precisely met. In this paper four incentive types are discussed and compared on their effectiveness in increasing survey response rates. These incentive types are conditional and unconditional incentives, large uncertain payments and small certain payments. Since it has been documented that offering an incentive in the first place increases response rates (Willimack et al. 1995) a group receiving no incentives is excluded in this paper. A first look at existing literature on the incentive types shows that according to an experiment by [Castiglioni, Pforr & Krieger (2008)](https://ojs.ub.uni-konstanz.de/srm/article/view/599/2137) response rates in panel data are higher when unconditional incentives are used compared to incentives that are conditional on the respondent filling in the survey first. On a side note, [Singer et al (1999)](http://www.jos.nu/Articles/article.asp) found that monetary incentives are more effective than non-monetary incentives in increasing response rates, which is also discussed following our results. However on the trade-off between large uncertain and small certain payments there is little literature to be found. Therefore this paper discusses our experiment where we investigate the four different incentive types and their effect on response rates and the amount of effort exerted in filling in a survey. It is often important to know the level of effort exerted by the respondents because if a firm is using open-questions for example more effort will most likely increase the value of an answer.Since it is often conventional to survey respondents only once our experiment compares conditional and unconditional incentive types over a set of independent subjects rather than using a panel as in the experiment of Castiglioni et al.   

## _Method_
Our experiment was conducted in the form of a randomized controlled field experiment aiming to discover if an unconditional incentive is better than a conditional one and if a small certain payment is better than a large uncertain payment for increasing response rates and effort levels. Each respondent was only asked once such that four independent treatment groups are formed. We constructed a questionnaire consisiting of questions about the opinions of certain facilities of the University of Tilburg, which was purposely entirely unrelated to the purpose of the experiment as to prevent it from affecting the outcomes. The level of effort was measured by the amount of words respondents used in answering all open questions. To eliminate selection bias all our respondents were students at computers in the library of Tilburg University. Furthermore the same interviewer was used for all four groups and all respondents of all groups were asked at the same time of day.

As already noted we use four different independent groups in our experiment. Group A represented the small certain payment group where we asked respondents if they wanted to fill in our survey for 50 eurocents. Group B represented the large uncertain payment group where we asked the respondents if they wanted to fill in the survey for a small chance (2,5%) at winning 20 euro's, equalling in expected value the 50 cents. Group C represented the conditional incentive group as we asked the respondents if they wanted to fill in our survey for a chocolate letter. Group D represented the unconditional group who were asked if they wanted a chocolate letter and only afterwards, regardless their answer, were asked if they wanted to fill in our survey. 


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

