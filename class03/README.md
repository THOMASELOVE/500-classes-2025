## 500 Class 03: 2025-01-30

Class 3 is divided into two parts.

### Part 1 is a recorded lecture you should watch before 10 AM on Thursday 2025-01-30.

- Slides for the recorded lecture 3 are [available in PDF](https://github.com/THOMASELOVE/500-slides-2025/blob/main/500_slides03r.pdf) (click on the down arrow to download) and [as Quarto (.qmd) code](https://github.com/THOMASELOVE/500-slides-2025/blob/main/500_slides03r.qmd).
- A link to the recording will be posted by Friday 2025-01-24.

### Part 2 is a Zoom meeting on Thursday 2025-01-30 from **10-11 AM** Eastern Time. 

- Zoom information has been sent (via email to your CWRU account) to all registered students, and is also available on [Canvas](https://canvas.case.edu).
- Slides for this Zoom meeting are [available in PDF](https://github.com/THOMASELOVE/500-slides-2025/blob/main/500_slides03z.pdf) and [as Quarto (.qmd) code](https://github.com/THOMASELOVE/500-slides-2025/blob/main/500_slides03z.qmd).
- A link to the recording will be posted [to Canvas](https://canvas.case.edu/) within 24 hours of the meeting.

----

## Class 3 Agenda (for the Recorded Lecture and Zoom Call)

1. Estimating the Propensity Score (Building the Propensity Model)
2. A schematic for propensity matching in a “simple” study
3. Mechanics of Propensity Matching
4. Schematics for other Propensity Methods in “simple” studies
5. An Introduction to The SUPPORT / Right Heart Catheterization Study
6. Lab 1 (How did it go?)
    - The Answer Sketch for Lab 1 is now available on our Shared Google Drive.
7. Rosenbaum Chapter 4

## Announcements

1. The [Lab 1](https://thomaselove.github.io/500-2025/lab1.html) answer sketch is posted to our Shared Google Drive. Thanks to everyone for submitting it on time. I really appreciate that. Grades and a little bit of feedback are going up on Canvas, as I finish reviewing each one.
    - You want to be using R version 4.4.2. Our [Software page](https://thomaselove.github.io/500-2025/software.html) has more instructions.
    - I didn't load [the `easystats` framework](https://easystats.github.io/easystats/) in my sketch for Lab 1. It's a perfectly reasonable thing to do, though, and if you're unfamiliar with it, it's worth learning about. The [431 Book](https://thomaselove.github.io/431-book/) has a lot of details.

## References from Today's Class

References posted on our [Sources page](https://github.com/THOMASELOVE/500-classes-2023/tree/main/sources)

- D'Agostino Ralph B Jr. 1998 [Tutorial in Biostatistics: Propensity Score Methods for Bias Reduction in the Comparison of a Treatment to a Non-Randomized Control Group](https://github.com/THOMASELOVE/500-classes-2023/tree/main/sources/articles/D'Agostino%201998%20SIM%20Tutorial%20on%20Propensity%20Scores.pdf) *Statistics in Medicine*
- Connors Alfred F et al. 1996 [The Effectiveness of Right Heart Catheterization in the Initial Care of Critically Ill Patients](https://github.com/THOMASELOVE/500-classes-2023/tree/main/sources/articles/articles/Connors%20et%20al%201996%20JAMA%20The%20Right%20Heart%20Catheterization%20Study.pdf) *Journal of the American 
- Gum Patricia A Thamailarasan Maran Watanabe Junko et al. 2001 [Aspirin Use and All-Cause Mortality among Patients being Evaluated for Known or Suspected Coronary Artery Disease](https://github.com/THOMASELOVE/500-classes-2023/tree/main/sources/articles/Gum%202001%20JAMA%20Aspirin%20Use%20Propensity%20Analysis.pdf) *JAMA* 2001 286(10): 1187-1194.
- Hirano Keisuke and Imbens Guido W 2001 [Estimation of Causal Effects using Propensity Score Weighting: An Application to Data on Right Heart Catheterization](https://github.com/THOMASELOVE/500-classes-2023/tree/main/sources/articles/Hirano%20and%20Imbens%202001%20Weighting%20in%20RHC.pdf) *Health Services & Outcomes Research Methodology*
- Hirano Keisuke, Imbens Guido W. and Ridder Geert 2003 [Efficient Estimation of Average Treatment Effects Using the Estimated Propensity Score](https://github.com/THOMASELOVE/500-classes-2023/tree/main/sources/articles/Hirano%20Imbens%20Ridder%20Efficient%20Estimation%20of%20ATE.pdf) *Econometrica* 2003, 71(4): 1161-1189. https://doi.org/10.1111/1468-0262.00442.
- Rosenbaum Paul E 2010 [Design of Observational Studies](https://github.com/THOMASELOVE/500-classes-2023/tree/main/sources/articles/Rosenbaum%20PR%202010%20Design%20of%20Observational%20Studies.pdf)
- Rosenbaum Paul E Rubin Donald B 1983 [The Central Role of the Propensity Score in Observational Studies for Causal Effects](https://github.com/THOMASELOVE/500-classes-2023/tree/main/sources/articles/Rosenbaum%20and%20Rubin%201983.pdf) *Biometrika* 1983: 70(1); 41-55.
- Rosenbaum Paul E Rubin Donald B 1984 [Reducing Bias in Observational Studies Using Subclassification on the Propensity Score](https://github.com/THOMASELOVE/500-classes-2023/tree/main/sources/articles/Rosenbaum%20and%20Rubin%201984%20JASA.pdf) *JASA* 1984: 79(387): 516-524.
- Rosenbaum Paul E Rubin Donald B 1985 [Constructing a Control Group Using Multivariate Matched Sampling Methods That Incorporate the Propensity Score](https://github.com/THOMASELOVE/500-classes-2023/tree/main/sources/articles/Rosenbaum%20and%20Rubin%201985.pdf) *The American Statistician* 1985: 39(1): 33-38.
- Rubin Donald B 2001 [Using Propensity Scores to help Design Observational Studies: Application to the Tobacco Litigation](https://github.com/THOMASELOVE/500-classes-2023/tree/main/sources/articles/Rubin%202001%20Tobacco%20Litigation%20article.pdf) *Health Services & Outcomes Research Methodology*
- Rubin Donald B 2004 [On principles for modeling propensity scores in medical research](https://github.com/THOMASELOVE/500-classes-2023/tree/main/sources/articles/Rubin%202004%20editorial%20Pharmacoepidemiology%20and%20Drug%20Safety%20on%20Propensity%20Score%20Principles.pdf) *Pharmacoepidemiology and Drug Safety*
- Weitzen Sherry et al. 2004 [Principles for modeling propensity scores in medical research: A systematic literature review](https://github.com/THOMASELOVE/500-classes-2023/tree/main/sources/articles/Weitzen%20et%20al%202004%20Systematic%20Literature%20Review%20of%20Propensity%20Score%20Usage.pdf) *Pharmacoepidemiology and Drug Safety*
- Weitzen Sherry et al. 2005 [Weaknesses of goodness-of-fit tests for evaluating propensity score models: the case of the omitted confounder](https://github.com/THOMASELOVE/500-classes-2023/tree/main/sources/articles/Weitzen%20et%20al%202005%20Why%20goodness%20of%20fit%20tests%20aren't%20appropriate%20for%20evaluating%20propensity%20score%20models.pdf) *Pharmacoepidemiology and Drug Safety*

Other references in the slides, if you're interested in tracking down further details...

- Brookhart MA Schneeweiss S Rothman KJ Glynn RJ Avorn J Stürmer T Variable selection for propensity score models. *Am J Epidemiol* 2006 Jun 15;163(12):1149-56. doi: 10.1093/aje/kwj149. Epub 2006 Apr 19 [PubMed](https://pubmed.ncbi.nlm.nih.gov/16624967/)
- D'Agostino Jr. RB and Rubin DB Estimating and Using Propensity Scores with Partially Missing Data *JASA* 2000, 95(451): 749-759.
- McCaffrey DF Ridgeway G Morral AR Propensity score estimation with boosted regression for evaluating causal effects in observational studies. *Psychol Methods* 2004 Dec;9(4):403-25. doi: 10.1037/1082-989X.9.4.403. [PubMed](https://pubmed.ncbi.nlm.nih.gov/15598095/)
- Harrell FE *[Biostatistics for Biomedical Research](http://hbiostat.org/bbr/)*, specifically the [BBR Notes (pdf)](http://hbiostat.org/doc/bbr.pdf). 
- Lunceford JK and Davidian M 2004 Stratification and weighting via the propensity score in estimation of causal treatment effects: a comparative study. *Stat Med* 2004 Oct 15;23(19):2937-60. doi: 10.1002/sim.1903. [PubMed](https://pubmed.ncbi.nlm.nih.gov/15351954/).

----


## What Should I be working on?

1. Watch recorded Lecture 4. The link is posted to our Shared Drive now.
2. The [toy example](https://github.com/THOMASELOVE/500-data/tree/master/toy) is be the focus of the recorded Class 04.
3. We'll spend some time on Normand (2001) in the Zoom session for Class 4, so it would help to have looked at that in advance of class. It would also be nice if you skimmed  Austin and Mamdani (2006), and D'Agostino, Jr. (1998), which we'll probably discuss in Class 5. All three papers are found on our [Sources](https://github.com/THOMASELOVE/500-sources) page. 
4. Read Chapter 5 of Rosenbaum *Causal Inference*.
5. It's definitely not too early to start thinking about:
    - developing a [project proposal](https://thomaselove.github.io/500-2025/proj500.html) and identifying an available data set (initial draft due 2025-02-13)
    - claiming an [Observational Studies In Action](https://thomaselove.github.io/500-2025/osia.html) article (due 2025-02-19)
