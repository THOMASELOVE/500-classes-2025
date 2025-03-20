## 500 Class 09: 2025-03-20

Class 9 will be given **in person** starting at 9:05 AM and continuing through 11:15 AM in room 1217 in the Wolstein Research Building ([directions](https://case.edu/medicine/neurology/research/behavioral-health-research-group/directions-wolstein-research-building))

Class | Date | Slides (pdf) | Code (.qmd) | Recording
:----: | :-----: | :-----------: | :--------: | :--------------:
9 | 2025-03-20 | [Class 9 Slides](https://github.com/THOMASELOVE/500-slides-2025/blob/main/500_slides09.pdf) | [Class 9 Code](https://github.com/THOMASELOVE/500-slides-2025/blob/main/500_slides09.qmd) | See the Zoom folder on [Canvas](https://canvas.case.edu/)

## Today's Agenda

1. Introduction (first class in person)
2. Observational Studies in Action - schedule below and [here](https://github.com/THOMASELOVE/500-classes-2025/tree/main/osia).
3. Discussion of Lab 4 - the sketch for Lab 4 is posted to our Shared Drive.
4. Discussion of Rosenbaum **Causal Inference** through Chapter 8 (Replication, Resolution and Evidence Factors)
5. Some Key Takeaways from Elbadawi 2021 [Contemporary Revascularization Strategies and Outcomes Among Patients With Diabetes With Critical Limb Ischemia](https://github.com/THOMASELOVE/500-sources/blob/main/articles/Elbadawi%202021.pdf) with [Supplement](https://github.com/THOMASELOVE/500-sources/blob/main/articles/Elbadawi%202021_supplement.pdf): Insights from the National Inpatient Sample. *JACC: Cardiovascular Interventions*, 14(6): 664-74. doi:10.1016/j.jcin.2020.11.032
    - I'm sharing this paper because it's claims data, it's done in R, and it has actual Love plots in the supplement!
    - It also shows how you might think about looking at multiple outcomes, and does two separate PS analyses to compare 1 vs, 2 and 3 and then 2 vs. 3 when there are three exposures of interest.
    - The paper helps us to think about tradeoffs between mortality and length of stay as outcomes, and it uses the National Inpatient Sample, which is worth knowing something about.
    - But there's also some unexplained stuff - like why no insurance data, and why the matched samples aren't the same size, without specifying why this is the case (one assumes they are matching with replacement, but it's not specified).
    - Thanks to recent student Sameer Prasada for drawing my attention to this paper.
6. The latest version of RStudio (ver 2024.12.1+563) is [available now](https://posit.co/download/rstudio-desktop/) and should be safe for you to download and use. The latest version of R, version 4.4.3, is [also now available](https://cran.case.edu/). I encouraged you to upgrade to these over Spring Break, but if you haven't gotten to it yet, now is the time. Either version 4.4.2 or 4.4.3 of R is OK for 500 work for the rest of this semester.

## OSIA Presentations to be given in Class 9 (2025-03-20)

First Reader | Second Reader | Paper
:---------------------: | :------------: |  :----------------------------------------------------------------------------------------------------
Katie Hassett | JiaWei Yu | Beauchat et al. 2025 [Association of early general anesthesia with outcome in adults with status epilepticus: A propensity-matched observational study](pdfs/Beauchat_2025.pdf) *Epilepsia* 66:e7–e13. doi:10.1111/epi.18203
Trisha Lal | Sarah Albalawi | Mackay et al. 2022 [The impact of cancer treatment on quality of life in patients with pancreatic and periampullary cancer: a propensity score matched analysis](pdfs/Mackay_2022.pdf) with [Supplement](pdfs/Mackay_2022_supplement.pdf) *HPB* 24: 443–451. doi:10.1016/j.hpb.2021.09.003
Dana Jian | Logan Harper | Zhang et al. 2025 [Sedentary Behavior and Its Association With Psychological Well-Being and Sleep Quality in Adolescents: Evidence from a Propensity Score Analysis](pdfs/Zhang_2025.pdf) with [Supplement](pdfs/Zhang_2025_supplement.pdf) *Psychology Research and Behavior Management* 18: 281-298, doi:10.2147/PRBM.S508382 

## Key Ideas from Rosenbaum, Chapter 8 (from postscript)

> Replication is central to science, but it is easy to use the same procedures to repeat the same mistakes. A series of observational studies may reach firmer conclusions than any one study in that series, providing successive studies are liable to different mistakes, not to repeating the same one. Evidence factors seek such replication within a single study through carefully varied comparisons.

## References in Today's Slides (after Rosenbaum discussion)

- [Replication and Replicability in Science](https://www.ncbi.nlm.nih.gov/books/NBK547524/) from the National Academies of Sciences, Engineering, and Medicine.
- Nosek B and Errington TM [What is replication?](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7100931/)
- Moreau D and Wiebels K [Ten simple rules for designing and conducting undergraduate replication projects](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10019630/)
- Royal Society Open Science [Replication Studies: Guidance for Authors and for Referees and Reviewers](https://royalsocietypublishing.org/rsos/replication-studies)
- Wikipedia on the [Replication Crisis](https://en.wikipedia.org/wiki/Replication_crisis)
- Ioannidis JPA 2005 [Why Most Published Research Findings are False](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC1182327/)
- Peng RD and Hicks SC 2021 [Reproducible Research: A Retrospective](https://www.annualreviews.org/doi/abs/10.1146/annurev-publhealth-012420-105110) *Annual Review of Public Health*
- Wikipedia on [Bayes factor](https://en.wikipedia.org/wiki/Bayes_factor)
- The [BayesFactor package](https://cran.r-project.org/web/packages/BayesFactor/vignettes/manual.html) in R
- Stefan et al. 2019  [A tutorial on Bayes Factor Design Analysis using an informed prior](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6538819), doi: 10.3758/s13428-018-01189-8

## Reminders for Next Week

1. The [Project Update](https://thomaselove.github.io/500-2025/proj500.html#the-project-update) is due to Canvas at 9 AM on Wednesday 2025-03-26.
2. The OSIA schedule for Class 10 includes Olivia, Tatchaporn and Kelly as first readers, then Anika, Katie and Dana as second readers.
    - First readers (Olivia, Tatchaporn and Kelly): Submit final versions of the slides for your class presentation (18 slides should be a reasonable maximum) to our Shared Google Drive **by 1 PM** on the day before your presentation, so **Wednesday 2025-03-26**. The file name should include your name. The folder you want in our Shared Drive is called **OSIA Slides for First and Second Readers on 2025-03-27 (Class 10)**.
    - Second readers (JiaWei, Tatchaporn, Sarah and Logan): Submit final versions of your 2-4 slides for your presentation to our Shared Google Drive **by 7:30 AM** on the day of your presentation, so **Thursday 2025-03-27**. Be sure the file name includes your name. We expect you to have reviewed the slides prepared by the First Reader (posted the day before) in preparing your materials. The folder you want in our Shared Drive is called **OSIA Slides for First and Second Readers on 2025-03-27 (Class 10)**.
3. For next week, complete reading Rosenbaum **Causal Inference** through Chapter 9 (Uncertainty and Complexity in Causal Inference)
4. Skim Posner et al. 2001 [Comparing Standard Regression, Propensity Score Matching, and Instrumental Variables Methods for Determining the Influence of Mammography on Stage of Diagnosis](https://github.com/THOMASELOVE/500-sources/blob/main/articles/Posner%20et%20al%202001%20Comparing%20Methods%20in%20a%20Mammography%20Study.pdf) *Health Services & Outcomes Research Methodology*, 2: 279-290. doi:10.1023/A:1020323429121
