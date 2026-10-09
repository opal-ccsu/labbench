# Concept Bench · content for review

What the Concept Bench checks against, in plain text. Terms, definitions, examples and watch-fors come straight from glossary/terms.json (the course glossary) and are not repeated here, except for the interim overrides in section 0. Live page: https://opal-ccsu.github.io/labbench/concepts/ · Glossary: https://opal-ccsu.github.io/labbench/glossary/

## 0 · Interim overrides of glossary entries

The rule on the map is: one continuous IV is correlation, two or more continuous IVs is regression, a mix of continuous and categorical is off the map. The glossary still describes a one-predictor "simple regression" branch in these entries, so the bench overrides them with the text below until the glossary is corrected. These are the suggested replacements.

### Simple linear regression (id: regression)

- **term** (was: Simple linear regression)  
  now: Regression
- **aliases** (was: linear regression, bivariate regression)  
  now: multiple regression, linear regression
- **definition** (was: Same two continuous variables as correlation, different question: use one to predict the other and get an equation you can put a number into. On the map: one continuous IV and the question asks for a predicted value.)  
  now: A score DV with two or more continuous IVs. Each predictor gets a slope that holds the others constant, and R² says how much of the outcome the set predicts together. That is the point of regression, and it takes more than one predictor. On the map: all IVs continuous, two or more of them.
- **example** (was: An admissions office wants to estimate first-semester GPA from high school GPA and state a predicted value for any applicant. The word predict is the signal.)  
  now: High school GPA and SAT score together predict first-semester GPA. Two continuous IVs, one score DV: regression. The equation returns a predicted GPA for any applicant.
- **watch** (was: If the question wants a value, it is regression. If it wants to know whether two things are related, it is correlation.)  
  now: One continuous IV is a correlation, whatever verb the question uses. Regression begins at two. A mix of continuous and categorical IVs is off this map, Psy 302.

### Correlation (id: correlation)

- **definition** (was: Two continuous variables measured on the same people, nothing manipulated, asking whether they are related. On the map: a score DV with one continuous IV, and the question is about a relationship.)  
  now: Two continuous variables measured on the same people, nothing manipulated, asking whether they are related. On the map: a score DV with one continuous IV, a second score on the same people. One continuous IV is correlation; two or more is regression.

### Continuous variable (id: continuous-variable)

- **watch** (was: A continuous variable can be an IV. Hours studied predicting exam score has one continuous IV.)  
  now: A continuous variable can be an IV. Hours studied with exam score is one continuous IV: correlation. Hours studied and sleep together predicting exam score is two: regression.

### The IV-kind fork (id: iv-kind-fork)

- **definition** (was: Once the DV is a score, the next question is what kind of IVs you have. None (comparing one group to a known value): one-sample t. All continuous: correlation or regression. All categorical: the t and ANOVA branch, by levels and by between or within. A mix of continuous and categorical: off this map, Psy 302.)  
  now: Once the DV is a score, the next question is what kind of IVs you have. None (comparing one group to a known value): one-sample t. One continuous IV: correlation. Two or more continuous IVs: regression. All categorical: the t and ANOVA branch, by levels and by between or within. A mix of continuous and categorical: off this map, Psy 302.
- **example** (was: Hours studied predicting exam score: one continuous IV. Four onboarding formats: one categorical IV. Caffeine group plus age in years: a mix, Psy 302.)  
  now: Hours studied with exam score: one continuous IV, correlation. Hours studied and sleep predicting exam score: two continuous IVs, regression. Four onboarding formats: one categorical IV. Caffeine group plus age in years: a mix, Psy 302.

### Off this map (Psy 302) (id: off-the-map)

- **definition** (was: Designs this course names but does not run: two or more continuous IVs (multiple regression), a mix of continuous and categorical IVs, ranks as the DV or an IV (ordinal), more than one DV (MANOVA), a within-subjects IV in a factorial (mixed ANOVA), and three or more IVs.)  
  now: Designs this course names but does not run: a mix of continuous and categorical IVs, ranks as the DV or an IV (ordinal), more than one DV (MANOVA), a within-subjects IV in a factorial (mixed ANOVA), and three or more IVs.

### The map (decision tree) (id: decision-tree)

- **example** (was: Ten boxes on the 215 handout tree: two chi-squares, three t-tests, three ANOVAs, correlation, and simple regression.)  
  now: Ten boxes on the 215 handout tree: two chi-squares, three t-tests, three ANOVAs, correlation (one continuous IV), and regression (two or more).

### The ones that look like something else (id: the-tricky-ones)

- **definition** (was: Scenarios commonly answered with the wrong test: before-and-after with different people (independent, not paired), a predict question with two continuous variables (regression, not correlation), two categorical variables (independence, not goodness of fit), three conditions on the same people (repeated-measures ANOVA, not three paired t-tests).)  
  now: Scenarios commonly answered with the wrong test: before-and-after with different people (independent, not paired), a predict question with one continuous IV (correlation, not regression), two categorical variables (independence, not goodness of fit), three conditions on the same people (repeated-measures ANOVA, not three paired t-tests).

### Regression equation (Ŷ = bX + a) (id: regression-equation)

- **term** (was: Regression equation (Ŷ = bX + a))  
  now: Regression equation (Ŷ = b₁X₁ + b₂X₂ + a)
- **definition** (was: What regression hands you. b is the slope, a is the intercept, X is the predictor value you plug in, and Ŷ is the predicted criterion value.)  
  now: What regression hands you. Each b is the slope for one predictor, holding the others constant; a is the intercept; the Xs are the predictor values you plug in; Ŷ is the predicted criterion value.
- **example** (was: Ŷ = 4.20X + 51.8. A student who studies 8 hours is predicted to score 4.20 × 8 + 51.8 = 85.4.)  
  now: Ŷ = 3.10X₁ + 0.02X₂ + 40.5, with X₁ hours studied and X₂ SAT score. A student with 8 hours and an SAT of 1200 is predicted to score 3.10 × 8 + 0.02 × 1200 + 40.5 = 89.3.

### Slope (b) (id: slope)

- **definition** (was: How much the predicted Y moves for each one-unit change in X.)  
  now: How much the predicted Y moves for each one-unit change in that predictor, holding the other predictors constant.
- **example** (was: b = 4.20: each additional hour of study predicts 4.2 more points on the exam.)  
  now: b₁ = 3.10: each additional hour of study predicts 3.1 more points, for students with the same SAT score.

### Predictor and criterion (id: predictor-criterion)

- **definition** (was: In regression, the predictor is the X you plug in (the IV) and the criterion is the Y you predict (the DV).)  
  now: In regression, the predictors are the Xs you plug in (the IVs, two or more of them) and the criterion is the Y you predict (the DV).

### Model fit (R² and the regression F) (id: model-fit)

- **example** (was: F(1, 83) = 60.72, p < .001, R² = .42: about 42% of the variance in exam score is predictable from hours studied, and the model beats chance.)  
  now: F(2, 82) = 31.40, p < .001, R² = .43: about 43% of the variance in exam score is predictable from hours studied and SAT together, and the model beats chance.

### Reporting a regression (id: apa-regression)

- **definition** (was: The model first: F(df1, df2) = value, p, R². Then the predictor: B, SE, β, t, p. Then the equation with your numbers, and one worked prediction.)  
  now: The model first: F(df1, df2) = value, p, R². Then each predictor: B, SE, β, t, p. Then the equation with your numbers, and one worked prediction.
- **example** (was: The model was significant, F(1, 83) = 60.72, p < .001, R² = .42. Hours studied predicted exam score, B = 4.20, SE = 0.54, β = .65, t = 7.79, p < .001. Ŷ = 4.20X + 51.8.)  
  now: The model was significant, F(2, 82) = 31.40, p < .001, R² = .43. Hours studied predicted exam score, B = 3.10, SE = 0.52, β = .48, t = 5.96, p < .001, as did SAT score, B = 0.02, SE = 0.01, β = .29, t = 3.61, p = .001. Ŷ = 3.10X₁ + 0.02X₂ + 40.5.

### Regression → Linear (id: regression-linear-dialog)

- **watch** (was: Two or more predictors in Independent(s) is multiple regression, which is off this course’s map.)  
  now: Every predictor goes into Independent(s). One predictor there is not regression on this map; it is the correlation you already ran.

### Trendline (Excel) (id: trendline)

- **watch** (was: The trendline is the regression line. Reading its equation is how 215 does regression without SPSS.)  
  now: A trendline fits one X, so it shows the slope-and-intercept idea on a scatterplot. Regression with two or more predictors runs through Data → Data Analysis → Regression.

### CORREL (id: excel-correl)

- **definition** (was: =CORREL(range1, range2) returns Pearson r. Square it yourself for r², and read the slope and intercept from the trendline equation.)  
  now: =CORREL(range1, range2) returns Pearson r. Square it yourself for r². With two or more predictors, run Data → Data Analysis → Regression instead.

## 1 · Key ideas per term (Define it)

Each key idea is matched loosely in the student's text; a missing one is listed back to them. Then the glossary definition, example and watch-for open and the student marks themselves.

### 1 · Seeing

- **Variable**: something measured or recorded that varies across people · each column of the data file is one
- **Independent variable (IV)**: manipulated, or the variable you group people by · it defines the groups being compared, or is expected to affect the DV
- **Dependent variable (DV)**: the thing measured, the outcome, your ruler · expected to depend on the IV, and found first
- **Manipulated vs. measured**: manipulated means the researcher assigned it · measured means it was already true of the person · both can be IVs; only a manipulated IV supports a causal claim
- **Levels**: the distinct values or groups of an IV · count them: two means t, three or more means ANOVA
- **Scale of measurement**: nominal, ordinal, interval, ratio · the DV's scale decides counts or scores, the first fork
- **Nominal**: categories or labels · no order; numbers are codes, not quantities
- **Ordinal**: order or rank is information · the gaps between steps are not equal  
  Wrong version flagged: Ordinal is not categorical. Order is information; what ordinal lacks is equal gaps.
