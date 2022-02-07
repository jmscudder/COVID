## Plotting publicly available COVID data for the state of Ohio. 

Most recent data: Feb 07 2022. 

#### Data source change
I have changed to using the summary data posted by the state of Ohio for the new case rate,
    new hospitalization, and new death plots. This requires an omission of the three most recent dates,
                       as the data is very incomplete. Values for the previous two weeks may change, and are flagged by a paler tone color in the plots below.
                       In general these numbers trace the daily reported numbers well, and it has the benefit
                       of reducing noise from days with no data reported, or spikes from backlog reporting. 

### 7 day averages
The 7 day averages for the daily increase in cases. If no new cases were reported, these lines would go to zero.
![](7dayaverage_cases.png)

>The average increase in reported cases for the seven days ending on Feb 04 is: 3877.0
>
>The last time cases per day were this high was Feb 03 2022: 1 day prior.
>
>The seven day average then was: 4550 cases.

>
>The last time cases per day was lower than this was Nov 03 2021: 93 days prior.
>
>The seven day average then was: 3794 cases.
>
>Feb 04 marks the lowest 7 day average in the last three weeks.

The 7 day averages for the daily increase in hospitalizations and deaths. If no new events were reported, these lines would go to zero.
![](7dayaverage_hospital.png)

>The average increase in hospitalizations per day for the seven days ending on Feb 04 is: 121
>
>Feb 04 marks the lowest 7 day average in hospitalizations in the last three weeks.

The 7 day average increase in cases, compared to the rate of first round vaccinations, second round vaccinations, and total number of vaccinations dispensed:
![](DailyVaccinationsCases.png)

### Raw data
The raw daily increase in cases, hospitalizations, and deaths. The 7 day average is shown faintly behind the raw data. If no new cases were reported, this line would go to zero.
![](DailyCases.png)

>The provisional increase in cases from Feb 03 to Feb 04: 1650.0 
>
>The last time cases per day were this high was Feb 02 2022: 2 days prior. 
>
>The case rate then was 4157 cases.
>
>The last time cases per day were lower than this was Feb 03 2022: 1 day prior. 
>
>The case rate then was 1525 cases.

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

>Today marks the lowest 7 day average positivity fraction in the last three weeks, at 15.2 percent.

### Cumulative plots
The cumulative number of cases, hospitalizations, ICU admissions, and deaths. If no new cases were reported, these lines would be horizontal.
![](Cases.png)

>The current total number of cases is equivalent to 2 people out of every 9 people in the state of Ohio having tested positive for COVID-19.

The cumulative number of hospitalizations, ICU admissions, and deaths. If no new events were reported, these lines would be horizontal.
![](Hospitalizations.png)
The cumulative number of first and second round vaccinations. If no new events were reported, these lines would be horizontal.
![](Vaccinations.png)

>The current total number of first round vaccinations represents to 8 people out of every 13 in the state of Ohio having begun their vaccination sequence.
>This is 61.43 percent of the population of Ohio.

>The current total number of second round vaccinations represents 17 people out of every 30 in the state of Ohio having completed their vaccination sequence.
>This is 56.6 percent of the population of Ohio.

>Currently fully vaccinated (2 weeks past a second dose) are: 6,562,217 people, who received their second round vaccination on or before Jan 30 2022.
>This represents 56.09 percent of the population of Ohio.

>Currently maximally protected are: 3,263,355 people, who received their third vaccination dose on or before Jan 30 2022.
>This represents 27.89 percent of the population of Ohio.

