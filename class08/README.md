## 500 Class 08: 2025-03-06

Class 8 is divided into two parts.

### Part 1 is a recorded lecture you should watch before 10 AM on Thursday 2025-03-06.

- Slides for the recorded lecture 8 are [available in PDF](https://github.com/THOMASELOVE/500-slides-2025/blob/main/500_slides08r.pdf) (click on the down arrow to download) and [as Quarto (.qmd) code](https://github.com/THOMASELOVE/500-slides-2025/blob/main/500_slides08r.qmd).
- A link to the recording is available on our Shared Drive.

### Part 2 is a Zoom meeting on Thursday 2025-03-06 from **10-11 AM** Eastern Time. 

- Zoom information has been sent (via email to your CWRU account) to all registered students, and is also available on [Canvas](https://canvas.case.edu).
- Slides for this Zoom meeting are [available in PDF](https://github.com/THOMASELOVE/500-slides-2025/blob/main/500_slides08z.pdf) and [as Quarto (.qmd) code](https://github.com/THOMASELOVE/500-slides-2025/blob/main/500_slides08z.qmd).
- A link to the recording will be posted [to Canvas](https://canvas.case.edu/) within 24 hours of the meeting.
- The reference I put in the chat was <https://matheusfacure.github.io/python-causality-handbook/16-Regression-Discontinuity-Design.html>.

----

## Agenda

The agenda for the recording:

- Instrumental Variables
    - Whitehouse (2007) [Is an Economist Qualified to Solve Puzzle of Autism?](https://github.com/THOMASELOVE/500-sources/blob/main/articles/Whitehouse%202007%20WSJ%20Economics%20and%20Autism.pdf)
    - Rosenbaum (2010) [The Design of Observational Studies](https://github.com/THOMASELOVE/500-sources/blob/main/articles/Rosenbaum%20PR%202010%20Design%20of%20Observational%20Studies.pdf)
    - Posner (2001) [Comparing Standard Regression, Propensity Score Matching, and Instrumental Variables Methods for Determining the Influence of Mammography on Stage of Diagnosis](https://github.com/THOMASELOVE/500-sources/blob/main/articles/Posner%20et%20al%202001%20Comparing%20Methods%20in%20a%20Mammography%20Study.pdf)
- Comparing Propensity Scores and Instrumental Variables
    - Landrum and Ayanian (2001) [Causal Effect of Ambulatory Specialty Care on Mortality Following Myocardial Infarction](https://github.com/THOMASELOVE/500-sources/blob/main/articles/Landrum%20and%20Ayanian%202001%20Propensity%20Scores%20and%20Instrumental%20Variables.pdf) 

Agenda for today's Zoom session:

- Announcements and Reminders, including the Project Presentation Schedule
- Lab 3 answer sketch
- Presentations (2-3 minutes each) of the remaining five Project Proposals, draft 2
    - The proposals and slides are [linked here](https://thomaselove.github.io/500-proj-draft2-slides/).
- Tanenbaum (2017) [Propensity Matched Analysis of Outcomes and Hospital Charges for Anterior versus Posterior Cervical Fusion for Cervical
Spondylotic Myelopathy](https://github.com/THOMASELOVE/500-sources/blob/main/articles/Tanenbaum_2017_extra.pdf)
- Discussion of Rosenbaum **Causal Inference** Chapters 6 (Quasi-Experimental Designs) and 7 (Natural Experiments, Discontinuities, and Instruments)

## Announcements

1. Remember that we do not have class on Thursday 2025-03-13, due to Spring Break.
    - I will be away and not responding to email from 2025-03-07 through 2025-03-14.
    - Spring Break is an excellent time to work on your OSIA presentation, and get going on the remaining elements of the Project.
2. To register (deadline is 2025-03-12!) or learn more about the Joint Biostatistics Symposium to be held on 2025-04-07 from 10:30 AM to 4 PM at CWRU, visit <https://case.edu/medicine/pqhs/node/3455>. Jeff Leek is the [keynote speaker](https://bioscinema.github.io/biostatsymposium/#keynote-speaker).
3. Lab 4 is due to Canvas at **8 AM** on Thursday 2025-03-20.
4. The latest version of RStudio (ver 2024.12.1+563) is [available now](https://posit.co/download/rstudio-desktop/) and should be safe for you to download and use. The latest version of R, version 4.4.3, is [also now available](https://cran.case.edu/). I encourage you to upgrade to these over Spring Break. Either version 4.4.2 or 4.4.3 of R is OK for 500 work for the rest of this semester.

## After Spring Break (and our next class, Class 9, IN PERSON!)

1. Our next class, Class 9, will be our first **in-person** class. We will start at **9:05 AM** and run until 11:15 AM in Wolstein Research Building, room 1217. Parking is *always* an issue near the CWRU Campus. Leave time to get to class by 9, if at all possible.
    - For directions and parking information, [visit this link](https://case.edu/medicine/cbhi/about-us/directions-and-parking/cwru-school-medicine-health-sciences-campus).
    - Classes 9-11 will not be broadcast on Zoom. I will try to record them.
    - Classes 12-14 will neither be broadcast nor recorded, since that causes problems with project presentations. Sorry.
2. At Class 9, our main activity will be the [first few OSIA presentations](https://github.com/THOMASELOVE/500-classes-2025/tree/main/osia). We will also discuss Lab 4, Rosenbaum through Chapter 8, and perhaps look at [Elbadawi (2021)](https://github.com/THOMASELOVE/500-sources/blob/main/articles/Elbadawi%202021.pdf) and this [Supplement for Elbadawi 2021](https://github.com/THOMASELOVE/500-sources/blob/main/articles/Elbadawi%202021_supplement.pdf).
3. The OSIA schedule for Class 9 includes Katie, Ajay, Trisha and Dana as first readers, then JiaWei, Tatchaporn, Sarah and Logan as second readers.
    - First readers (Katie, Ajay, Trisha and Dana): Submit final versions of the slides for your class presentation (18 slides should be a reasonable maximum) to our Shared Google Drive **by 1 PM** on the day before your presentation, so **Wednesday 2025-03-19**. The file name should include your name. The folder you want in our Shared Drive is called **OSIA Slides for First and Second Readers on 2025-03-20 (Class 9)**.
    - Second readers (JiaWei, Tatchaporn, Sarah and Logan): Submit final versions of your 2-4 slides for your presentation to our Shared Google Drive **by 7:30 AM** on the day of your presentation, so **Thursday 2025-03-20**. Be sure the file name includes your name. We expect you to have reviewed the slides prepared by the First Reader (posted the day before) in preparing your materials. The folder you want in our Shared Drive is called **OSIA Slides for First and Second Readers on 2025-03-20 (Class 9)**.
    - The complete schedule for OSIA presentations is on [the Course Calendar](https://thomaselove.github.io/500-2025/calendar.html), and [also here](https://github.com/THOMASELOVE/500-classes-2025/tree/main/osia).

-------

## Key Ideas from Rosenbaum, Chapter 6 (from postscript)

> Sensitivity analysis addresses small pre-treatment differences that we cannot see, but of course the differences might be large, not small. Perhaps large differences that we cannot see leave behind visible traces that we can see. An invisible mouse may pass unnotices, where an invisible elephant leaves a path of wreckage. Quasi-experimental devices, such as multiple control groups, are tools for discovering large unmeasured pre-treatment differences between treated and control groups when such differences are present.

## Key Ideas from Rosenbaum, Chapter 7 (from postscript)

> Random assignment of treatments is sometimes unethical or infeasible, but bits of randomness enter every life, altering its course. Natural experiments, discontinuities, and instruments are attempts to cull bits of natural randomness for constructive use in an observational study.

-----

## Project Presentation Schedule

Here's what I've come up with. Let me know via email if there are any problems. The complete schedule for project presentations is also on [the Course Calendar](https://thomaselove.github.io/500-2025/calendar.html)

- **Class 12**: **2025-04-10** between 9 AM and 11:15 AM
    - Ajay Mahenthiran "[Limited Choices, Higher Risks: How Food Access Shapes Diabetes Prevalence](https://thomaselove.github.io/500-proj-draft2-slides/slides/ajay_draft2.html)"
    - JiaWei Yu "[The Impact of Time Lived in the United States on Adult Food Security](https://thomaselove.github.io/500-proj-draft2-slides/slides/jiawei_draft2.html)"
    - Logan Harper "[Glucocorticoid toxicity in a prospective international survey of sarcoidosis patients](https://thomaselove.github.io/500-proj-draft2-slides/slides/logan_draft2.html)"
    - Catherine Hassett "[Impact of Antihypertensive Therapy on Hematoma Expansion in Intracerebral Hemorrhage](https://thomaselove.github.io/500-proj-draft2-slides/slides/katie_draft2.html)"
- **Class 13**: **2025-04-17** between 9 AM and 11:15 AM
    - Trisha Lal "[Preventable Hospitalizations in Rural and Non-Rural Counties in the Midwest Based on 2024 County Health Rankings](https://thomaselove.github.io/500-proj-draft2-slides/slides/trisha_draft2.html)"
    - Tatchaporn Ongphichetmetha "[Impact of Non-Adherence to Inhaled Corticosteroids on Asthma Control in Adult Patients](https://thomaselove.github.io/500-proj-draft2-slides/slides/tatchaporn_draft2.html)"
    - Anika Krishna "[Framing Mental Illness: Racial Disparities in Police Killings](https://thomaselove.github.io/500-proj-draft2-slides/slides/anika_draft2.html)"
    - Olivia Lindberg "[Substance Use and Social Development in Young Adults](https://thomaselove.github.io/500-proj-draft2-slides/slides/olivia_draft2.html)"
- **Class 14**: **2025-04-24** between 9 and 11:15 AM
    - Sarah Albalawi "[Dental Ratio: A Key to Reducing Adult Smoking and Excessive Drinking in US Counties](https://thomaselove.github.io/500-proj-draft2-slides/slides/sarah_draft2.html)"
    - Dana Jian "[Examining Mental Health Burden Among Foreign and U.S. Born Adults: Nativity Status and Depression Outcomes](https://thomaselove.github.io/500-proj-draft2-slides/slides/dana_draft2.html)"
    - Kelly Bowen "[Effect of Metformin on Liver Health in a Sample of Patients with Diabetes](https://thomaselove.github.io/500-proj-draft2-slides/slides/kelly_draft2.html)"