- **Interval**: equal gaps between units · no true zero, so no ratios
- **Ratio**: a true zero that means none of the thing · equal gaps, so ratios ("twice as much") make sense
- **Borda count** [Psy 215 only]: each rank position earns points, summed across rankers · it works because ordinal data has order
- **Counts vs. scores (the first fork)**: counts of people in categories · a score you can average · counts go to chi-square; it is the top of the map
- **Continuous variable**: a number every person has, with many possible values · a continuous IV leads to correlation and regression
- **Categorical IV**: an IV that sorts people into named groups · all categorical IVs puts you on the t and ANOVA branch
- **Between-subjects**: different people in each level · each participant contributes one score in one condition
- **Within-subjects**: the same people in every level, or matched pairs · each participant contributes a score in every condition
- **Design**: how many IVs and how many levels each has · whether each IV is between- or within-subjects
- **One row per participant**: one row per participant, one column per variable · names in row 1, no blank rows or notes; a group column rather than one column per group
- **The Estimation Habit**: guess or predict before you compute · then compute and compare
- **Descriptive vs. inferential statistics**: descriptive describes the data you have · inferential uses a sample to say something about a population, with a test
- **Frequency distribution**: which values showed up · how often each one occurred
- **Histogram**: scores grouped into bins · bar height is frequency; for score variables
- **Bin width** [Psy 215 only]: the size of each grouping in a histogram · you choose it and the choice changes the picture
- **Shape of a distribution**: symmetric, skewed, or bimodal · read it before choosing a measure of center
- **Symmetric**: both tails about the same, a bell · mean and median land in the same place
- **Positive skew**: the tail stretches to the right, a few very high scores · the mean is pulled above the median
- **Negative skew**: the tail stretches to the left, a few very low scores · the mean is pulled below the median
- **Bimodal**: two separate humps or peaks · usually two groups mixed in one file; the mean describes nobody
- **Outlier**: a case far from the rest · investigate it; not automatically an error or a delete
- **Look first**: plot before you test · before running the analysis or reading the number
- **Central tendency**: a single number for where the scores sit · mean, median, or mode, chosen by scale and shape · the choice depends on scale and shape
- **Mean**: sum of the scores divided by n · uses every score, so one outlier moves it
- **Median**: the middle score when ordered · not moved by extreme scores, so it is reported on skewed data
- **Mode**: the most common score · the only center that works for nominal data
- **Variability**: how spread out the scores are · two groups can share a mean and still differ; report SD with M
- **Range**: maximum minus minimum · sensitive to a single extreme case
- **Variance**: the average squared distance from the mean, SD squared · in squared units, so SD is what gets reported; it is what ANOVA partitions
- **Standard deviation (SD)**: the typical distance of a score from the mean · typical spread, not literally the average distance (squares are involved)  
  Wrong version flagged: Close, and the course says "roughly the typical distance". The deviations are squared before they are averaged, so it is not literally the average distance.
- **STDEV.S vs. STDEV.P** [Psy 215 only]: S is the sample version, dividing by n − 1 · P is the population version, dividing by N · you essentially always have a sample, so use STDEV.S  
  Wrong version flagged: STDEV.P is not more accurate. It is the population formula, and you have a sample.
- **n − 1**: sample scores huddle closer to their own mean than to the population mean · dividing by n would underestimate the spread; n − 1 corrects it
- **Minimum and maximum**: the lowest and highest values · the first check that data are inside the legal range
- **Reporting M and SD**: M and SD reported together · italic symbols, two decimals
- **z-score**: how many standard deviations from the mean · in which direction; answers how unusual a score is
- **Standardizing**: converting raw scores to z-scores · so scores on different scales share one ruler
- **Normal distribution**: symmetric and bell-shaped · about 68% within one SD, about 95% within 1.96 SDs, only in a normal distribution
- **Area under the curve** [Psy 215 only]: the proportion of a normal distribution below, above or between scores · Excel computes it with NORM.DIST or NORM.S.DIST; no tables
- **Screening with z (|z| > 3)**: flag cases with |z| beyond 3 before analysis · a flag means look, not delete
- **Population**: everyone you care about · you never measure all of it
- **Sample**: who you actually measured · it should look like the population
- **Parameter**: a number describing the population · unknown, and the thing you want
- **Statistic**: a number describing the sample · known, and slightly off from the parameter
- **Sampling error**: the gap between the statistic and the parameter · not a mistake; the price of not measuring everyone  
  Wrong version flagged: Sampling error is not a mistake. Every one of those sample means was computed correctly.
- **Standard error**: the typical distance between a sample mean and the population mean, the SD of sample means · it shrinks as n grows
- **Distribution of sample means**: the distribution a statistic would have across many samples · tighter than the raw data, because averages vary less than individuals
- **Sample size**: n per group and total N · larger samples mean smaller standard error and more power

### 2 · The hinge

- **Hypothesis testing**: could I have gotten a result this extreme if nothing was going on · every test asks the same question
- **Null hypothesis (H₀)**: no difference, no relationship, no effect · it is the claim being tested  
  Wrong version flagged: You never accept the null. You reject it or you fail to reject it.
- **Alternative hypothesis (H₁)**: something is going on: an effect or difference · never established directly; you reject the null or fail to
- **p value**: the probability of a result at least this extreme · if the null were true  
  Wrong version flagged: That is the wrong version, the one to say out loud and cross out. p is the probability of data at least this extreme IF the null were true. It is not the probability that the null is true, and not the probability you are wrong.
- **Alpha (α)**: the cutoff you set before testing, usually .05 · it is the Type I error rate you accept when H₀ is true
- **Reject / fail to reject**: p at or below alpha means reject · otherwise fail to reject; never "accept"  
  Wrong version flagged: Fail to reject is not accept. Absence of evidence is not evidence of absence.
- **Statistical significance**: p at or below alpha, so the result would be rare under the null · it does not mean large or important  
  Wrong version flagged: Significant does not mean large. Effect size says how big.
- **Type I error**: rejecting a true null, finding something that is not there · its rate is alpha, about one in twenty
- **Type II error**: failing to reject a false null, missing something real · the rate is beta; small samples make it more likely
- **Statistical power**: probability of detecting an effect that is really there · rises with sample size and effect size; 1 − β
- **The 2 × 2 decision matrix** [Psy 215 only]: truth (H₀ true or false) by decision (reject or fail to reject) · two correct cells; the other two are Type I and Type II
- **Reporting a non-significant result**: report it in full with the statistic and exact p · conclude no evidence of a difference, not that there is none
- **Degrees of freedom (df)**: how much information you had; values free to vary · it comes from the design, so it checks that you ran the right test
- **Test statistic**: the number a test produces (χ², t, F, r) · converted to a p; bigger means further from the null
- **Assumption**: a condition a test needs to be trustworthy · examples: expected counts ≥ 5, similar variability, a straight line; check it and report that you did

### 3 · A categorical DV

- **Chi-square goodness of fit**: one nominal variable, counts of people in categories · observed compared with expected if nothing were going on
- **Observed count**: how many people actually landed in each category · what you counted, compared with expected
- **Expected count**: how many would land in each category if the null were true · where they come from is a decision you state
- **Three sources of expected counts**: equal across categories · a known population rate · a control group
- **Residual (observed − expected)** [Psy 210 only]: observed minus expected for each category · sign says over- or under-represented; size says which category drove it
- **Chi-square test of independence**: two nominal variables counted together · asks whether they are related, whether one tells you about the other
- **Contingency table**: a rows-by-columns table of counts for two variables · each cell holds the people with that combination
- **Expected counts from the margins**: row total times column total divided by the grand total · each cell gets its fair share if the variables are unrelated
- **Expected-count assumption (≥ 5)**: every expected count at least 5 · expected, not observed; collapse categories or get more data, and report the check
- **df for chi-square**: goodness of fit: categories − 1 · independence: (rows − 1)(columns − 1)
- **Reporting a chi-square**: χ²(df, N = total) = statistic, p · two decimals on the statistic, exact p unless below .001, then say which categories drove it

### 4 · A score, two levels

- **t-test**: a difference divided by how much it bounces · divided by the bounce, the standard error or spread
- **One-sample t-test**: one group of scores · compared with a known or claimed value from outside the data
- **Paired-samples t-test**: the same people measured twice, or matched pairs · one IV with two levels, within-subjects; built on difference scores, df = pairs − 1
- **Independent-samples t-test**: two groups of different people, one score each · one IV with two levels, between-subjects
- **The before-and-after trap**: same participants means paired · before and after by itself does not decide it; different people means independent
- **Difference scores**: each pair's Time 2 minus Time 1 · the paired t is a one-sample t on those differences, tested against zero
- **Test value** [Psy 210 only]: the known population figure you compare the sample against · it comes from outside the data; the default 0 is almost never right
- **Homogeneity of variance**: similar spread or variance in the groups · not similar means; that is what you test · Levene's checks it in SPSS; Excel asks up front
- **Levene’s test**: checks whether the groups have similar variances · p > .05 means read "equal variances assumed"; p ≤ .05 means the other row
- **Fractional df** [Psy 210 only]: df on the "not assumed" row is adjusted and not a whole number · that is correct; report it as printed
- **df for t-tests**: one-sample: n − 1 · paired: pairs − 1 · independent: n₁ + n₂ − 2
- **Reporting a t-test**: t(df) = statistic, p, d · with the means and SDs, then what it means in words
- **Effect size**: how big the difference or relationship is · independent of sample size; part of the result, not an extra
- **Cohen’s d**: the difference between two means in SD units · benchmarks about 0.2, 0.5, 0.8, which are not laws
- **Eta squared (η²)**: the proportion of variance in the DV predictable from the IV · benchmarks about .01, .06, .14
- **Partial eta squared** [Psy 210 only]: what SPSS prints under Estimates of effect size · variance predictable from one effect with the others set aside; equals η² for one-way
- **Practical vs. statistical significance**: statistical: rare under the null · practical: big enough to matter · large samples make the first free, never the second

### 5 · More levels, more IVs

