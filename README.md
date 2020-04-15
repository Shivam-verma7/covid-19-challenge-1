# Everything COVID

We believe that the access to right information is a critical weapon in fighting this pandemic. This project aims at building a one-stop-all-information website about COVID19. Everything COVID narrates the effect of this virus in various facets.

## Getting Started

The website is accessible through this [link](https://johnelmer.github.io/covid-19-challenge/index.html).

## Acknowledgments

The developers would like to acknowledge the following websites/organizations as sources of data:
* [World Health Organization](https://www.who.int/emergencies/diseases/novel-coronavirus-2019) - Virus Information, Symptoms, and Prevention
* [European Centre for Disease Prevention and Control](https://www.ecdc.europa.eu/en/publications-data/download-todays-data-geographic-distribution-covid-19-cases-worldwide) - Data on the geographic distribution of COVID-19 cases worldwide
* [Worldometer](https://www.worldometers.info/coronavirus/) - Country-wise distribution, cases trends, total cases in absolute numbers
* [Yahoo Finance](https://finance.yahoo.com/) - Stock Market Data
* [International Monetary Fund](https://www.imf.org/en/Publications/WEO/Issues/2020/04/14/weo-april-2020) - Worldwide GDP Outlook and Unemployment
* [Bureau of Labor Statistics](https://www.bls.gov/web/empsit/cpseea31.htm) - Unemployment by Industry
* [Trials Tracker Project by the DataLab](http://covid19.trialstracker.net/index.html) - COVID-19 Trials Tracker
* [Statista](https://www.statista.com/) - Coronavirus (COVID-19) cases in India, New Zealand, Sweden, Iceland, Japan, Romania, Norway, Finland, and Wuhan China 2020, by age group
* [Cambodia COVID Wikipedia](https://en.wikipedia.org/wiki/2020_coronavirus_pandemic_in_Cambodia#Confirmed_Cases) - Cambodia Confirmed Cases by age and gender
* [Netherlands COVID Wikipedia](https://en.wikipedia.org/wiki/2020_coronavirus_pandemic_in_the_Netherlands#Statistics) - Netherlands Confirmed Cases by age and gender
* [Italy COVID Wikipedia](https://en.wikipedia.org/wiki/2020_coronavirus_pandemic_in_Italy) - Italy Confirmed Cases by age and gender
* [Belgium COVID Wikipedia](https://en.wikipedia.org/wiki/2020_coronavirus_pandemic_in_Belgium) - Belgium Confirmed Cases by age and gender
* [Philippines COVID Wikipedia](https://en.wikipedia.org/wiki/2020_coronavirus_pandemic_in_the_Philippines) - Philippines Confirmed Cases by age and gender
* [South Korea COVID Wikipedia](https://en.wikipedia.org/wiki/2020_coronavirus_pandemic_in_South_Korea) - South Korea Confirmed Cases by age and gender
* [Spain COVID Wikipedia](https://en.wikipedia.org/wiki/2020_coronavirus_pandemic_in_Spain) - Spain Confirmed Cases by age and gender
* [Canada COVID Wikipedia](https://en.wikipedia.org/wiki/2020_coronavirus_pandemic_in_Canada#By_age) - Canada Confirmed Cases by age

The developers would also like to acknowledge the following websites for the technical components of this website:
* [HTML5 UP](http://html5up.net) - Website Template
* [Unsplash](http://unsplash.com) - Stock Photos

## Data

The following datasets have been used in the website:
### Clinical Trials

Clinical Trials data can be downloaded [here](https://github.com/johnelmer/covid-19-challenge/blob/master/data/ClinicalTrials.csv).
```
index,trial_id,registry,registration_date,start_date,retrospective_registration,sponsor,recruitment_status,phase,study_type,countries,title,intervention_type,intervention,enrollment,primary_completion_date,full_completion_date,registy_url,results_type,results_published_date,results_url,last_updated,first_seen
0,ChiCTR2000029953,ChiCTR,2020-02-17,2020-02-01,True,Zhongnan Hospital of Wuhan University,Not Recruiting,Not Applicable,Observational,China,Construction and Analysis of Prognostic Predictive Model of Novel Coronavirus Pneumonia (COVID-19),Prognosis,No Intervention,400,Not Available,2021-05-01,http://www.chictr.org.cn/showproj.aspx?proj=49217,No Results,No Results,No Results,2020-02-17,2020-08-03
...
```

### Current COVID Cases

Clinical Trials data can be downloaded [here]().
```
,"Country,Other",TotalCases,NewCases,TotalDeaths,NewDeaths,TotalRecovered,ActiveCases,"Serious,Critical",Tot Cases/1M pop,Deaths/1M pop,TotalTests,"Tests/1M pop"
0,World,"1,266,782","+65,329","69,177","+4,489","261,132","936,473","45,530",163,8.9,,
...
```

### GDP Outlook

GDP Outlook data can be downloaded [here]().
```
WEO Country Code	ISO	WEO Subject Code	Country	Subject Descriptor	Subject Notes	Units	Scale	Country/Series-specific Notes	1980	1981	1982	1983	1984	1985	1986	1987	1988	1989	1990	1991	1992	1993	1994	1995	1996	1997	1998	1999	2000	2001	2002	2003	2004	2005	2006	2007	2008	2009	2010	2011	2012	2013	2014	2015	2016	2017	2018	2019	2020	2021	Estimates Start After
512	AFG	NGDP_RPCH	Afghanistan	Gross domestic product, constant prices	Annual percentages of constant price GDP are year-on-year changes; the base year is country-specific . Expenditure-based GDP is total final expenditures at purchasers? prices (including the f.o.b. value of exports of goods and services), less the f.o.b. value of imports of goods and services. [SNA 1993]	Percent change		Source: National Statistics Office Latest actual data: 2018 Notes: National accounts data is originally compiled on the basis of a solar year, which runs from March 21 to March 20. Data is converted to calendar years for the purpose of WEO publication. National accounts manual used: System of National Accounts (SNA) 1993 GDP valuation: Market prices Start/end months of reporting year: January/December. none Base year: 2002. Base year is the solar year 2002/03 Chain-weighted: No	n/a	n/a	n/a	n/a	n/a	n/a	n/a	n/a	n/a	n/a	n/a	n/a	n/a	n/a	n/a	n/a	n/a	n/a	n/a	n/a	n/a	n/a	n/a	8.692	0.671	11.83	5.361	13.34	3.863	20.585	8.438	6.479	13.968	5.683	2.697	0.988	2.164	2.889	2.664	3.037	-3.007	4.495	2018

...
```

### World Unemployment

### Unemployment by Industry

Unemployment by Industry data can be downloaded [here]
```
WEO Country Code	ISO	WEO Subject Code	Country	Subject Descriptor	Subject Notes	Units	Scale	Country/Series-specific Notes	1980	1981	1982	1983	1984	1985	1986	1987	1988	1989	1990	1991	1992	1993	1994	1995	1996	1997	1998	1999	2000	2001	2002	2003	2004	2005	2006	2007	2008	2009	2010	2011	2012	2013	2014	2015	2016	2017	2018	2019	2020	2021	Estimates Start After
512	AFG	NGDP_RPCH	Afghanistan	Gross domestic product, constant prices	Annual percentages of constant price GDP are year-on-year changes; the base year is country-specific . Expenditure-based GDP is total final expenditures at purchasers? prices (including the f.o.b. value of exports of goods and services), less the f.o.b. value of imports of goods and services. [SNA 1993]	Percent change		Source: National Statistics Office Latest actual data: 2018 Notes: National accounts data is originally compiled on the basis of a solar year, which runs from March 21 to March 20. Data is converted to calendar years for the purpose of WEO publication. National accounts manual used: System of National Accounts (SNA) 1993 GDP valuation: Market prices Start/end months of reporting year: January/December. none Base year: 2002. Base year is the solar year 2002/03 Chain-weighted: No	n/a	n/a	n/a	n/a	n/a	n/a	n/a	n/a	n/a	n/a	n/a	n/a	n/a	n/a	n/a	n/a	n/a	n/a	n/a	n/a	n/a	n/a	n/a	8.692	0.671	11.83	5.361	13.34	3.863	20.585	8.438	6.479	13.968	5.683	2.697	0.988	2.164	2.889	2.664	3.037	-3.007	4.495	2018

...
```

## Built With

* [HTML5](https://www.w3.org/TR/2017/REC-html52-20171214/) - Website Frontend
* [HTML5UP](https://html5up.net) - Website Template
* [Tableau](https://www.tableau.com) - Data Visualizations
* [Jupyter Notebook](https://jupyter.org) - Data Wrangling IDE
* [Python](https://python.org) - Language for Data Processing

## Contributing

This project is currently not open for contributions from other developers. If you have any suggestions, please contact the developers of this website.

## Version History

* Version 1: Initial Release: April 15, 2020

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Project Disclaimer

This project is originally released as an entry submission for UC Davis MSBA COVID19 Challenge Competition.

## Authors

* **Mitesh Jain**
* **John Elmer Loretizo**
* **Shrey Shah**
* **Shivam Verma**
