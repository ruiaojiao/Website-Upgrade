---
layout: post
title: "The Recovery of U.S Restaurant Industry In 2021"
subtitle: "How well the restaurant industry is recovering in 2021 with the impact of COVID-19?"
background: '/img/posts/restaurant_covid/res.jpg'
thumbnail: '/img/posts/restaurant_covid/fig_1.png'
---
<div class="col-lg-8 col-md-10 mx-auto" markdown="1">
U.S Restaurant industry of all could be affected by the pandemic the most due to the nature of the industry. It would be interesting to see how well the restaurant industry is recovering from Covid-19, more importantly, what is helping its recovery?


### **Data**

Data of restaurant open for seated dinner is released by OpenTable. It is collected from restaurants of its own platform. The data is starting from Jan 28th, 2020 to  Oct 28th, 2021. Over 50 restaurants are recorded and the result is calculated into a percentage by comparing its year over year comparison. 

For example, of all restaurants that are recorded on OpenTable, the number of restaurants that are open for seated dinner on Jan 28th, 2019 is divided by the number of restaurants that are open for seated dinner on Jan 28th, 2020 and 2021. 0 % means that the same amount of restaurants are open on that day comparing to the same day in 2019. 

### **Findings**

By comparing time series data of restaurant open for seated dinner, COVID-19 positive test cases and vaccination, I am
able to 
- Identify <strong class="covid">crucial moments</strong> when the recovery happens in different states.

- Discover that the U.S restaurant industry is <strong class="covid">slowly recovering </strong> from the pandemic, but the <strong class="covid"> impact of it is severe</strong>. 

- <strong class="covid">Vaccinations</strong> greatly boost the confidence for owners to reopen but the policy of mask order during the pandemic does not seem to affect the industry significantly.

![U.S restaurant industy in recovery overivew](/img/posts/restaurant_covid/fig_1.png "U.S restaurant overview")

From the figure, the daily test positive cases does not show a dramatic increase, it does indicate that it is the start of the pandemic season. Then at the end of 2020, the restaurant industry is taking another hit while the whole country is experiencing its worst impact. Throughout the whole 2020, the trend of daily positive test cases is <strong class="covid">increasing</strong> and the trend of restaurants reopen is <strong class="uber">decreasing</strong>. There is no doubt that the whole industry is <strong class="covid">heavily damaged</strong> by the virus since the daily open percentage is never even close to what it was in 2019 at any given day in 2020. However, the trend changes in 2021 with <strong class="covid">help of vaccinations</strong>. By comparing all three line charts, the pandemic has another peak in September but the recovery of the industry is more stable comparing to last year. It could be the reason that more than half of people are vaccinated and are confident that the virus can be under control over the time. 

<div class="col-lg-8 col-md-10 mx-auto" markdown="1">
Considering the difference of population in different states, I have picked two states from <strong class="covid">top 5 most populated states</strong> that have corresponding restaurant open data and those two are <strong class="covid">California</strong> and <strong class="covid">Texas</strong>. I have also picked two states from the <strong class="uber">bottom 5 least populated states</strong> that have corresponding restaurant open data and those two are <strong class="uber">Nebraska</strong> and <strong class="uber">Rhode Island</strong>. All four states’ restaurants open trend comparing to their daily positive test cases. From bar plots of all four graphs, they indicate that population rank is almost the <strong class="covid">same</strong> as the test positive cases rank. It could mean that more people are in a state, more infected case there is. It could also mean that none of them impose any effective methods to stop the pandemic. 

All four states’ industries suffer a big drop at the start of the pandemic even though positive test cases does not show a drastic increase right away. And during the <strong class="covid">winter in 2020</strong>, the restaurant industry of all four states are at another bottom. However, having less population seems to have a faster recovery speed for the industry especially during the year of 2020. In 2021, however, four different states show different patterns due to various reasons.  Except California, the other three states show that the restaurant industry is recovering to almost the same level as in 2019, which can be considered to be <strong class="covid">back to normal</strong>. By having the most population of all  states in the country, <strong class="covid">California</strong> restaurant industry is still slowly climbing back to the normal stage.

![The mask order](/img/posts/restaurant_covid/fig_6.png "The mask order")

Another potential reason could be <strong class="policy">policy</strong> imposed by different states. Figure shows<strong class="covid"> the difference of vaccination rate and mask order in four different states</strong>. California, having the most population and the most vaccinated population, is still the slowest for the recovery process; it is also the only state that imposes Mask Order throughout the whole time. It is clear that the vaccination rate in all four states has over 50% and it provides a <strong class="covid"> huge boost</strong> for the restaurant industry. On the other hand, the mask order does not seem to affect the industry recovery at all, rather it shows the state of the pandemic. More importantly, the difference between California and Texas shows that there are some other reasons that delay the restaurant recovery. 

 <br/><br/>
 

> Python pacakges that are used:
> - pandas
> - matplotlib
> - seaborn
> 
> <a href="/pdf/project_python_code.pdf" target="_blank">Python code</a>
</div>