- **One-way ANOVA**: three or more groups, one IV, one analysis · compares variability between groups to variability within, giving one F
- **F ratio**: variability between groups divided by variability within · within-group variability underneath · near 1 means the groups are about the same
- **Familywise error**: every test carries a Type I risk; several tests multiply it · ANOVA asks one question with one alpha; post hocs control the follow-ups
- **Omnibus test**: the overall F across all groups · says somebody differs, not who; read it before the post hocs
- **Post-hoc tests**: pairwise comparisons that find which groups differ · only after a significant F
- **Tukey HSD**: a common post hoc, moderate · controls familywise error without being as strict as Bonferroni
- **Bonferroni**: divides alpha by the number of comparisons · the conservative post hoc; each comparison clears a stricter bar
- **One-way repeated-measures ANOVA**: one IV with three or more levels · the same people in every level, the within version of one-way ANOVA
- **The Excel wall** [Psy 215 only]: the ToolPak gives F, df, p and the sums of squares, then stops · no post hoc, no effect size printed, no Levene's · past that line is SPSS and Psy 210
- **df for ANOVA**: between: number of groups − 1 · error or within: total N minus the number of groups
- **Reporting an ANOVA**: F(df between, df error) = statistic, p, η² · then the post hoc sentence: which groups differed, which direction, by how much
- **Factorial design**: two IVs at once, every combination of levels · three questions: A, B, and whether A depends on B
- **Two-way between-subjects ANOVA**: a factorial where every IV is between-subjects · an F for each main effect and one for the interaction
- **Design notation (2 × 2)**: number the levels of each IV, multiplied · the count of numbers is the IVs; the product is the cells
- **Cell**: one combination of levels in a factorial, or one box in a contingency table · record each cell's size; small cells are the concern
- **Main effect**: the effect of one IV by itself · averaging over the levels of the other
- **Interaction**: the effect of one IV depends on the level of the other · the headline when significant; main effects then mislead
- **Interaction plot**: cell means plotted, one IV on the axis and the other as lines · parallel means no interaction; non-parallel or crossing means an interaction
- **Main effects when the interaction is significant**: the effect of A is a different number at each level of B · describe the simple effects condition by condition instead of the average
- **Reporting a factorial ANOVA**: three results, each with F, df, p and partial η² · then describe the interaction from the plot or cell means

### 6 · Association

- **Correlation**: two scores on the same people: one continuous IV, nothing manipulated · the question is whether they are related
- **Scatterplot**: one dot per person, one variable on each axis · read direction, strength and form
- **Direction, strength, form**: direction: up together, or one up one down · strength: tight band or a cloud · form: straight or curved; r only measures straight
- **Linear relationship**: a relationship a straight line describes well · r assumes one and cannot check for it; look at the plot
- **Pearson r**: runs from −1 to +1 · the sign is the direction, the distance from zero is the strength · straight-line relationships only
- **r²**: the proportion of variance in one variable predictable from the other · square r yourself; it is the honest number
- **Correlation does not imply causation**: moving together does not say which one moves the other · a third variable could move both; say it about your own variables  
  Wrong version flagged: Check that sentence: a correlation cannot say which variable moves the other, or whether a third variable moves both.
- **One bad point**: a single extreme case can change r, the slope and the conclusion · which is why you plot first; investigate it, do not delete silently
- **Restricted range** [Psy 210 only]: the sample covers only a narrow slice of a variable · r shrinks even when the relationship is strong across the full range
- **Regression**: two or more continuous IVs · each slope holds the others constant; R² for the set; a predicted value
- **Predictor and criterion**: the predictor is the X you plug in, the IV · the criterion is the Y you predict, the DV
- **Regression equation (Ŷ = b₁X₁ + b₂X₂ + a)**: each b is a slope, holding the other predictors constant · a is the intercept · Ŷ is the predicted value for a given X
- **Slope (b)**: change in predicted Y for each one-unit change in X
- **Intercept (a)**: the predicted Y when X is zero · often not meaningful on its own, but the equation needs it
- **Predicted value (Ŷ)**: the Y the equation gives for a specific X · the product of regression; it carries prediction error
- **Prediction error**: the gap between predicted and what a real person scored · find someone near your X and compare
- **Do not predict outside the range**: predicting outside the range of the data · the line keeps going but the relationship may not
- **Model fit (R² and the regression F)**: R², the proportion of variance in the criterion predictable from the predictor · the ANOVA-table F asks whether the model beats chance
- **Coefficients table** [Psy 210 only]: one row per predictor plus a Constant row · report B, SE, β, t, p; Constant is the intercept, the predictor row is the slope
- **Reporting a correlation**: r(df) = value, p, with df = n − 2 · direction and strength in words, without claiming causation
- **Reporting a regression**: the model first: F, p, R² · then the predictor: B, SE, β, t, p · then the equation with your numbers and one worked prediction
- **Trendline (Excel)** [Psy 215 only]: Excel's fit line on a scatterplot · display the equation and R²; it is the regression line

### 7 · Proof

- **The map (decision tree)**: starts with the DV: counts or a score · counts split into one or two variables; scores fork on the kind of IV · built one branch at a time; drawn from memory on the Capstone
- **The five-step procedure**: find the DV · find the IVs, continuous or categorical · for each: name it, levels, between or within · name the test · say why
- **The IV-kind fork**: none: one group against a known value, one-sample t · one continuous IV is correlation; two or more is regression · all categorical: t and ANOVA by levels and between/within · a mix is off the map, Psy 302
- **Off this map (Psy 302)**: designs the course names but does not run · examples: a mix of IV kinds, ordinal, MANOVA, mixed ANOVA, three or more IVs
- **“Which test?” items**: a scenario in a few sentences · name the DV, IVs, levels, between or within, the test and why · design earns more than the name
- **The ones that look like something else**: before-and-after with different people is independent · predict means regression; two categorical means independence; three conditions on the same people is RM ANOVA · say what rules the wrong test out
- **Say why**: one sentence that names the test using the design · DV scale, number and kind of IVs, levels, between or within
- **The Test-Selection Capstone** [Psy 215 only]: draw the map from memory · name the test for scenarios, including tricky ones, and diagnose an error
- **The Comprehensive Practical** [Psy 210 only]: your own dataset, nobody tells you which tests to run · submit data, syntax, output and write-up, and they must agree

### 8 · The AI Data Protocol

- **The AI Data Protocol**: specify, generate, verify, analyze, log · you order data rather than download it; every week, both courses
- **Specify**: write it down before typing anything to an AI · every variable with scale and legal range, the design, n, the truth and the format
- **Specification (spec)**: the written order for a dataset: variables, scales, ranges, design, n, the truth, the format · grading checks your conclusions against it
- **Generate**: ask for the data as CSV in one code block, one row per participant · and a plain-English Truth Statement
- **Verify**: count, range, structure, descriptives · and whether the effect you ordered is there; never skip it
- **Analyze**: this step is yours alone; AI does not interpret output or write results · only now do you touch Excel or SPSS
- **Log**: the prompts verbatim, what came back including the Truth Statement · what was wrong and what you did about it
- **Truth Statement**: the AI's plain-English statement of what it built into the data · your answer key and the grading key; ask for it every time
- **Legal range**: the values a variable is allowed to take · state it in the spec, check it in Verify
- **Realistically noisy**: individual variation so the data look like data · no identical SDs, no suspiciously tidy means
- **Generation failure modes**: wrong row count, out-of-range values, too clean, cut off, commentary mixed in, formatted table · caught by Verify and recorded in the Log
- **Shared spec, individual data** [Psy 215 only]: one specification for the team · each member generates their own data; the answers differ and nobody made a mistake
- **Simulation vs. fabrication**: simulation is transparent: specified, logged, verified, labeled as simulated · presenting generated data as genuinely collected is fabrication

### 9 · APA reporting

- **The APA opener**: write the sentence before you click: to determine whether, I ran, and found · it commits you to what you are running and why
- **What did you do, what did you find, what is your evidence**: what test you ran · what you found, in plain words with direction · the statistics as evidence
- **Reporting p**: exact p to two or three decimals · below .001 write p < .001; never .000, never ns · no leading zero on p
- **Symbols, italics, and decimals**: statistical symbols in italics; Greek letters not · two decimals for statistics, two or three for p, no leading zero on values that cannot exceed 1
- **Plain-language conclusion**: one sentence a non-statistician would understand · names your actual variables and the direction; follows the statistics
- **Say which groups and which direction**: say which groups, categories or conditions drove the result · and in what direction, with numbers
- **Find the Error**: a reported result with one clear mistake · identify it and correct it; the correction is part of the answer

### 10 · SPSS

