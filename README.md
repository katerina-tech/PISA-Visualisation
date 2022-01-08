<p align="center">
  <a href="https://www.udacity.com/">
    <img src='https://course_report_production.s3.amazonaws.com/rich/rich_files/rich_files/5511/s300/udacity-logo.png' alt="Udacity logo" width = 100px>
   </a>
</p>
<h3 align="center"><a href='https://www.udacity.com/course/data-analyst-nanodegree--nd002'> Udacity Data Analyst Degree </a></h3>
<h4 align="center">  Project 5: Exploring Studying Factors from PISA2012 </h4>

## Table of Contents
- [Overview](#over)
- [Summary of Findings](#summary)
- [Project Instructions](#pi)
- [Results](#results)

### Overview <a name="over"></a>

PISA is a survey of students' skills and knowledge as they approach the end of compulsory education. This survey examines:
 - how well students have learned the school curriculum,
 - how well prepared they are for life beyond school etc.

I set out to understand what factors, like: wealth, country of residence, gender, programming skills,
etc. can be used from a dataset to predict student performance.
The factors I decided to focus on were:
- 'CNT' Country
- 'LNT' Language
- 'ST04Q01' Gender
-'IMMIG' Immigration Status
- Score is PV…MATH (Mathematik), PV…READ (Reading), PV…SCIE (Sciense)
- 'HISCED' Parents Highest Education
- ‘Wealth’ or Family wealth.
- 'Mother Job' and 'Mother at Home'
- And Programming skills

### Summary of Finings <a name="summary"></a>

In this Project we made univariate, bivariate and multivariate Exploration of data.

### Discuss the distribution(s) of your variable(s) of interest. Were there any unusual points? Did you need to perform any transformations?

> Most of parents have upper secondary education level and 32,9% of parents have at least Bachelor degree. Distribution Wealth of Families loooks like normal distribution, 
but we can that there is more poorer( less then mean) families. Unususual point in this distribution for me that exist a gap between very wealth families and less wealthy.
Most students are native to their country of residence. And less than 30K students are in the first or second generation of immigrants. First and second generation immigrants are equivalently reprensented in the dataset
Reading Mean is obviously higher then Science and Mathematik Mean
Most of Students for this research have Mexico, Italy and Spain residense And least number of students from Liechtenstein, 1 city of Russia and individual states of USA. So we need to merge individual states and citys to the coutries, then our data will be consistenter.

There is a lot of interesting correlations between mother job status and math scores. When mother at home notes in math is significantly higher (approximately on 30 points) then by them whose mother is working.
Absolutely signifficant,that je higher degree of parents then higher the note schoolchildren in this 3 disciplines.
Most of kids is not programming at home, but most of them who programming boys and geeks guys (who programming always) approximately in three times more then girls.

Girl in all countries have better notes in reading then boys. In Mathematic this difference is not so obviosly and in most of countries they have better notes. Just in some countries like Jordan, Thailand and Quatar. 
Important to notice that in these countries Mathematic score are at the end of the list of all countries. The Leaders is China, Singapore, Korea.

### Of the features you investigated, were there any unusual distributions? Did you perform any operations on the data to tidy, adjust, or change the form of the data? If so, why did you do this?

> Unususual point in the wealth distribution for me that exist a gap between very wealth families and less wealthy families
I was surprised, that by uneployed (looking for a job) mothers scores of their childs is lower then by full-time working mothes. 
Also interesting that immigration status have not signifficant impact on the notes.
Note difference in reading is so big, but in mathematic it is not so obvios. Bytheway i was surprised that, 
when mother not at home with her son than his reading notes signifficant lower then by other group.

