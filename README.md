# covid19
Analysis of Covid-19 cases based on data reported on the European CDC website. The data is updated once weekly every Thursday and can differ from other sources because the reporting times for each country varies.

In 2020, the data was published on a daily basis and the move to a weekly update was in December.

* _cv19_weekly.ipynb:_ Dashboard notebook for the weekly data
* _ecdc_2021_10.csv:_ Sample weekly data file asof Mar 2021 (week 10)

* _cv19_daily.ipynb:_ Dashboard notebook for the daily data
* _ecdc_20201214.csv:_ Sample daily data file for



### Modification History

- 26 Mar 2020: Intial version
- 27 Mar 2020: Mods for new ECDC file format
- 30 Mar 2020: Added generic chart() function; added pm_cases and pm_deaths (per million of population)
- 11 Apr 2020: Added moving averages / new definition of fatality7 metric implemented
- 07 May 2020: rpt_daily_stats() modified to filter countries (default is cum_deaths > 100)
- 19 May 2020: Stop parsing Excel date; use other fields instead. Added consolidation at continent level
- 28 Dec 2021: Modifications for the new weekly data format
