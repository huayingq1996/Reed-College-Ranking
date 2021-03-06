# A True Lie about Reed College: U.S News Ranking
![](img/2019pcrPI_1.png)
The above graph is the result generated by a PCR model to predict Reed College's overall score used by U.S. News & Worlds Report (USNWR) in  their Best College Ranking. If I tell you the vertical bars are prediction intervals, would you be shocked by the result? I certainly was when I first got to this result. This graph is a sneak peek of an course project of MATH343 *Statistical Practicum* at Reed College. Our group were tasked to help the Reed College's Office of Institutional Research investigate if non-reporting schools are under-ranked by USNWR in their Best College Ranking. To put it in a nutshell, this research used Principal Component Regression and Elastic Net Regularized Regression methods to build predictive models, aiming to reproduce the USNWR College Rankings published in 2009 and 2019 and assess if non-reporting schools are truly under-ranked. The current result we have suggests that there is no systematic under-ranking for non-reporting schools. Reed College was shown to be the only institution that is significantly under-ranked by USNWR both in 2009 and 2019.
The following is a table presenting the predicted overall score of Reed College and the corresponding ranks, compared with the those given by USNWR:
</br>

Source | 2009 Overall Score| 2019 Overall Score | 2009 Rank | 2019 Rank
-------|------|------ | ------ | ------
PCR    | 72   | 77 | 37 | 36
Elastic Net | 72 | 77 | 37 | 36
USNWR | 65 | 60 | 54 | 77


 </br>

Unfortunately, due to confidentiality, we can't share the datasets on this repo. For more details on the project, **PLEASE READ THE FINAL REPORT IN THE REPO**.
