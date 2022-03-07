# Baby-Birth-Weight-Analysis

Baby-Birth-Weight-Analysis is a project based on R, using statistical inference methods to produce an useful report on the factors that affect a baby's birth weight. 

The project started in October 2022 by Klaire Pham, Jason Phillip, and JoJo Summersett as the final assignment of Vassar's Introduction to Statistics course. 

---

For more information, feel free to read our [report](report.pdf).

## Idea
The idea is as follows:

- **Questions**: We are interested in the relationship between certain factors (including smoking habits, mother’s weight gain, etc) have on a baby’s birth weight. Generally, mothers are advised not to smoke tabacco during their pregnancy, so we want to ﬁnd out whether or not that advise is statistically sound. Diﬀerent studies have also shown the advantages of abstinence from cigarette smoking during pregnancy, thus, we also want to reproduce evidence to those claims.
- Is there a diﬀerence in average weights of babies birthed by smoking mothers and non-smoking mothers? Is there a diﬀerence in proportion of low-weight babies birthed by smoking mothers and non-smoking mothers? Does a mother’s smoking habits have an eﬀect on the baby’s birth weight?
- As we explore the answers to these questions, we decided to study the variability of the diﬀerence of the proportions of low weight babies with smoking moms and low weight babies for non-smoking moms through both simulation- and theory-based inference methods.
- **Preparing the dataset**: We sourced our dataset from the R OpenIntro package, BIRTHS14. The US Government runs a continous observational study recording information about the weight, demographic, sex, and other attributes of US babies and births. It is observational because there is no random assignment or treatment groups. Because of this, ﬁndings from this dataset can be generalized to the general population because it uses random sampling methods; however, it is not an experiment so the data cannot be used to establish a causal link.
- The US released a large dataset containing information on births recorded within the country in 2014, and the dataset cases represent 1,000 birth records, randomly sampled from the US Department of Health. We are interested in the birth weight classiﬁcation (low or not low) of babies (nominal, categorical) and if other variables, like smoking habits (nominal, categorical) and mother’s age (discrete, numerical), have a positive or negative eﬀect on it. We will at times also consider other variables such as the weight gained by mother (continuous, numerical).


## Folders/Files:

- **r-code**: This is the R mark-down file which implements the graphing and produces the report. 
- **report.pdf**: Report of this project. Read it to see our results and conclusions.

## Reproduce:
To download the data and reproduce the report:

1. Download the dataset from [OpenIntro](https://www.openintro.org/data/index.php?data=births14) and save them in the same folder as the r-code file. 
2. Run and knit the r-code file on RStudio.
	- **Note**: This will produce the same report as the file we include here. 
	
## Critical issues	
- Do not change the names of the data files, this could provoke problems in the code.

## Licensing
- There is no licence. 