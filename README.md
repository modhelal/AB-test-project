# AB-test-project
## project oveview
#### Hypothesis testing is a valuable method to take a decision regarding two possiblities. in This project we will apply AB test concept to take a descision regarding the usage of old web page or new web page taking in consideration the conversion rate of them. Regression also, is applyed to detect relations between conversion and other recorded elements.

##  Project was divided into Three Parts:
### - ***Part one - Probability***
#### Statistics were computed to find out the probabilities of converting regardless of page. These were used to analyze if one page or the other led to more conversions.

### - ***Part two - A/B Test***
#### Next, hypothesis testing was conducted assuming the old page is better unless the new page proves to be definitely better at a Type I error rate of 5%. The data was bootstrapped and sampling distributions were determined for both pages. Conclusions were drawn on conversions for both pages by calculating p-values.

### - ***Part three - Regression***
#### Logistic regression was then performed to confirm results of the previous steps.
## Findings
#### According to actions done throug the analysis, we fail to reject the null hypothesis and found there is no difference in conversion rate between od and new pages,we find also according to regression results that As a final conclousion we can say that ab page and Country have no significane impact on page conversion, in addition, although it seems the conversion is similar for old and new pages, old page has a lead for conversion over the new page.

## USed programmes and libraries to be installed:
- Python
- Jupyter NoteBook
- Pandas
- NumPy
- Matplotlib
- sklearn
- statsmodels