- **Variable View** [Psy 210 only]: the tab where you tell SPSS what every column is · one row per variable: Name, Type, Decimals, Label, Values, Missing, Measure
- **Data View** [Psy 210 only]: the spreadsheet-like tab where the data live · one row per participant, one column per variable
- **Variable Name** [Psy 210 only]: the Name column: no spaces, not starting with a number · name it the way a human reads it, so you know what it was later
- **Type (Numeric vs. String)** [Psy 210 only]: Numeric for numbers, String for text · code categories as numbers with labels, because strings cannot go into most analyses
- **Decimals** [Psy 210 only]: how many decimal places SPSS displays · set 0 for whole numbers, codes and counts
- **Values (value labels)** [Psy 210 only]: labels that turn a code into a word in the output · set for every categorical variable; they do not arrive with an import
- **Measure (Nominal, Ordinal, Scale)** [Psy 210 only]: Nominal for categories, Ordinal for ranks, Scale for interval and ratio · SPSS guesses wrong on import; fix every variable yourself
- **Import Data (Excel)** [Psy 210 only]: File → Import Data → Excel, reading variable names from the first row · then fix Measure and Values in Variable View
- **Frequencies** [Psy 210 only]: counts and percentages for every value of a variable · for categorical variables and for finding dirt in items
- **Descriptives** [Psy 210 only]: mean, SD, minimum and maximum for score variables · Options chooses which; Save standardized values adds z columns
- **Chart Builder** [Psy 210 only]: Graphs → Chart Builder: drag a chart type and variables onto it · histogram for one score, simple scatter for two
- **Output window and export** [Psy 210 only]: where SPSS prints every table and chart · export to PDF or save as .spv; export the whole output
- **SPSS file types (.sav, .sps, .spv)** [Psy 210 only]: .sav is data · .sps is syntax · .spv is output; the Practical wants all plus a write-up, consistent
- **Codebook** [Psy 210 only]: what each variable is, how coded, legal range, where from · read it before opening the data; uninterpretable data are not usable
- **Data screening** [Psy 210 only]: finding the dirt before you analyze: missing, out of range, reverse-keyed, wrong N · dirty data give normal-looking results that are wrong
- **Missing values** [Psy 210 only]: blank cells where a participant skipped, or codes treated as missing · find them during screening, decide, document
- **Out-of-range value** [Psy 210 only]: a value outside the legal range · treat as missing or fix from the source; document it
- **Reverse-keyed item** [Psy 210 only]: worded so a high score means the opposite of the construct · must be reverse-scored before it goes into a scale mean
- **Reverse scoring (max + 1 − x)** [Psy 210 only]: new item = (maximum + 1) − item · the number depends on the response scale, not the number of items; verify the recode
- **Compute Variable** [Psy 210 only]: Transform → Compute Variable: a new column from a formula · for a reversed item, a scale mean, a difference score
- **Scale mean** [Psy 210 only]: the average of a participant's correctly scored items · the score you analyze; the items are what you clean
- **Item-level vs. scale-level data** [Psy 210 only]: items are for reverse-scoring, the scale mean, and reliability · every test runs on the scale mean
- **Reliability analysis (Cronbach’s α)** [Psy 210 only]: Cronbach's α, internal consistency: how well the items hang together · enter the items, not the scale mean; benchmarks .70, .80, .90
- **Paste, don’t OK (syntax)** [Psy 210 only]: click Paste instead of OK; the command appears in a Syntax window and you run it · the syntax is the record of what you did; save it as .sps
- **Select Cases** [Psy 210 only]: filter rows by a condition, or draw a random sample · everything afterward runs on the selected rows until you reset
- **Random sample of cases** [Psy 210 only]: Select Cases draws exactly n cases from the file · each draw is a different sample, so you watch sampling error
- **Save standardized values as variables** [Psy 210 only]: the Descriptives checkbox that adds a z-score column · named with a Z prefix; check its min and max
- **Recode** [Psy 210 only]: Transform → Recode: turn specified values into other values · including system-missing; use Different Variables to keep the original
- **Filter variable** [Psy 210 only]: a column of 1s and 0s marking which cases an earlier analyst kept · just a column until activated in Select Cases; you do not have to accept it
- **Sig. (the p value)** [Psy 210 only]: SPSS's label for the p value · read to three decimals; .000 becomes p < .001; report two-sided
- **Nonparametric Tests → Legacy Dialogs → Chi-square** [Psy 210 only]: the goodness-of-fit dialog under Nonparametric Tests → Legacy Dialogs · set expected values equal or by proportion; read Observed, Expected and Residual first
- **Crosstabs** [Psy 210 only]: one variable in Rows, one in Columns · Statistics → Chi-square; Cells → Observed, Expected, Row percentages; read the table first
- **Compare Means (the three t-tests)** [Psy 210 only]: One-Sample: the variable plus a Test Value · Paired: the two columns as a pair · Independent: Test Variable, Grouping Variable, Define Groups
- **Define Groups** [Psy 210 only]: the button in the Independent-Samples dialog · tells SPSS which two codes of the grouping variable to compare
- **Equal variances assumed / not assumed** [Psy 210 only]: two rows: Levene's p > .05 sends you to the top, p ≤ .05 to the bottom · report which row you used and why
- **General Linear Model → Univariate** [Psy 210 only]: the dialog for one-way and factorial between-subjects ANOVA · DV into Dependent Variable, groups into Fixed Factor(s); then Post Hoc, Plots, Options
- **Tests of Between-Subjects Effects** [Psy 210 only]: the ANOVA table GLM prints · read your factor's row, not Corrected Model or Intercept; Error gives the second df
- **Mean Difference (I − J)** [Psy 210 only]: each row is Mean(I) − Mean(J) · positive with a star means I is significantly higher; only if F was significant
- **Plots (bar chart with error bars; interaction lines)** [Psy 210 only]: one-way: the factor on the Horizontal Axis · factorial: one factor on the axis, the other in Separate Lines; how you read the interaction
- **Homogeneity tests (Levene’s in ANOVA)** [Psy 210 only]: the Options checkbox that prints Levene's for the ANOVA · report it; with large unequal cells say how worried to be
- **Correlate → Bivariate** [Psy 210 only]: Analyze → Correlate → Bivariate; Pearson, two-tailed, flag significant · output is a matrix with r, Sig., N; each pair appears twice; df = N − 2
- **Add Fit Line at Total** [Psy 210 only]: double-click the scatterplot to open the Chart Editor · Add Fit Line at Total draws the regression line and prints R²
- **Regression → Linear** [Psy 210 only]: criterion into Dependent, predictor into Independent(s) · Statistics: Estimates, Model fit, Descriptives, CIs; three tables: Model Summary, ANOVA, Coefficients
- **The four-file deliverable set** [Psy 210 only]: data, syntax, output, write-up · they must be consistent with one another

### 11 · Excel tools

- **Text to Columns (Excel)**: what to do when a pasted CSV lands in one column · Data → Text to Columns → Delimited → Comma, then save as .xlsx
- **AVERAGE, MEDIAN, MODE, MIN, MAX, COUNT** [Psy 215 only]: AVERAGE, MEDIAN, MODE, MIN, MAX, COUNT · center, extremes and n; guess first
- **COUNTIF and the frequency table** [Psy 215 only]: COUNTIF counts cells meeting a condition · two COUNTIFs give a bin: at or above the lower edge minus at or above the upper
- **STANDARDIZE** [Psy 215 only]: STANDARDIZE(x, mean, SD) returns a z
- **NORM.DIST and NORM.S.DIST** [Psy 215 only]: NORM.DIST(x, mean, SD, TRUE) gives the proportion below x · NORM.S.DIST starts from a z; above is 1 minus; between is a difference of two calls
- **CHISQ.TEST** [Psy 215 only]: CHISQ.TEST(observed, expected) returns p, and only p · compute the χ² statistic yourself from (O − E)² ÷ E
- **T.TEST** [Psy 215 only]: T.TEST(array1, array2, tails, type) returns p · type 1 paired, 2 equal variances, 3 unequal · no one-sample function: build t from mean, SD, n and use T.DIST.2T
- **Data Analysis ToolPak: ANOVA Single Factor** [Psy 215 only]: Data → Data Analysis → ANOVA: Single Factor, one column per group · returns SS, df, MS, F, p and nothing else; compute η² yourself
- **CORREL** [Psy 215 only]: CORREL(range1, range2) returns Pearson r · square it yourself for r²; slope and intercept come from the trendline

## 2 · Fill it in

### 1 · Seeing

- The ____ names a skewed distribution, not the hump.  
  Answers: blank 1 = tail
- One extreme score moves the ____ and leaves the ____ alone.  
  Answers: blank 1 = mean; blank 2 = median
- The mean of a ____ distribution describes nobody in the dataset.  
  Answers: blank 1 = bimodal
- Ordinal: order is information. What it lacks is equal ____.  
  Answers: blank 1 = gaps / intervals / spacing / distances / steps / spaces
- STDEV.____ is the sample standard deviation; STDEV.____ is for a population. [Psy 215 only]  
  Answers: blank 1 = s; blank 2 = p
- APA: M = 24.31, SD = 5.02, both reported to ____ decimals.  
  Answers: blank 1 = two / 2
- z = (X − ____) ÷ ____  
  Answers: blank 1 = m / mean / the mean; blank 2 = sd / standard deviation / the sd
- A z column must have a mean of ____ and an SD of ____.  
  Answers: blank 1 = 0 / zero; blank 2 = 1 / one
- About ____% of a normal distribution falls within 1.96 SDs of the mean.  
  Answers: blank 1 = 95
- The ±1.96 rule is only true if the distribution was already ____.  
  Answers: blank 1 = normal / normally distributed / bell shaped / bell-shaped
- The standard deviation of sample means is called the ____.  
  Answers: blank 1 = standard error / standard error of the mean / se / sem
- Sampling error is not a ____. It is the price of not measuring everyone.  
  Answers: blank 1 = mistake / error / flaw / problem
- A number that describes a population is a ____; one that describes a sample is a ____.  
  Answers: blank 1 = parameter; blank 2 = statistic

### 2 · The hinge

- p is the probability of a result at least this extreme IF the ____ were true.  
  Answers: blank 1 = null / null hypothesis / h0
- Rejecting a true null is a Type ____ error.  
  Answers: blank 1 = i / 1 / one
- Missing a real effect is a Type ____ error.  
  Answers: blank 1 = ii / 2 / two
- In the null-data exercise about one in ____ null datasets comes out significant.  
  Answers: blank 1 = twenty / 20
- You test the null. You never ____ the alternative.  
  Answers: blank 1 = prove

### 3 · A categorical DV

- Expected counts under ____ break a chi-square, and software will not warn you.  
  Answers: blank 1 = 5 / five
- CHISQ.TEST returns ____ and nothing else.  
  Answers: blank 1 = p / the p value / p value / a p value
- If software prints p = .000, you write p ____ .001.  
  Answers: blank 1 = < / less than / is less than / under
- Chi-square test of independence: df = (rows − 1)(____ − 1).  
  Answers: blank 1 = columns / cols / c
- Goodness of fit counts ____ variable; independence counts ____.  
  Answers: blank 1 = one / 1 / a single; blank 2 = two / 2
- Expected counts for independence: row total × column total ÷ ____.  
  Answers: blank 1 = n / grand total / total / the total / N
- A bare significant chi-square is an announcement, not a finding. Say which ____ drove it.  
  Answers: blank 1 = cells / categories / cell / category

### 4 · A score, two levels

- Every t is a ____ divided by how much it bounces.  
  Answers: blank 1 = difference / mean difference / a difference
- Before and after does not mean paired. ____ participants means paired.  
  Answers: blank 1 = same / the same / identical
- Paired-samples t: df = ____ − 1.  
  Answers: blank 1 = pairs / number of pairs / n pairs / the number of pairs
