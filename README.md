# Computational Physics: Exam #1

This repository contains a jupyter notebook with an exploratory data analysis (EDA) of a set of data with information from 200k chess games played in the platform [lichess.org](lichess.org) during May 2019. The [dataset](https://web.chessdigits.com/data), ready for analysis, has both numerical and categorical variates such as elo and eco opening, respectively. The specifics of the dataset can be checked loading the ```modified_datset``` file.

![Lichess logo](https://upload.wikimedia.org/wikipedia/commons/a/af/Landscape-Lichess-logo.jpg)

The main objective of this EDA was to determine the statistical relations between many of the variates in order to establish whether the dataset is suitable for machine learning (ML) or not. Furthermore, the size of the dataset permitted the execution of more precise hypothesis testing meaning that, overall, many of the tests resulted in p-values below the established threshold. In that sense, data visualization techniques provided greater insight to determine if the statistical significance predicted by the tests was relevant.

## Remarks

1. The tests include: two goodness of fit tests, KS and $\chi^2$; three analysis of variance tests (ANOVA), for checking differences among the means of certain groups; two statistical independence tests, $\chi^2$; and one A/B test, a binomial test.
2. All the tests where done using ```scipy.stats``` module functionality.
3. The notebook has a plethora of graphs for regular frequency visualization.
4. The authors' take full responsibility for any unnoticed mistakes.

### License

The code here can be used according to CC BY-NC 4.0 License.
