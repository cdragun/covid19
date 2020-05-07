# covid19
Analysis of Covid-19 cases based on data reported on the European CDC website. The data is updated once daily and can differ from other sources because the reporting times for each country is different. E.g. the UK figures are a day late sometimes

* _cv19_dashboard.ipynb:_ Dashboard notebook
* _ecdc_20200327.csv:_ Sample data file for 27 Mar 2020



### Modification History

- 26 Mar 2020: Intial version
- 27 Mar 2020: Mods for new ECDC file format
- 30 Mar 2020: Added generic chart() function; added pm_cases and pm_deaths (per million of population)
- 11 Apr 2020: Added moving averages / new definition of fatality7 metric implemented
- 07 May 2020: rpt_daily_stats() modified to filter countries (default is cum_deaths > 100)