- Independent-samples t: df = n₁ + n₂ − ____.  
  Answers: blank 1 = 2 / two
- One-sample t: df = n − ____.  
  Answers: blank 1 = 1 / one
- T.TEST type 1 is ____, type 2 is equal variances, type 3 is ____ variances. [Psy 215 only]  
  Answers: blank 1 = paired; blank 2 = unequal / different
- Cohen's d benchmarks: .2 small, ____ medium, .8 large.  
  Answers: blank 1 = .5 / 0.5 / 5
- The independent t assumes similar ____, not similar means.  
  Answers: blank 1 = spread / variance / variances / variability / standard deviations / sds / sd
- In SPSS, ____ test tells you which row of the independent t to read. [Psy 210 only]  
  Answers: blank 1 = levene's / levenes / levene
- Significant does not mean ____. Effect size says that.  
  Answers: blank 1 = large / big / important / meaningful / strong

### 5 · More levels, more IVs

- F = variability ____ groups ÷ variability ____ groups.  
  Answers: blank 1 = between; blank 2 = within
- An F near ____ means the groups are alike.  
  Answers: blank 1 = 1 / one / 1.0
- A significant F says somebody differs. ____ tests say who.  
  Answers: blank 1 = post hoc / post-hoc / posthoc / tukey / bonferroni / follow up / follow-up
- η² = SS between ÷ SS ____.  
  Answers: blank 1 = total
- Excel's ToolPak ANOVA gives the omnibus F and stops: no ____, no effect size, no Levene's. [Psy 215 only]  
  Answers: blank 1 = post hoc / post-hoc / post hocs / posthoc / post hoc tests
- Three t tests on three groups rolls the Type ____ dice three times.  
  Answers: blank 1 = i / 1 / one
- Two-way ANOVA asks three questions: main effect of A, main effect of B, and the ____.  
  Answers: blank 1 = interaction / a x b interaction / interaction effect
- ____ lines on an interaction plot mean no interaction.  
  Answers: blank 1 = parallel
- A 2 × 3 design has ____ IVs and ____ cells.  
  Answers: blank 1 = two / 2; blank 2 = six / 6
- A factorial with a within-subjects IV is a ____ design: off the map, Psy 302.  
  Answers: blank 1 = mixed / mixed factorial

### 6 · Association

- Three things to say about every scatterplot: direction, strength, and ____.  
  Answers: blank 1 = form / shape
- r only measures ____ relationships.  
  Answers: blank 1 = straight / linear / straight line / straight-line
- r² is the proportion of ____ in one variable predictable from the other.  
  Answers: blank 1 = variance / variability / variation
- Ŷ = b₁X₁ + b₂X₂ + a: each b is a ____ and a is the ____.  
  Answers: blank 1 = slope; blank 2 = intercept / y intercept / y-intercept / constant
- Predicting outside the range of your data is called ____.  
  Answers: blank 1 = extrapolation / extrapolating / extrapolate
- Correlation does not imply ____.  
  Answers: blank 1 = causation / cause / causality / cause and effect
- Correlation has ____ continuous IV; regression has ____ or more.  
  Answers: blank 1 = one / 1; blank 2 = two / 2
- A regression that fits perfectly in real data is a red ____, not a triumph.  
  Answers: blank 1 = flag

### 7 · Proof

- Step 1 of choosing a test: find the ____.  
  Answers: blank 1 = dv / dependent variable / the dependent variable
- Step 5 of choosing a test: name the test, and say ____.  
  Answers: blank 1 = why
- The per-IV loop: name it, count its ____, between or within?  
  Answers: blank 1 = levels
- A mix of continuous and categorical IVs, or an ordinal DV, is kicked to Psy ____.  
  Answers: blank 1 = 302

### 8 · The AI Data Protocol

- The AI Data Protocol: Specify → Generate → ____ → Analyze → Log.  
  Answers: blank 1 = verify
- The AI's plain-English statement of exactly what it built into the data is the ____ Statement.  
  Answers: blank 1 = truth
- Keep total N at ____ or below when you generate, or the table gets cut off.  
  Answers: blank 1 = 150
- The log has four parts: the prompts, what came back, what was ____, and what you did about it.  
  Answers: blank 1 = wrong / incorrect / off
- Step 4, Analyze, is ____ alone. AI does not interpret output.  
  Answers: blank 1 = yours / mine / your own / the student's

### 9 · APA reporting

- The APA opener: "To determine whether ___, I ran a ___ and ____ ___."  
  Answers: blank 1 = found
- No leading ____ on p, r, or η², because they cannot exceed 1.  
  Answers: blank 1 = zero / 0
- df for a correlation is n − ____.  
  Answers: blank 1 = 2 / two
- Statistical symbols such as M, SD, t and p are set in ____.  
  Answers: blank 1 = italics / italic
- Every results statement has three parts: what you did, what you ____, and what your evidence is.  
  Answers: blank 1 = found

### 10 · SPSS

- Click ____ instead of OK so the command lands in a Syntax window. [Psy 210 only]  
  Answers: blank 1 = paste
- SPSS file types: .sav is data, .sps is ____, .spv is output. [Psy 210 only]  
  Answers: blank 1 = syntax / the syntax / syntax file / commands
- Reverse scoring on a 7-point item: new = ____ − item. [Psy 210 only]  
  Answers: blank 1 = 8 / eight
- After Select Cases, reset to ____ Cases before the next analysis. [Psy 210 only]  
  Answers: blank 1 = all
- In Variable View, Measure is Nominal, Ordinal, or ____. [Psy 210 only]  
  Answers: blank 1 = scale
- In Tests of Between-Subjects Effects, read your factor's own row, not ____ Model or Intercept. [Psy 210 only]  
  Answers: blank 1 = corrected
- Cronbach's α from .80 to .89 is ____. [Psy 210 only]  
  Answers: blank 1 = good
- In the Coefficients table the intercept is the B in the ____ row. [Psy 210 only]  
  Answers: blank 1 = constant
- SPSS labels the p value "____." in its output tables. [Psy 210 only]  
  Answers: blank 1 = sig / sig. / significance
- One-Sample T Test: the known comparison figure goes in the ____ Value box, never left at 0. [Psy 210 only]  
  Answers: blank 1 = test

### 11 · Excel tools

- The Excel function that turns a raw score into a z is ____. [Psy 215 only]  
  Answers: blank 1 = standardize / =standardize
- =NORM.S.DIST(z, ____) gives the proportion of the curve below z. [Psy 215 only]  
  Answers: blank 1 = true / 1
- Excel has no one-sample t function; after building t by hand, get p with =____(ABS(t), n − 1). [Psy 215 only]  
  Answers: blank 1 = t.dist.2t / tdist2t / t dist 2t
- In Excel, split a pasted CSV with Data → Text to ____. [Psy 215 only]  
  Answers: blank 1 = columns
- Excel's regression line on a scatterplot is called a ____. [Psy 215 only]  
  Answers: blank 1 = trendline / trend line
- CORREL returns r; you ____ it yourself to get r². [Psy 215 only]  
  Answers: blank 1 = square
- CHISQ.TEST returns p only; compute χ² yourself as the sum of (observed − expected)² ÷ ____. [Psy 215 only]  
  Answers: blank 1 = expected / e

## 3 · Work it (numeric drills)

Numbers are regenerated every time. One example of each, with the worked solution.

- **z** (Seeing): A test has M = 76 and SD = 5. What is the z-score for a raw score of 73?  
  Answer: z = -0.6  
  Worked: z = (X − M) ÷ SD = (73 − 76) ÷ 5 = -0.60. Inside ±1.96: not unusual.
- **raw** (Seeing): M = 68, SD = 5. What raw score has z = 2?  
  Answer: X = 78  
  Worked: X = M + z·SD = 68 + (2)(5) = 78. Check: a positive z must land above the mean, and it does.
- **twoexams** (Seeing): Exam A: you scored 76 (class M = 66, SD = 9). Exam B: you scored 86 (class M = 76, SD = 4). Compute both z-scores. The higher z is the better performance.  
  Answer: z for A = 1.11; z for B = 2.5  
  Worked: zA = (76 − 66) ÷ 9 = 1.11; zB = (86 − 76) ÷ 4 = 2.50. Exam B was the better performance relative to the class, whatever the raw numbers said.
- **meanmed** (Seeing): Five scores: 35, 40, 39, 41, 37. Give the mean and the median.  
  Answer: Mean = 38.4; Median = 39  
  Worked: Sum = 192, ÷ 5 = M = 38.4. Ranked: 35, 37, 39, 40, 41, middle score = median = 39. No outlier here, so mean and median sit close together.
- **se** (Seeing): A population of scores has SD = 17. For samples of n = 49, how much does the sample mean bounce? Give the standard error (SD ÷ √n).  
  Answer: SE = 2.43  
  Worked: SE = 17 ÷ √49 = 17 ÷ 7 = 2.43. Quadruple n and the bounce halves. That is why the n = 100 means huddle and the n = 15 means scatter.
- **dfchi** (A categorical DV): A chi-square test of independence on a 2 × 3 table. What is df?  
  Answer: df = 2  
  Worked: df = (rows − 1)(columns − 1) = (1)(2) = 2. If the output shows anything else, somebody's table is not 2 × 3.
- **expgof** (A categorical DV): 130 students chose among 5 class times. Under the null of equal preference, what is the expected count for each option?  
  Answer: Expected per category = 26  
  Worked: Equal across 5 categories: 130 ÷ 5 = 26 each. "Equal" was a decision; a known population split or a control group would give different expected counts.
- **expind** (A categorical DV): In a crosstab the row total is 76, the column total is 83, and N = 225. What is the expected count for that cell?  
  Answer: Expected count = 28.04  
  Worked: row × column ÷ N = 76 × 83 ÷ 225 = 28.04. Above 5, so this cell is fine for the test.
- **dfpair** (A score, two levels): A paired-samples t on 37 participants measured twice (so 74 scores in the file). What is df?  
  Answer: df = 36  
  Worked: df = pairs − 1 = 37 − 1 = 36. Not 72: the two columns are the same people. Check df against the design every time.
