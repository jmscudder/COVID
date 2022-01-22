## Plotting publicly available COVID data for the state of Ohio. 

Most recent data: Jan 22 2022. 

#### Data source change
I have changed to using the summary data posted by the state of Ohio for the new case rate,
    new hospitalization, and new death plots. This requires an omission of the three most recent dates,
                       as the data is very incomplete. Values for the previous two weeks may change, and are flagged by a paler tone color in the plots below.
                       In general these numbers trace the daily reported numbers well, and it has the benefit
                       of reducing noise from days with no data reported, or spikes from backlog reporting. 

### 7 day averages
The 7 day averages for the daily increase in cases. If no new cases were reported, these lines would go to zero.
![](7dayaverage_cases.png)

>The average increase in reported cases for the seven days ending on Jan 19 is: 16117.0
>
>The last time cases per day were this high was Jan 18 2022: 1 day prior.
>
>The seven day average then was: 17162 cases.

>
>The last time cases per day was lower than this was Dec 27 2021: 23 days prior.
>
>The seven day average then was: 14753 cases.
>
>Jan 19 marks the lowest 7 day average in the last three weeks.

The 7 day averages for the daily increase in hospitalizations and deaths. If no new events were reported, these lines would go to zero.
![](7dayaverage_hospital.png)

>The average increase in hospitalizations per day for the seven days ending on Jan 19 is: 215
>
>Jan 19 marks the lowest 7 day average in hospitalizations in the last three weeks.

The 7 day average increase in cases, compared to the rate of first round vaccinations, second round vaccinations, and total number of vaccinations dispensed:
![](DailyVaccinationsCases.png)

### Raw data
The raw daily increase in cases, hospitalizations, and deaths. The 7 day average is shown faintly behind the raw data. If no new cases were reported, this line would go to zero.
![](DailyCases.png)

>The provisional increase in cases from Jan 18 to Jan 19: 17787.0 
>
>The last time cases per day were this high was Jan 18 2022: 1 day prior. 
>
>The case rate then was 19475 cases.
>
>The last time cases per day were lower than this was Jan 17 2022: 2 days prior. 
>
>The case rate then was 14217 cases.

The raw daily increase in hospitalizations, ICU admissions, and deaths. The 7 day average is shown faintly behind the raw data. If no new events were reported, these lines would go to zero.
![](DailyHospitalizations.png)

### Case rates/100K 

The number of positive cases per 100,000 people in the state of Ohio (gray). This is an estimate based on the number of cases reported with onsets within the last two weeks, per 100K people.
![](7dayaverage_rate.png)
### Testing

The increase in the number of reported total tests (navy). A 7 day running average is shown in black.
![](DailyTests.png)
The percent of each day's new reported tests which represent that day's new reported cases.
![](percentpositive_tests.png)

>The lowest 7 day average reported positive test fraction per day in the last three weeks was on Jan 06 2022.
>
>This was 14 days prior. The average was 28.7 percent positive. 
>
>The current average positive test rate is 29.1 percent, a change of 1.4 percent with respect to then. 

### Cumulative plots
The cumulative number of cases, hospitalizations, ICU admissions, and deaths. If no new cases were reported, these lines would be horizontal.
![](Cases.png)

>The current total number of cases is equivalent to 3 people out of every 14 people in the state of Ohio having tested positive for COVID-19.

The cumulative number of hospitalizations, ICU admissions, and deaths. If no new events were reported, these lines would be horizontal.
![](Hospitalizations.png)
The cumulative number of first and second round vaccinations. If no new events were reported, these lines would be horizontal.
![](Vaccinations.png)

>The current total number of first round vaccinations represents to 11 people out of every 18 in the state of Ohio having begun their vaccination sequence.
>This is 61.04 percent of the population of Ohio.

>The current total number of second round vaccinations represents 14 people out of every 25 in the state of Ohio having completed their vaccination sequence.
>This is 56.02 percent of the population of Ohio.

>Currently fully vaccinated (2 weeks past a second dose) are: 6,489,503 people, who received their second round vaccination on or before Jan 14 2022.
>This represents 55.47 percent of the population of Ohio.

>Currently maximally protected are: 3,083,921 people, who received their third vaccination dose on or before Jan 14 2022.
>This represents 26.36 percent of the population of Ohio.

