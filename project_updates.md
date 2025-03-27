# Comments on Project Updates, due 2025-03-26 

## Notes to everyone

1. The final project document (not the slides), including all elements, should be written in Quarto and submitted as HTML. Do not send me Word or PDF files for the final version. And don't send me anything with tracked changes, please.
2. The slides for your project presentation can be in PDF, Powerpoint or Google Slides.
3. If you learn nothing else from this course in general and this project in particular, please learn that statistical significance is not in any way a useful concept, and you shouldn't be using it for any purpose *other* than deciding whether or not to include a Rosenbaum sensitivity analysis after your propensity-matched result.
4. You should be defaulting to doing single imputation on missing data in the predictors of the propensity model (assuming MAR), after restricting to complete cases for the outcome and exposure (assuming MCAR). Using the terms (Missing At Random and Missing Completely At Random) helps. If you want to use multiple imputation, save it for the outcome model, rather than the propensity model, for this Project.
5. The warning `glm.fit: fitted probabilities numerically 0 or 1 occurred` is a clear indication that you have a problem that must be fixed. Usually this is a sign that you have some categories (or combinations of categories) in which all subjects are in one of your two exposure groups. Collapse such categories profoundly will be my first piece of advice.

## Anika Krishna "Framing Mental Illness: Racial Disparities in Police Killings"

- Data in R
- I, too, wish you had more covariates available. I'm not sure why you had to remove things when you re-downloaded the data. Don't you have the initial version?

## Trisha Lal "Preventable Hospitalizations in Rural and Urban Counties in the Midwest Based on 2025 County Health Rankings"

- Data in R
- Some issues
    1. Removing all of the variables that are highly collinear isn't the goal - you still want to include at least one of them.
    2. Identifying what in the propensity score model is causing observations to have propensity scores well below 0.01 or well above 0.99 is your job here, I'm afraid. You need to figure out who is in this situation, and what values of your predictors are leading to these results.
    3. Make sure that you describe the actual years in which each of your data elements was collected (not 2025) and that those make sense in your propensity model presentation.

## Logan Harper "Glucocorticoid toxicity in a prospective, international, survey of sarcoidosis patients"

- Data in R
- Several minor concerns.
    1. If you're matching with replacement, I *might* worry about it if a single case was used 10 or more times. Otherwise, I wouldn't worry.
    2. Steroid duration isn't a variable you can use in a model where steroids is the exposure. If they're both potential predictors, pick one or the other.
    3. Significance is absolutely not what you should be focusing on, in any scenario at all, except for deciding whether a Rosenbaum sensitivity analysis is needed in addition to a stability analysis. The best thing you could do about statistical significance is never, ever think about it or use it again, in any setting. 
    4. What about outlying values in predictors?
    5. ATT Weighting is no different than matching when it comes to comparing outcomes. Estimates from weighting work in the same way as estimates from matching.

## Olivia Lindberg "Substance Use and Social Development in Young Adults"

- Data in R
- No major problems.
    1. I, too, wish you had some quantitative covariates.
    2. Do a good job on the exposure and predictors setup you have rather than experimenting with new exposures. Don't fit lots of different propensity models in this project.
    3. It's fine to look at more than one outcome, and then select a key one or two to present in detail, but I worry you would be cherry-picking results. So you probably want to stick to at most three.

## Jiawei Yu "The Impact of Time Lived in the United States on Adult Food Security"

- Data in R
- No major problems.
    1. You definitely want to make sure that you are understanding and applying Rubin's Rule 1 and Rubin's Rule 2 to describe balance in the linear propensity score before and after your matching and weighting as well as before you fit the propensity model, and the Love plot appropriately to look at comparing means of the individual covariates. It is perfectly possible to have better looking results with some of these three tools than others, but if that happens, you should be able to explain why.
    2. You need to match in this project, and you need to weight and regression adjust (double robust approach) in this project. Both analyses need to be done, and you can focus on one in your presentation, but then you'll need to convince us that the other approach is problematic, by showing us the problem in your presentation.

## Tatchaporn Ongphichetmetha "Impact of Non-Adherence to Inhaled Corticosteroids on Asthma Control in Adult Patients"

- Data in R
- Some issues
    1. Secondary outcome has a major problem with floor and ceiling. You are stuck a bit there. Good thing it's a secondary outcome. A count model isn't appropriate for this project, although you might consider it after April is over.
    2. Nothing should stop any of you from assuming MAR and using single imputation for covariates.
    3. Why would you expect to pass Rubin's Rule 2 (or Rule 1 for that matter) in a model that doesn't adjust for the propensity score? Should you?

## Dana Jian "Examining Mental Health Burden Among Foreign and U.S. Born Adults"

- Data in R
- Some issues
    1. If there's less overlap than you would like, the whole point is to try different matching methods until you find one that you are happy with.
    2. You want to match as many subjects as possible, sure, but that's part of the purpose of weighting.
    3. Should we be more concerned with using as many subjects as possible, or getting the best possible balance, or is there a tradeoff?


## Kelly Bowen "Effect of Metformin on Liver Health in a Sample of Patients with Diabetes"

- Data in R
- No major current problems. I encourage single imputation of predictors included in the PS, rather than complete case analysis.

## Ajay Mahenthiran "Limited Choices, Higher Risks: How Food Access Shapes Diabetes Prevalence"

- Data in R, though not without some difficulties along the way
- I would never make a covariate which was actually quantitative into a categorical one unless I had an excellent reason to do so.
- Some very specific issues
    1. Sample size is fine for 1:1 matching, certainly.
    2. I am virtually certain that your problem is not with your model. You need to look at what tidy(unadj_diab) is before you start trying to select from it. You also need to make sure that you aren't using two R packages that have conflicting meanings of `select()`. Use the conflicted package to be sure.

## Catherine Hassett "Impact of Antihypertensive Therapy on Hematoma Expansion in Intracerebral Hemorrhage"

- Data in R
- Some issues
    1. Data are widely separated in distribution across the two groups. You need to figure out which of the variables in your propensity score are causing this. It's your job to then decide whether those variables should be included in your model, or whether you should exclude subjects with certain values which make them inevitably fall in one specific group or the other.
    2. The warning glm.fit: fitted probabilities numerically 0 or 1 occurred is a clear indication that you have a problem that must be fixed. Usually this is a sign that you have some categories (or combinations of categories) in which all subjects are in one of your two exposure groups. As you should see in your propensity score fit, you have (at least two) categorical variables: race and admission type, which must be collapsed, as the model cannot handle the separation you're seeing and thus you're getting standard errors which blow up. I would turn each of those into binary predictors (perhaps White vs. all other races) and one type of admission vs. all others. You may also have a problem with hypertension, but I would look at that again when you have addressed the race and admission type variables. I'm not seeing the modified rank score in your model. What am I missing?
    3. It's your job to try various matching and weighting strategies to deal with the imbalance you find in your data. I will not give you strong advice on this, but there's no point in looking at matches until you have a model that fits properly and produces propensity scores that fall (at least almost completely) between 0.0050 and 0.9949.

## Sarah Albalawi?