- **dfind** (A score, two levels): An independent-samples t with 14 people in one group and 17 in the other. What is df (equal variances assumed)?  
  Answer: df = 29  
  Worked: df = n₁ + n₂ − 2 = 14 + 17 − 2 = 29.
- **dfone** (A score, two levels): A one-sample t with n = 42. What is df?  
  Answer: df = 41  
  Worked: df = n − 1 = 41.
- **d** (A score, two levels): Two groups differ by 8 points and the (pooled) standard deviation is 15. What is Cohen's d?  
  Answer: d = 0.53  
  Worked: d = difference ÷ SD = 8 ÷ 15 = 0.53: medium by the benchmarks, which are benchmarks, not laws.
- **eta** (More levels, more IVs): From a ToolPak ANOVA table: SS between = 106, SS within = 384. Excel will not give you η². Build it: what is η²?  
  Answer: η² = 0.22  
  Worked: SS total = 106 + 384 = 490. η² = SS between ÷ SS total = 106 ÷ 490 = 0.22: 22% of the variance in the DV goes with group. Large by the benchmarks.
- **bonf** (More levels, more IVs): A one-way ANOVA with 4 groups came out significant. How many pairwise comparisons are there, and what alpha does Bonferroni give each one (overall .05)?  
  Answer: Comparisons = 6; Alpha per comparison = 0.01  
  Worked: Pairs: k(k − 1) ÷ 2 = 4(3) ÷ 2 = 6. Bonferroni: .05 ÷ 6 = 0.00833 for each. Rolling the dice 6 times is why you do not just run 6 t tests.
- **cells** (More levels, more IVs): A 2 × 3 between-subjects design. How many IVs, and how many cells?  
  Answer: IVs = 2; Cells = 6  
  Worked: Two numbers, so 2 IVs: one with 2 levels, one with 3. Cells = 2 × 3 = 6. Each cell gets its own mean on the interaction plot.
- **r2** (Association): r = 0.3. What proportion of the variance in one variable is predictable from the other?  
  Answer: r² = 0.09  
  Worked: r² = (0.3)² = 0.09: about 9% of the variability is shared. 
- **yhat** (Association): Sleep is predicted from screen time (hours) and caffeine (mg) by Ŷ = -0.4X₁ + -0.02X₂ + 10, built on data where screen time ran from 1 to 10 hours. Predict sleep for X₁ = 9 hours and X₂ = 93 mg. (Then ask whether you could report a prediction for X₁ = 30.)  
  Answer: Ŷ = 4.54  
  Worked: Ŷ = -0.4(9) + -0.02(93) + 10 = 4.54 hours. Each slope holds the other predictor constant. For X₁ = 30 you can compute -3.86, but it is outside the data's range: extrapolation. "I can compute it" and "I can report it" are different sentences.
- **dfr** (Association): A correlation on 59 students. What df goes in r(df)?  
  Answer: df = 57  
  Worked: df for r is n − 2 = 57. Eighty students gives r(78), not r(80).
- **rev** (SPSS [Psy 210 only]): A reverse-keyed item on a 7-point scale. A participant answered 1. What is the reverse-scored value, and what number do you subtract from?  
  Answer: Reversed value = 7; Subtract from = 8  
  Worked: New = (max + 1) − item = (7 + 1) − 1 = 8 − 1 = 7. The 8 comes from the response scale, not from how many items there are.
- **chistat** (A categorical DV): Observed counts across four rows: 36, 27, 18, 39 (N = 120), expected equal. CHISQ.TEST gives only p. Compute the χ² statistic yourself: the sum of (O − E)² ÷ E.  
  Answer: χ² = 9  
  Worked: E = 120 ÷ 4 = 30 each. (36 − 30)² ÷ 30 = 1.2; (27 − 30)² ÷ 30 = 0.3; (18 − 30)² ÷ 30 = 4.8; (39 − 30)² ÷ 30 = 2.7. Sum = 9, df = 3.
- **expknown** (A categorical DV): Barnaby Bloop surveys 100 households on pet type and compares with the national pattern of 60% dog, 30% cat, 10% other. What are the three expected counts?  
  Answer: Dog = 60; Cat = 30; Other = 10  
  Worked: A known population: 100 × .60 = 60, 100 × .30 = 30, 100 × .10 = 10. "All categories equal" would have been the wrong decision here.
- **variance** (Seeing): SD = 8.1. What is the variance?  
  Answer: Variance = 65.61  
  Worked: Variance = SD² = 8.1² = 65.61, in squared units, which is why SD is what gets reported.
- **dfanova** (More levels, more IVs): A one-way ANOVA with 4 groups and N = 160. What two df go in F(df1, df2)?  
  Answer: df between = 3; df error = 156  
  Worked: Between = groups − 1 = 3; error = N − groups = 160 − 4 = 156. F(3, 156). The first df tells a reader how many groups you had.
- **slopeapply** (Association): In a regression with two predictors, the slope for X₁ is b₁ = -1.25. If X₁ increases by 3 units and X₂ stays the same, how much does predicted Y change?  
  Answer: Change in Ŷ = -3.75  
  Worked: A slope is the change in Ŷ per one unit of its predictor, holding the other predictors constant, so 3 units changes Ŷ by -1.25 × 3 = -3.75 (a decrease).

## 4 · Which test?

The student types the test and a sentence saying why. The why is checked against the diagnosis pieces listed.

### 1 · Seeing

- Fifty students report their commute time in minutes. There is nothing to compare it with; the question is what the commute times look like.  
  Test: **Descriptives, not a test**  
  Why: the DV is a score you can average; nothing to compare it with: describe it
- Voters rank five candidates from first to fifth. Does the ranking differ between younger and older voters?  
  Test: **Off the map: Psy 302**  
  Why: the DV or IV is ordinal (ranks)  
  Note shown: Ranks are ordinal: you can order them but not average them. Off the map, Psy 302.

### 3 · A categorical DV

- Students say which they prefer: morning, afternoon or evening classes. Does one preference come up more often than the others?  
  Test: **Chi-square goodness of fit**  
  Why: the DV is counts in categories; one variable being counted
- Preference for class time (morning, afternoon, evening) is tallied separately for commuters and residents. Does preference depend on where students live?  
  Test: **Chi-square test of independence**  
  Why: the DV is counts in categories; two categorical variables
- A coin is flipped 200 times and lands heads 118 times. Is the coin fair?  
  Test: **Chi-square goodness of fit**  
  Why: the DV is counts in categories; one variable being counted
- The department expects 70% of students to pass the lab. This semester 52 of 80 passed. Is the pass rate different from what was expected?  
  Test: **Chi-square goodness of fit**  
  Why: the DV is counts in categories; one variable being counted
- Party affiliation (three parties) is recorded for voters in four regions. Is affiliation related to region?  
  Test: **Chi-square test of independence**  
  Why: the DV is counts in categories; two categorical variables
- Yes-or-no: did the participant return the lost wallet? Recorded separately for people who found it with and without a photo of a baby inside.  
  Test: **Chi-square test of independence**  
  Why: the DV is counts in categories; two categorical variables
- Dr. Wanda Wafflebottom records which of four rows each of 120 students sits in and asks whether the rows are chosen equally often.  
  Test: **Chi-square goodness of fit**  
  Why: the DV is counts in categories; one variable being counted
- Barnaby Bloop surveys 200 households on pet type and compares the split with the national pattern of 60% dog, 30% cat, 10% other.  
  Test: **Chi-square goodness of fit**  
  Why: the DV is counts in categories; one variable being counted  
  Note shown: The expected counts come from a known population, not from "equal."
- Dr. Priscilla Pemberton records each student's class standing (four levels) and preferred study location (three) and asks whether they are related.  
  Test: **Chi-square test of independence**  
  Why: the DV is counts in categories; two categorical variables
- Major (psychology, biology, business) is tallied against whether the student uses AI on homework (yes or no).  
  Test: **Chi-square test of independence**  
  Why: the DV is counts in categories; two categorical variables
- Barnaby Bloop surveys 300 people on which of four streaming services they subscribe to and asks whether the four are chosen equally often.  
  Test: **Chi-square goodness of fit**  
  Why: the DV is counts in categories; one variable being counted

### 4 · A score, two levels

- Thirty students report their average nightly sleep. Is the class different from the recommended 8 hours?  
  Test: **One-sample t**  
  Why: the DV is a score you can average; no IV; compared with a known value from outside the data
- The same 25 students complete a statistics-anxiety scale in week 1 and again in week 14.  
  Test: **Paired-samples t**  
  Why: the DV is a score you can average; one IV; two levels; the same people in every level (within-subjects)
- Students are randomly assigned to study with music or in silence, then take the same quiz.  
  Test: **Independent-samples t**  
  Why: the DV is a score you can average; one IV; two levels; different people in each level (between-subjects)
- Mood is rated before and after a walk, but the "before" ratings come from one set of people and the "after" ratings from a different set.  
  Test: **Independent-samples t**  
  Why: the DV is a score you can average; one IV; two levels; different people in each level (between-subjects)  
  Note shown: "Before and after" was the bait. Different people in each condition means independent.
- Forty employees have cortisol measured before a stress-management program and again after it.  
  Test: **Paired-samples t**  
  Why: the DV is a score you can average; one IV; two levels; the same people in every level (within-subjects)
- The class mean IQ is compared with the population value of 100.  
  Test: **One-sample t**  
  Why: the DV is a score you can average; no IV; compared with a known value from outside the data
- Two sections of the same course use different textbooks. Compare their final exam scores.  
  Test: **Independent-samples t**  
  Why: the DV is a score you can average; one IV; two levels; different people in each level (between-subjects)
- Nurses on the day shift and nurses on the night shift rate their job satisfaction on a 40-point scale.  
  Test: **Independent-samples t**  
  Why: the DV is a score you can average; one IV; two levels; different people in each level (between-subjects)
- A chip company advertises 50 chips per bag. Fernando Fizzlewick, deeply suspicious, counts the chips in 30 bags.  
  Test: **One-sample t**  
  Why: the DV is a score you can average; no IV; compared with a known value from outside the data
