Quantitative Activity Levels and Gestational Age at Delivery: A
Prospective Cohort Study among Nulliparous Women
================
Sara Kim

**Directory**

To view the code and detailed analysis of the data, click
[here](https://github.com/gekim0519/Fitbit-Analysis/blob/master/fitbit_analysis.pdf).

**Background**

Preterm labor occurs when regular contractions result in the opening of
your cervix after week 20 and before week 37 of pregnancy. Premature
infants are at greater risk for cerebral palsy, delays in development,
hearing problems, and sight problems (1). The earlier premature birth
happens, the greater the health risks for the baby (2). There are
several risk factors for preterm labor and preterm birth. These include
having history of delivering preterm, diabetes, high blood pressure,
being pregnant with more than one baby, among many others. However, the
cause of preterm birth is often not known (3) and better understanding
of the causes and mechanisms will advance the development of solutions
to prevent preterm birth. To find if higher amount of daily activity can
reduce the risk of preterm birth, this research will assess whether the
mean number of steps/day differs between women that spontaneously
deliver preterm versus those that deliver at term. Also, we will test
whether a linear relationship exists between the number of steps/day and
preterm birth.

**Study design**

The primary exposure and outcome of the study is the mean number of
steps/day and the risk of spontaneous preterm delivery (\<37 weeks),
respectively. The sample size was 130 healthy women recruited at
Columbia University Irving Medical Center. The expected number of women
to deliver preterm spontaneously was 10 to 12 women. Both the mean and
the standard deviation (SD) of the number of steps/day remains unknown
among term births. Thus, the sample size was calculated through
simulating the number of subjects required in this prospective cohort
study to detect a difference in the number of steps/day between
spontaneous preterm cases and term births based on the following
assumptions: types I and II error rates of 5% and 10% (power of 90%),
respectively, and the average number of steps/day among term births will
be 5,000 (US average: 5,117 steps/day). With estimated SD of 750,
adjusting for potential loss of follow-up, and to compensate for the
reduced power due to statistical adjustment for potential confounders,
the sample size estimation was inflated by 25% and was calculated to be
126 subjects to see a difference of 500 steps/day. The 130 subjects were
each given a Fitbit, an activity tracker, to record their number of
steps walked per day. The subjects were to use the device daily from
their second trimester (Weeks 15-18) till their day of labor.

**Methods**

As there were high amount of observations with zeros and significantly
low numbers (below 300), only values with higher than 300 steps/day were
counted toward analysis. Median steps per day were calculated per
participant to be more robust against extreme values, especially the
ones in the lower end. Fisher’s exact test was conducted to test the
association between the higher/lower median number of steps per day and
pre-term/term birth group. Pearson’s correlation coefficient was
calculated to see whether significant correlation exists between
delivery date and median steps per day.

**Results**

Excluding one subject with a miscarriage, out of the 129 subjects, 8
subjects delivered at preterm. Based on fisher’s exact test, with
p-value of 0.7178, the test does not provide any evidence against the
assumption of independence at significance level of 5%. In other words,
we cannot confidently claim any difference in median steps for the
pre-term birth group and term-birth group. Pearson’s correlation
coefficient calculated as 0.096, had a p-value of 0.2785. At
significance level of 5%, we do not reject the null hypothesis and can
conclude that there is not significant correlation between delivery date
and median steps per day.

**Discussion**

The biggest issue of this analysis was the high records of zero and very
low steps per day and large number of missings. This was due to Fitbit
being a wearable electronic device and one can forget to put it on or
forget to charge it. This could be addressed by asking subjects whether
they were put to best rest during their pregnancy and if they were when
to filter out the observations in the lower end that are viable.
However, even one is at bed rest if they were wearing the device, it is
nearly impossible to get zero steps in a day. Thus, it is justifiable to
remove the zeros and extremely low values that are not associated with
bed rest to be removed for the analysis. Furthermore, we looked at
median values instead of means to get a more robust estimate. In the
study design, this issue could have been better dealt with if the device
also recorded heart beats. That way we may be able to record other forms
of activity than walking and get a better estimate on one’s amount of
daily activity.

Since the data for each subject was collected throughout the span of
pregnancy, another statistical analysis that can be done is longitudinal
data analysis. Even though the median of the median number of steps per
day may not differ between the two groups, they may have differed in
different time periods and it is worth looking into.

**Refrerence**

1.  “Preterm Labor and Birth: Condition Information”. National
    Institutes of Health. 3 November 2014. Archived from the original on
    2 April 2015. Retrieved 7 March2015.
2.  Preterm Labor:
    <https://www.mayoclinic.org/diseases-conditions/preterm-labor/symptoms-causes/syc-20376842>
3.  World Health Organization (November 2014). “Preterm birth Fact sheet
    N°363”. who.int. Archivedfrom the original on 7 March 2015.
    Retrieved 6 March 2015.
