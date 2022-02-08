<p align="center">
# The Pandemic’s Path: Predicting Future Covid-19 Cases in Midwestern States Using Machine Learning Methods

#### Brenda Li
#### Sophia Mlawer
#### Michelle Orden
</p>

## Executive Summary

The coronavirus pandemic has taken the lives of over 3.5 million people worldwide, spread through virtually
every country, and changed many aspects of our world1. A major challenge that the pandemic has posed is the
lack of knowledge of what comes next. Many policy decisions such as mask mandates, stay at home orders, and
virtual schooling rely on the knowledge of how many Covid-19 cases are to be expected in the coming week.
The prediction of future Covid-19 cases is a complex task, as many factors contribute to the spread of the virus.
In this report, we attempt to predict Covid-19 cases for a given week in the Midwest states of Illinois, Ohio, and
Missouri using various machine learning models. To do so, we collected data on the number of Covid-19 cases,
the number of Covid-19-related deaths, vaccine administration counts, public mask mandates, hospital
utilization, mobility, and demographics information for each county in these states, dating from July 2020 to
May 2021. With the successful prediction of future Covid-19 cases, policy makers and state/county leaders can
better prepare their respective counties for what’s to come.

## Background and Overview of your Solution

Now over a year into this global pandemic, we have seen the destructive effects of Covid-19 on countries all
across the globe. Covid-19 has taken over 3.5 million lives, overwhelmed hospital networks, disrupted
schooling and education, wreaked havoc on economies, and affected our lives in all imaginable ways. At the
beginning of the pandemic, part of the challenge of controlling the spread of the virus was not knowing where
the next Covid-19 outbreak would occur. Unlucky states like New York2 faced harrowing outbreaks that
debilitated their hospital systems while other states worried about whether they would be next. A year into the
pandemic, the U.S now has a better handle on containing outbreaks. Through the combination of restrictions,
public health mandates, and a massive vaccination campaign, Covid-19 cases are currently declining in both
number and severity in the U.S. However, health experts caution that the pandemic is still far from over34,
especially with the rise of dangerous variants that have devastated other countries like India5. Experts anticipate
that the U.S. will continue to see seasonal peaks and surges throughout at least the next few years6. Therefore,
predicting future Covid-19 cases remains an important problem and it’s one we can leverage machine learning
methods for.

Our machine learning model predicts Covid-19 cases a week into the future at the county level using
regression-based machine learning techniques and a variety of different information for each county. This data
includes information on current Covid-19 cases, hospital utilization, mobility, and general demographics. We
were also able to explore using data about vaccinations and public mask mandates, though they were not
incorporated into our final model due to their lack of predictive strength (see Section 5).

Using the predictions from this model, county level health officials can forecast whether Covid-19 is expected to
flare up in their county and decide whether to reinstate social distancing measures and pandemic-related
restrictions. Since Covid-19 restrictions are tentatively being lifted across the country right now, these
predictions will be important in helping county level health officials prepare for the return of any Covid-19
surges and allow them to proactively reinstate restrictions as needed.

In order to train our models on the most complete data possible, we restricted our model to focus on the three
Midwest states of Illinois, Missouri, and Ohio. Each of these states have had varying experiences with the
pandemic. They’ve each experienced numerous surges in Covid-19 cases, deaths, and hospitalizations (see
Figures 1-3 in appendix) and taken varying approaches to controlling the virus. For instance, Illinois and Ohio
implemented a public mask mandate early on in the pandemic while Missouri never instituted such a mandate.
Ohio captured headlines in early May when it was the first state to announce a lottery incentive for vaccinations.