- Twenty-five participants complete an anxiety measure, a six-week meditation program, and the same measure again.  
  Test: **Paired-samples t**  
  Why: the DV is a score you can average; one IV; two levels; the same people in every level (within-subjects)
- Forty-five varsity athletes and forty-five non-athletes report their nightly sleep.  
  Test: **Independent-samples t**  
  Why: the DV is a score you can average; one IV; two levels; different people in each level (between-subjects)
- Fifty nurses before a management change, and fifty different nurses after it, rate their job satisfaction.  
  Test: **Independent-samples t**  
  Why: the DV is a score you can average; one IV; two levels; different people in each level (between-subjects)  
  Note shown: Looks paired, is independent. The one question that settles it: are these the same people?

### 5 · More levels, more IVs

- Three note-taking methods (longhand, laptop, none), different students in each, and an exam score.  
  Test: **One-way between-subjects ANOVA**  
  Why: the DV is a score you can average; one IV; three or more levels; different people in each level (between-subjects)
- Each participant's reaction time is measured under three caffeine doses on three separate days.  
  Test: **One-way repeated-measures ANOVA**  
  Why: the DV is a score you can average; one IV; three or more levels; the same people in every level (within-subjects)
- Caffeine (yes or no) crossed with sleep (deprived or rested), different people in every cell, and a memory score.  
  Test: **Two-way between-subjects ANOVA**  
  Why: the DV is a score you can average; two IVs; two levels; different people in each level (between-subjects)
- Does the number of typing errors differ across four keyboard layouts, when every typist uses all four?  
  Test: **One-way repeated-measures ANOVA**  
  Why: the DV is a score you can average; one IV; three or more levels; the same people in every level (within-subjects)
- Student sex (two levels) crossed with major (three majors), different students in each cell, and a quantitative-reasoning score.  
  Test: **Two-way between-subjects ANOVA**  
  Why: the DV is a score you can average; two IVs; different people in each level (between-subjects)
- Students in four dorms, different students in each, complete a 10-item belonging scale that is summed to a score.  
  Test: **One-way between-subjects ANOVA**  
  Why: the DV is a score you can average; one IV; three or more levels; different people in each level (between-subjects)
- Training (yes or no) is between-subjects, and every participant is tested at pretest and posttest. Score on a skills test.  
  Test: **Off the map: Psy 302**  
  Why: the DV is a score you can average; two IVs; the same people in every level (within-subjects); different people in each level (between-subjects)  
  Note shown: A factorial with a within-subjects IV is a mixed design. Name it and park it: Psy 302.
- Anxiety and depression are both measured as outcomes across three therapy groups and analyzed together.  
  Test: **Off the map: Psy 302**  
  Why: more than one DV  
  Note shown: More than one DV at once is MANOVA. Off the map. Or start again with each DV on its own.
- Exam score is predicted from hours studied (a score) and from section (three sections), in the same analysis.  
  Test: **Off the map: Psy 302**  
  Why: a mix of continuous and categorical IVs  
  Note shown: A mix of continuous and categorical IVs (ANCOVA territory). Psy 302.
- Dr. Persimmon Quackenbush randomly assigns 96 employees to one of four onboarding formats and measures job satisfaction.  
  Test: **One-way between-subjects ANOVA**  
  Why: the DV is a score you can average; one IV; three or more levels; different people in each level (between-subjects)
- Each of 24 typists completes the same typing test under classical music, rock music, and silence, in randomized order.  
  Test: **One-way repeated-measures ANOVA**  
  Why: the DV is a score you can average; one IV; three or more levels; the same people in every level (within-subjects)
- Participants are randomly assigned to caffeine or no caffeine, and independently to low or high sleep, then take a memory test.  
  Test: **Two-way between-subjects ANOVA**  
  Why: the DV is a score you can average; two IVs; two levels; different people in each level (between-subjects)
- Thirty people are measured at baseline, four weeks, and eight weeks, split between two therapy types.  
  Test: **Off the map: Psy 302**  
  Why: the DV is a score you can average; two IVs; the same people in every level (within-subjects); different people in each level (between-subjects)  
  Note shown: A within-subjects IV inside a factorial: a mixed design. Name it and park it for Psy 302.
- Memory score is analyzed by caffeine group (yes or no) together with age in years in the same analysis.  
  Test: **Off the map: Psy 302**  
  Why: a mix of continuous and categorical IVs  
  Note shown: Age in years is continuous; caffeine group is categorical. A mix: Psy 302.
- Dose is coded low, medium, high and treated as ranks. The DV is reaction time.  
  Test: **Off the map: Psy 302**  
  Why: the DV or IV is ordinal (ranks)  
  Note shown: An ordinal IV. Off the map, Psy 302.

### 6 · Association

- Hours of screen time and hours of sleep are recorded for the same 60 students. Are they related?  
  Test: **Pearson correlation**  
  Why: the DV is a score you can average; one continuous IV: a second score on the same people; the question is whether two scores go together
- Screen time in hours and caffeine in milligrams are both recorded for the same students and used together to predict hours of sleep.  
  Test: **Regression**  
  Why: the DV is a score you can average; two or more continuous IVs; the question is a predicted value
- Is GPA related to the number of hours students work per week?  
  Test: **Pearson correlation**  
  Why: the DV is a score you can average; one continuous IV: a second score on the same people; the question is whether two scores go together
- Study hours and sleep hours are both used together to predict exam score.  
  Test: **Regression**  
  Why: the DV is a score you can average; two or more continuous IVs; the question is a predicted value  
  Note shown: Two continuous IVs: regression. With only one of them it would be a correlation.
- Is a person's age related to how many seconds they take to solve the puzzle?  
  Test: **Pearson correlation**  
  Why: the DV is a score you can average; one continuous IV: a second score on the same people; the question is whether two scores go together  
  Note shown: One continuous IV. Even if the question says "predict", one predictor is a correlation on this map; regression begins at two.
- Winnifred Wobblesocks records hours studied and exam score for 80 students and asks whether they are related.  
  Test: **Pearson correlation**  
  Why: the DV is a score you can average; one continuous IV: a second score on the same people; the question is whether two scores go together
- Daily caffeine intake and hours of sleep are recorded for 140 adults, nothing manipulated. Are they related?  
  Test: **Pearson correlation**  
  Why: the DV is a score you can average; one continuous IV: a second score on the same people; the question is whether two scores go together
- An admissions office wants to estimate first-semester GPA from high school GPA and SAT score together, and state a predicted value for any applicant.  
  Test: **Regression**  
  Why: the DV is a score you can average; two or more continuous IVs; the question is a predicted value
- A screening-assessment score and years of prior experience are used together to predict first-year sales revenue.  
  Test: **Regression**  
  Why: the DV is a score you can average; two or more continuous IVs; the question is a predicted value
- Hours studied is used to predict exam score for 80 students. One predictor, one outcome.  
  Test: **Pearson correlation**  
  Why: the DV is a score you can average; one continuous IV: a second score on the same people; the question is whether two scores go together  
  Note shown: One continuous IV is a correlation on this map, whatever verb the scenario uses. Regression needs two or more.

Accepted names for each test: Chi-square goodness of fit (goodness of fit, chi square goodness of fit, chi-square goodness of fit, gof, chi square gof, one way chi square, chi square, chi-square); Chi-square test of independence (test of independence, chi square test of independence, chi-square test of independence, chi square independence, independence, two way chi square, chi square of independence, crosstabs); One-sample t (one sample t, one-sample t, one sample t test, single sample t); Paired-samples t (paired t, paired samples t, paired-samples t, paired t test, dependent t, dependent samples t, repeated measures t, matched pairs t, within subjects t); Independent-samples t (independent t, independent samples t, independent-samples t, independent t test, two sample t, two-sample t, between subjects t, independent groups t); One-way between-subjects ANOVA (one way anova, one-way anova, anova, single factor anova, one way between subjects anova, between subjects anova, one way between anova); One-way repeated-measures ANOVA (repeated measures anova, repeated-measures anova, within subjects anova, rm anova, one way repeated measures anova, one way within subjects anova, within anova); Two-way between-subjects ANOVA (two way anova, two-way anova, factorial anova, two way between subjects anova, 2x2 anova, 2 x 2 anova, two factor anova, 2x3 anova, 2 x 3 anova, factorial); Pearson correlation (correlation, pearson correlation, pearson r, pearson, r, bivariate correlation, pearsons r); Regression (regression, multiple regression, linear regression, multiple linear regression, regression with several predictors, regression with two or more predictors); Descriptives, not a test (descriptives, descriptive statistics, descriptive, no test, just describe, describe it, not a test, descriptives not a test); Off the map: Psy 302 (302, psy 302, off the map, off this map, off map, research methods ii, research methods 2, mixed design, mixed anova, manova, ancova, ordinal test, mann whitney, kruskal wallis, spearman, wilcoxon)

## 5 · Find the error

### 1 · Seeing

- Shown: Scores had two humps, at about 35 and 70. The report said "the typical score was M = 52."  
  Looks for: the mean of a bimodal distribution describes nobody  
  Model fix: The distribution is bimodal. The mean of 52 describes nobody; report the shape and the two centers.
- Shown: A sample of 20 students. The spread was computed with STDEV.P. [Psy 215 only]  
  Looks for: a sample uses STDEV.S (n − 1)  
  Model fix: Your data are a sample, so use STDEV.S (n − 1). STDEV.P is for a whole population, and it would understate the spread.
- Shown: Results: "The mean score was M = 24.31." That was the whole sentence.  
  Looks for: the SD is missing  
  Model fix: A mean without a spread is half an answer. M = 24.31, SD = 5.02.
- Shown: Reaction times were strongly positively skewed. A participant with z = 2.10 was described as "in the top 2.5%."  
  Looks for: the ±1.96 rule needs a normal distribution  
  Model fix: The 2.5% claim comes from the normal curve. Standardizing did not change the shape: skewed data stays skewed, so the percentile is wrong.
- Shown: "Our sample mean was 3 points off the population mean, so someone made an error collecting the data."  
  Looks for: that gap is sampling error, not a mistake  
  Model fix: That gap is sampling error: the price of not measuring everyone. Every one of those sample means can be correct and still differ.
