## 500 Class 01: 2025-01-16

Class 1 is divided into two parts.

### Part 1 is a recorded lecture you should watch before 10 AM on Thursday 2025-01-16.

- Slides for the recorded lecture 1 are [available in PDF](https://github.com/THOMASELOVE/500-slides-2025/blob/main/500_slides01r.pdf) and [as Quarto (.qmd) code](https://github.com/THOMASELOVE/500-slides-2025/blob/main/500_slides01r.qmd).
- A link to the recording will be posted by Monday 2025-01-13.

### Part 2 is a Zoom meeting on Thursday 2025-01-16 from **10-11 AM** Eastern Time. 

- Zoom information has been sent (via email to your CWRU account) to all registered students.
- Slides for the first Zoom meeting are [available in PDF](https://github.com/THOMASELOVE/500-slides-2025/blob/main/500_slides01z.pdf) and [as Quarto (.qmd) code](https://github.com/THOMASELOVE/500-slides-2025/blob/main/500_slides01z.qmd).
- A link to the recording will be posted [to Canvas](https://canvas.case.edu/) within 24 hours of the meeting.

## What should I do to prepare BEFORE the first class session?

1. **Register for the course** through SIS. That will alert Dr. Love to get you set up to access the course materials.
2. Watch the recorded **Lecture 1** RCTs and Observational Studies; A Motivating Example when it becomes available in January.
3. **Buy the book**. During the course, we will read Paul Rosenbaum's book **Causal Inference**, which is available as an e-book or in paperback for under $15. Please buy the book and get started reading it as soon as you can. Ideally, you'd read through Chapter 2 before our first class.
4. Once you have registered for the course, please visit our [Welcome to 500 survey](https://bit.ly/500-welcome-2025) when it becomes available in January. You'll need to log into Google via CWRU to access the survey, which should take about 10 minutes to complete. Please complete the survey as soon as possible.
5. **Download the software**. Install R and RStudio and some necessary R packages on a computer you can control throughout the semester. Details [are available here](https://thomaselove.github.io/500-2025/software.html).
6. Read Benson and Hartz 2000 from [Sources](https://github.com/THOMASELOVE/500-sources)

---

## Welcome to 500!

- Instructor: Thomas E. Love, Ph.D., Professor of Medicine and of Population and Quantitative Health Sciences, CWRU.
- Email: **Thomas** dot **Love** at **case** dot **edu**.
- Office Hours: By appointment, after class, or via email. 
- Be sure you are registered with SIS for the course.

Need help? Contact me with your questions. We want to hear from you!

## Shared Google Drive

You should have access to the **500 Spring 2025 Dr. Love and Students** shared drive. Find it by logging into Google via CWRU and then visiting the Shared Drives section under Google Drive. Let us know if you have any problems accessing the Drive.

## References from Today's Class

Articles posted on our [Sources page](https://github.com/THOMASELOVE/500-sources)

- Concato John et al. 2000 [Randomized, Controlled Trials, Observational Studies and the Hierarchy of Research Designs](https://github.com/THOMASELOVE/500-classes-2023/blob/main/sources/articles/Concato%20Shah%20and%20Horwitz%202000%20OS%20vs%20RCTs%20and%20Hierarchy%20of%20Research%20Design.pdf) *New England Journal of Medicine*
- Gum Patricia A Thamailarasan Maran Watanabe Junko et al. 2001 [Aspirin Use and All-Cause Mortality among Patients being Evaluated for Known or Suspected Coronary Artery Disease](https://github.com/THOMASELOVE/500-classes-2023/blob/main/sources/articles/Gum%202001%20JAMA%20Aspirin%20Use%20Propensity%20Analysis.pdf) *JAMA* 2001 286(10): 1187-1194.
- Smith Gordon C S and Pell Jill P 2003 [Parachute use to prevent death and major trauma related to gravitational challenge: Systematic review of randomized controlled trials](https://github.com/THOMASELOVE/500-classes-2023/blob/main/sources/articles/Smith%20and%20Pell%202003%20BMJ%20Parachutes.pdf) *The BMJ*
- STROBE Guidelines are available at <https://www.strobe-statement.org/>.

You might be interested as well in [The Book of Why](http://bayes.cs.ucla.edu/WHY/) by Judea Pearl and Dana Mackenzie in 2018.

Other articles I refer to in the slides, if you're interested in tracking down further details...

- Multiple risk factor intervention trial. Risk factor changes and mortality results. Multiple Risk Factor Intervention Trial Research Group. *JAMA* 1982 Sep 24;248(12):1465-77. [PubMed](https://pubmed.ncbi.nlm.nih.gov/7050440/)
- [USPSTF Grade Definitions](https://www.uspreventiveservicestaskforce.org/Page/Name/grade-definitions) including links to definitions prior to July 2012.
- Veterans Administration Coronary Artery Bypass Surgery Cooperative Study Group. Eleven-year survival in the Veterans Administration randomized trial of coronary bypass surgery for stable angina. *N Engl J Med* 1984 Nov 22;311(21):1333-9. doi: 10.1056/NEJM198411223112102. [PubMed](https://pubmed.ncbi.nlm.nih.gov/6333636/)

## Learning about Quarto (and making the switch from R Markdown)

1. Virtually any code you have written in R Markdown can be run using Quarto instead, by simply switching the file extension from .Rmd to .qmd.
2. It's still worth it to learn about how Quarto works, and why it differs from R Markdown when it does.

Here are some suggestions:

- <https://quarto.org/> is the main website for all things Quarto, will help you get started making the transition, and has a detailed set of guides and references.
    - Here's the start of the [Tutorial, including Hello, Quarto](https://quarto.org/docs/get-started/hello/rstudio.html) that shows you how to use Quarto with RStudio, which is what you'll be doing in this class.
    - This [FAQ for R Markdown users](https://quarto.org/docs/faq/rmarkdown.html) might be a good starting point.
    - Alison Hill wrote a great blog post [We don't talk about Quarto](https://www.apreshill.com/blog/2022-04-we-dont-talk-about-quarto/) which got me started last April.
- [R for Data Science (2nd edition)](https://r4ds.hadley.nz/) has three chapters on [Communication](https://r4ds.hadley.nz/communicate.html) which include sections dedicated to Quarto, Quarto formats and a Quarto workflow.
- YouTube videos discussing Quarto that may be of interest to you include (in no special order):
    - From Tom Mock at Posit (new name of RStudio the company)
        - [Quarto for the Curious](https://www.youtube.com/watch?v=mrvhk2XUfWo) (runs 21 minutes)
        - [Welcome to Quarto workshop](https://www.youtube.com/watch?v=yvi5uXQMvu4) (2 hours 23 minutes)
        - [Beautiful Reports and Presentations with Quarto](https://www.youtube.com/watch?v=hbf7Ai3jnxY) (1 hour 45 minutes)
        - [Create & Publish a Quarto Blog on Quarto Pub in 100 Seconds](https://www.youtube.com/watch?v=t8qtcDyCRFA) (2 minutes).
        - [Reproducible Medical Research with Quarto](https://www.youtube.com/watch?v=KnwQFph3s94) (3 hours 15 minutes)
    - Isabella Velásquez: [Building a Blog with Quarto](https://www.youtube.com/watch?v=CVcvXfRyfE0) (1 hour 13 minutes)
    - Devin Pastoor: [Websites & Books & Blogs, oh my! Creating Rich Content with Quarto](https://www.youtube.com/watch?v=A9QRN4cpsDY) (21 minutes)
    - Frank Harrell: [R Workflow for Reproducible Biomedical Research using Quarto](https://www.youtube.com/watch?v=NCrrN3Al-kw) (1 hour, 2 minutes)
    - Lyndon Walker: [Create beautiful documents with Quarto and R](https://www.youtube.com/watch?v=y5VcxMOnj3M) (29 minutes)
    - Mine Çetinkaya-Rundel: [Hello, Quarto!](https://www.youtube.com/watch?v=YVa5cdkypbw)
    - Ted Laderas on [Quarto/R Markdown: What's Different?](https://www.youtube.com/watch?v=xC6I5OVOnKI) (28 minutes)

## Notes from the 431-432 Sequence

If you need them, the [431 Notes from Fall 2024 are here](https://thomaselove.github.io/431-book/), and the [432 Notes for Spring 2025 are here](https://thomaselove.github.io/432-notes/).

----

## What Should I Do Before Our Next Class?

1. Be sure you are registered with SIS for the course. 
2. Please complete our [Welcome to 500 survey](https://bit.ly/500-welcome-2025). You’ll need to log into Google via CWRU to access the survey, which should take about 10 minutes to complete. Please complete the survey as soon as possible, and thanks to those of you who've already done this.
3. Download the software. Install R and RStudio and some necessary R packages on a computer you can control throughout the semester. Details [are available here](https://thomaselove.github.io/500-2025/software.html).
4. Work through [Lab 0](https://thomaselove.github.io/500-2025/lab0.html). Note that there's nothing to turn in here. If you like, you could also get started on [Lab 1](https://thomaselove.github.io/500-2025/lab1.html) which is due on 2025-01-30.
5. Buy the book. During the course, we will read Paul Rosenbaum’s book **Causal Inference**, which is available as an e-book or in paperback for about $15. Please read through Chapter 3 before our next class on 2024-01-23, if you can.
6. Watch my second recorded lecture once it becomes available.
7. At least skim through the other things I've asked you to read in [the Course Calendar](https://thomaselove.github.io/500-2025/calendar.html).
8. Make sure you familiarize yourself with everything [on our website](https://thomaselove.github.io/500-2025/).

If you have questions, email me.
