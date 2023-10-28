### COVID-19 Cases prediction

**Evgeny Vinnichenko**

#### Executive summary
Try to predict future (as of time of recording data) COVID-19 cases based on their past number.

#### Rationale
During COVID-19 pandemic, it was important to know how many people have COVID and how many would be infected in near future to plan ahead with hospital resources, medical goods like personal masks and medicines, and social restrictions. While the former was covered by various hospitals reporting recorded cases, the latter is a task for machine learning.

#### Research Question
Given the number of reecorded cases divided per date and country, we need to build a model that can predict number of infected and fatalities in the future.

#### Data Sources
Original data source is [John Hopkins CSSE](https://github.com/CSSEGISandData/COVID-19). However, to limit the number of data downloaded and make it more interesting, I used a subset of the initial dataset, provided by Kaggle's ["COVID19 Global Forecasting (Week 4)"](https://www.kaggle.com/competitions/covid19-global-forecasting-week-4/data) competition to later check my results against other people and see how well did I do.

#### Methodology
Plan so far is to see what I can do with various types of regression (linear, despite it obviously being not suited for this, and other types) as well as ARIMA. Other methods might come up in the future and be used.

#### Results
What did your research find?

Unfortunately, nothing. The goal was to produce a good prediction model, and all my options, even ARIMA that I hoped would be the right answer, didn't profuce any good results. honestly, this is a fail that is only getting submitted due to running out of time.

#### Next steps
I suspect that my bad results stem from bad data preparation, although I am puzzled as to where exactly my mistake lies. Perhaps, this direction is worth looking into.

#### Outline of project
[Preliminary report](/Preliminary%20report.ipynb)

##### Contact and Further Information