- Shown: Travel method was coded 1 = car, 2 = bus, 3 = walk. The report says "mean travel method = 1.8."  
  Looks for: a mean of a nominal variable is meaningless; report the mode or counts  
  Model fix: Travel method is nominal. The codes are labels, not quantities, so 1.8 means nothing. Report counts per category, or the mode.
- Shown: "We used STDEV.P because it is more accurate." [Psy 215 only]  
  Looks for: STDEV.P is the population formula, not a more accurate one; a sample uses STDEV.S  
  Model fix: STDEV.P is not more accurate. It is the population formula, and you have a sample. Use STDEV.S.

### 2 · The hinge

- Shown: p = .03, "so there is a 3% chance that the null hypothesis is true."  
  Looks for: that is the wrong definition of p  
  Model fix: p is the probability of a result at least this extreme IF the null were true. It is not the probability that the null is true.
- Shown: p = .20, "which proves there is no effect."  
  Looks for: failing to reject is not proving the null  
  Model fix: Failing to reject the null does not prove it. The study may have lacked power. "No significant effect was found" is the honest sentence.
- Shown: "p = ns, so the program has no effect."  
  Looks for: no exact p; a null result is not evidence that nothing is there  
  Model fix: Two errors. Report the exact p, not "ns". And a non-significant result means the data provide no evidence of an effect, not that there is none.

### 3 · A categorical DV

- Shown: χ²(3, N = 120) = 18.53, p = .000.  
  Looks for: p is never .000; write p < .001  
  Model fix: p is never .000. Software printed .000 because p was smaller than it shows. Write χ²(3, N = 120) = 18.53, p < .001.
- Shown: A chi-square was run on a 2 × 3 table where two cells had expected counts of 2 and 3.  
  Looks for: expected counts under 5 break the test  
  Model fix: Expected counts under 5 break a chi-square, and software will not warn you. Combine categories or collect more data.
- Shown: χ²(3, N = 120) = 18.53, p The report stops there.  
  Looks for: say which cells drove it  
  Model fix: A bare significant chi-square is an announcement, not a finding. Compare observed with expected and say which categories were off, and in which direction.

### 4 · A score, two levels

- Shown: Twenty-five students were tested twice. Reported: t(25) = 3.35, p = .003.  
  Looks for: df should be pairs − 1 = 24  
  Model fix: Paired df = pairs − 1 = 24, not 25. Check df against the design every time; this is the habit that catches the most errors.
- Shown: The same 30 students rated their mood before and after a walk. The researcher ran an independent-samples t.  
  Looks for: same participants means paired  
  Model fix: Same participants measured twice: that is a paired-samples t, df = 29. "Independent" would need different people in each condition.
- Shown: t(38) = 2.30, p = .03. "The effect was large." No effect size was reported.  
  Looks for: significant is not large; report d  
  Model fix: Significant does not mean large. Report d and read it against the benchmarks; a p of .03 says nothing about size.
- Shown: Excel: T.TEST(A2:A26, B2:B26, 2, 2) for 25 students measured twice. [Psy 215 only]  
  Looks for: type should be 1 (paired)  
  Model fix: Same students twice is paired, so the type argument must be 1, not 2 (equal-variance independent).
- Shown: Independent-samples t. The student read the top row of the output without looking at Levene's test.  
  Looks for: Levene's decides which row  
  Model fix: Read Levene's first. Its p decides whether the "equal variances assumed" row is the right one. The top row is only correct if Levene's said so.

### 5 · More levels, more IVs

- Shown: Three study-method groups. The researcher ran three independent t tests, one for each pair of groups.  
  Looks for: three tests inflate Type I error; run a one-way ANOVA  
  Model fix: Three tests means rolling the Type I dice three times. Run a one-way ANOVA, then post hocs if F is significant.
- Shown: F(2, 57) = 4.10, p = .02. "Therefore the laptop group scored higher than the longhand group."  
  Looks for: the omnibus F does not say which groups differ; post hocs do  
  Model fix: A significant F says somebody differs, not who. The pairwise claim needs a post-hoc test.
- Shown: The caffeine × sleep interaction was significant. The report concludes: "Caffeine improves memory."  
  Looks for: under an interaction the main effect is misleading on its own  
  Model fix: With a significant interaction, the effect of caffeine depends on sleep. "Caffeine improves memory" may be true for one group and false for the other. Read the interaction first.
- Shown: A 2 × 3 design was described as "two IVs, each with five levels."  
  Looks for: one IV has 2 levels, the other 3; six cells  
  Model fix: Each number names one IV's levels: one IV with 2 levels, one with 3. Six cells, not five levels each.
- Shown: The omnibus F was not significant, F(2, 57) = 1.20, p = .31, but the report says Tukey shows Group 1 differs from Group 3.  
  Looks for: post hocs are not read after a non-significant F  
  Model fix: If the omnibus F says nothing differs, the post-hoc table is not yours to read. Report the F, fail to reject, and stop.

### 6 · Association

- Shown: The correlation between hours studied and exam score was r = 1.30, p < .001.  
  Looks for: r cannot exceed 1  
  Model fix: r runs from −1 to +1. An r of 1.30 is impossible: a typo, or the wrong number copied from the output.
- Shown: Data on screen time ran from 1 to 10 hours. The researcher used the equation to predict sleep for 25 hours of screen time and reported it.  
  Looks for: that is extrapolation, outside the range of the data  
  Model fix: Extrapolation. The line keeps going; the relationship may not. You can compute it, but you cannot report it as a finding.
- Shown: Screen time correlates with poorer sleep, r = −.42. "Screen time causes poor sleep."  
  Looks for: correlation does not establish cause  
  Model fix: Correlation does not say which causes which, and a third variable (stress, a job) could drive both. Say it about these variables, not as a slogan.
- Shown: A survey regression reported R² = 1.00 and the author called it an excellent fit.  
  Looks for: a perfect fit in real data is a red flag  
  Model fix: Real behavioral data never fit perfectly. R² = 1.00 means a variable predicting itself, a data error, or fabricated data. A red flag, not a triumph.
- Shown: Hours studied was used to predict exam score for 80 students. The report calls it "a regression with one predictor."  
  Looks for: one continuous IV is a correlation on this map; regression needs two or more  
  Model fix: On this map one continuous IV is a correlation: r(78), direction, strength and form. Regression begins at two or more predictors, because its point is each predictor's slope holding the others constant.
- Shown: Eighty students. Reported r(80) = .60, p < .001.  
  Looks for: df for r is n − 2 = 78  
  Model fix: df for a correlation is n − 2. Eighty students gives r(78), not r(80).

### 8 · The AI Data Protocol

- Shown: The log says "nothing was wrong." Verify was skipped and no Truth Statement was requested.  
  Looks for: verify was skipped; no Truth Statement means no answer key  
  Model fix: Unverified data cannot be logged as clean, and without a Truth Statement nothing can be graded. Verify (count, range, structure, descriptives, the truth), request the Truth Statement, then log what was wrong and what you did.

### 9 · APA reporting

- Shown: t(38) = 2.30, p  The output showed Sig. = .027.  
  Looks for: report the exact p when you have it  
  Model fix: You have the exact value, so report it: p = .027. "p < .05" throws away information you had.
- Shown: "There was a significant effect, p = .02." That was the whole results sentence.  
  Looks for: name the test, the variables, the direction and the statistic  
  Model fix: Three parts, every time: the test you ran, the finding in plain words with the direction and your variables, and the statistic with df, exact p and effect size.

### 10 · SPSS

- Shown: One-Sample T Test run with the Test Value left at 0, to see whether sleep differs from the national 7.0 hours. [Psy 210 only]  
  Looks for: the Test Value should be 7.0  
  Model fix: With Test Value at 0 you tested whether mean sleep differs from zero. Enter 7.0, the known figure from outside the data.
- Shown: Reliability analysis was run by entering the scale mean into the items list. [Psy 210 only]  
  Looks for: enter the items, not the scale mean  
  Model fix: Reliability is agreement among items. Enter the correctly scored items; a scale mean has no items left in it.
- Shown: The scale mean was computed with MEAN(item1 … item11) before item4 and item7 were reverse-scored. [Psy 210 only]  
  Looks for: reverse first, verify, then average  
  Model fix: Reverse first, verify the recode, then average. A scale mean built from unreversed items looks fine and is wrong.
- Shown: Select Cases was used to look at |z| > 3 suspects. The t-test was run next, without resetting to All Cases. [Psy 210 only]  
  Looks for: reset to All Cases first  
  Model fix: Every analysis after Select Cases runs on the selected rows until you reset. The t-test ran on the suspects only. Reset to All Cases and rerun.
- Shown: From Tests of Between-Subjects Effects, the student reported the Corrected Model row as the effect of Group. [Psy 210 only]  
  Looks for: read the factor's own row  
  Model fix: Your factor has its own named row. Corrected Model and Intercept are not it. Read Group's F, df, Sig. and partial η², with Error supplying the second df.
- Shown: Imported from Excel and went straight to Analyze. ParticipantID is set to Scale and Group has no value labels. [Psy 210 only]  
  Looks for: go to Variable View first: fix Measure and Values  
  Model fix: The import worked; that does not mean it worked correctly. Go to Variable View: ParticipantID and Group are Nominal, and Group needs value labels from the spec.

## 6 · The map

- Counts · one variable → **Chi-square goodness of fit**
- Counts · two variables → **Chi-square test of independence**
- Score · no IV · a known value from outside the data → **One-sample t**
- Score · one IV · two levels · different people → **Independent-samples t**
- Score · one IV · two levels · the same people → **Paired-samples t**
- Score · one IV · three or more levels · different people → **One-way between-subjects ANOVA**
- Score · one IV · three or more levels · the same people → **One-way repeated-measures ANOVA**
- Score · two IVs · both between-subjects → **Two-way between-subjects ANOVA**
- Score · one continuous IV (a second score on the same people) → **Pearson correlation**
- Score · two or more continuous IVs → **Regression**

Off the map, Psy 302: a mix of continuous and categorical IVs · an ordinal DV or IV · more than one DV (MANOVA) · a within-subjects IV in a factorial (mixed ANOVA) · three or more IVs.
