# COVID-19 and stocks interactive visualization. 

## Pseudo Random Team #5


<p style="text-align: right">
Sanzhar Yeleuov (@yelsanya) </p>


<p style="text-align: right">
Nazarbek Altybay (@na2a)</p>

## Demo

https://yelsanya.github.io/IVPROJECT.html

##	Plan



1. Introduction
2. Related Work
3. Goal
4. Methods of visualization
5. Use case
6. Future work
7. Conclusion
8. References
### Introduction
COVID-19 started as a virus in Wuhan and became a pandemic. As SARS-CoV-2 is highly infectious, global quarantine and self-isolation for both countries and their citizens are the best-found solutions for now. Because of such measures, the global economy is suffering. We believe that COVID-19 will end someday, but after that, we must deal with the upcoming economic crisis. Governments are not able to fully minimize both the impact of the economy and virus’ spread and it is not a dilemma since human life is priceless. Our motivation is that we are interested in how COVID-19 was spread among the world, how that affected local and global economies and how different countries responded to that changes. 
### Related Work
Recent studies on the economic impact of COVID-19 face the inevitable challenge of dealing with rapidly changing circumstances. Nevertheless, there are several resources helpful in analysing effect of novel coronavirus in global economy. McKibbin and Fernando [1] is one of the earliest systematic studies of potential economic cost of COVID-19. There is a UNCTAD [4,5], which is a resource for monitoring the effects of the global pandemic on manufacturing, trade, foreign direct investment and economic growth. OECD [2,3] is also worth mentioning -- it has a lot of analysis on outbreak, including policy responses which is important while researching the data.
### Goal
In particular, we are interested in the correlation between spread rate and economic impact. Our goals are to find valuable insights from both datasets and to find other factors that helped other countries to stabilize their economy based on visualization. And what is also important, how simple visualization techniques based on limited data can be helpful in the global situations as COVID-19 pandemic. 
### Methods of Visualization
Our intention was to make supportive tool to analyze influence of the COVID-19 on the economic and the market. To achieve that we made four interactive multiple line graphs that allowed to change time period and set of countries that we want to analyze. First chart showed cumulative number of infected people starting from the picked start day until specified end day, which allowed to better see situation on that specific period of time. Next chart showed daily number of new cases. Next 2 graphs show stock prices and daily percentage change. For each of the countries, we have chosen one stock (RUS:IMOEX.ME, CHN:SSE, USA:GSPC, UK:FTSE 100, ESP:IBEX 35, ITA:FTSE MIB, KOR:KOSPI). Additionally we added parallel plot with static data about countries that doesn’t depend on period of time. Containing info about monthly new cases per million of the population, GDP change (Jan-Mar), stock price change (1 Jan - 18 May) , and monthly stocks volatility. As we made an assistance tool we added search button near date regulator that opens google page in the new tab of your browser where you can search for missing factors among news articles (we simply typed the name of the country or region in the search bar) during specified period of time. 
### Use case
Our intention was to make it easier to identify key factors affecting economy, since it is obvious that not everything made to fight consequences of the novel coronavirus disease are equally effective we made and it is not easy to find every action made by governments of different countries in the ocean of news related to covid-19 we decided to use visualization to identify trend/behavior changing dates and ease a way to search for events in news articles by specifying dates that we are interested in. This can be helpful for countries lately facing with coronavirus or for ones whose market is unstable and they want to analyze how different countries dealt with this. Or as time goes and more data will arrive we will also see which actions made only temporary improvements and which lead to permanent stabilization of situation and that data can be used in the future health crisis situations. 




![alt_text](https://raw.githubusercontent.com/yelsanya/covidvseconomy/main/images/figure1.png "image_tooltip")


	Figure 1. List of events that majorly affected volatility of market found using our tool.
  
Economies of all countries’ have suffered from COVID-19 pandemic. One of the factors to see is change in GDP. Our last parallel graph has GDP field, which is change in percentage for period of January to March, 2020. As can be seen in parallel plot, China has the worst GDP difference of -13.2% and Russia has the best of 0.6%. Even though China almost beat the pandemy in February, it was the most affected country. We thought about two factors, first is  that China was the origin of this disease and the second one that China was separated from other countries for the longest period, since when only China was affected other countries closed their borders for China and after China flattened the curve virus spreaded all around the world forcing China to isolate themself to avoid second wave. Korea is another country that flattened the curve in relatively short period of time that were affected by the virus one of the first after China, but it has GDP difference of only -0.3%. This fact supports our assumption about effect of being the origin. Another factor is that South Korea reacted immediately and beat the pandemy using aggressive testing and tracing what allowed them to minimize lethality and avoid lockdown and shutting down of the economy. Russia’s GDP hasn’t suffered and even has a little increase. We think that the reason is that COVID-19 seriously affected the Russia only by April, and the GDP data is only for first three months, as was mentioned above. One of the findings is that except for China, GDP change can be correlated with the COVID-19 rate for March. Another factor is amount of budget that government injected into economy as an anti crisis measures (which we found using our tool), which also correlates with GDP change. Regarding countermeasures against COVID-19 our tool allowed to show effectiveness of different measures, like lockdown (which is differs across countries) and test and trace. On top of that our tool allowed us to find news articles telling about measures which assisted countries from our scope to stabilize market. (Figure 1)
### Future Work
Our work relies on fixed set of countries and static dataset, mostly because we modified dataset manually in order to make it usable. It is possible to automate data preprocessing to make data always up to date as well as to not limit on small set of countries. Also we thought that making it more configurable may help simplify usage for people with different needs, by configurability we mean allow modification of size and order of the windows as well as set of  windows which are needed to an analyst. Even if we tried to find and use most appropriate financial data we understand that our lack of competence in that sphere may result in misinterpretation or misuse of the financial data and trends as well as some important data could possibly left without proper attention, which means big window for improvement. 
### Conclusion
Visualization helps to represent data differently in order to make it easier and faster to identify correlations and find hidden insights. Our simple visualization techniques allowed to find some correlations among which correlation between rapid growth of infected people and volatility of stocks. But there are some factors which are not included in datasets and our visualization tool can fasten the process of identification of moments when something not included in dataset affects the data. Since in our use case we are particularly interested in events that affect stock prices and economy our tool is showed to be very helpful in identification of such events. Our work showed that visualization can be used with incomplete or unstructured (Google) datasets in order to help to find missing parts allowing to see full picture.

### References:


1. _McKibbin, W. J., & Fernando, R. (2020). The global macroeconomic impacts of COVID-19: Seven scenarios._
2. _OECD . [https://www.oecd.org/coronavirus/en/](https://www.oecd.org/coronavirus/en/)_
3. _OECD. [https://www.oecd.org/coronavirus/country-policy-tracker/](https://www.oecd.org/coronavirus/country-policy-tracker/)_
4. _UNCTAD (2020). The COVID-19 Pandemic and the Blue Economy: New challenges and prospects for recovery and resilience. (n.d.). Retrieved from [https://unctad.org/en/PublicationsLibrary/ditctedinf2020d2_en.pdf](https://unctad.org/en/PublicationsLibrary/ditctedinf2020d2_en.pdf)_
5. _UNCTAD. https://unctad.org/en/Pages/publications.aspx_
