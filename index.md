# Global Covid-19 Vaccination Progress

Countries all over the world face difficult challenges during their fight agains further Covid-19 spreading and try to protect their citizens as much as possible.
The currently released vaccines are the new hope in order to defeat the virus and every country is trying to vaccinate as much people as possible in the shortest time.
This strategy brings new challenges with huge efforts needed in logistics and organisation. A race for vaccines has started between nations and million of people need to get vaccinated while prioritzing the risk groups.
But which countries are doing best compared globally? What influences the number of people that can get vaccinated daily? And do wealthy nations have easier access to the vaccines than others? These questions will be answered below.

The blog analyzes the progress of covid vaccination in different countries by investigation the [COVID-19 World Vaccination Progress Dataset](https://www.kaggle.com/gpreda/covid-world-vaccination-progress) from [Our World Data](https://ourworldindata.org/).
The data is enriched with [GDP per Capita Information](https://data.worldbank.org/indicator/NY.GDP.PCAP.CD) provided by the world bank and [country population information](https://population.un.org/wpp/Download/Standard/CSV/) provided by the United Nations.
The enriched dataset allows insights into the demographic and economic situations of the analysed countries and their progress on vaccinating their citizens.
The data is being transformed to optimize the analytical insights.

## Results

**Association between GDP per Capita and percent of vaccinated citizens**
<img src="GDP_vs_PercVacc.png">

**Association between population size and percent of vaccinated citizens**
<img src="PopSize_vs_PercVacc.png">

**Regression Coefficients for population size, GDP per Capita and population density**

Running a linear regression for total percentage of vaccinated citizens resulted in the following coefficients:
* **Population Size: (Negative)** -1.63475623e-06
* **GDP per Capita: (Positive)** 2.32138617e-05
* **Population Density: (Positive)** 2.81426369e-04

**Vaccines Analysis: Are there vaccines mainly accessible for countries with a high GDP per Capita?**
<img src="Vacc_plot.png">
