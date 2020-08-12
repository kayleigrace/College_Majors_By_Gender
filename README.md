# Interrogating College Data on Graduates
## *A data analysis of college graduates and their majors sorted by gender, STEM and non-STEM, and median earnings.*

#### By Kaylei Nilson-Pierce




For this data analysis, I will be using the data sets under [College Majors](https://github.com/fivethirtyeight/data/tree/master/college-majors "College Majors Data Set") provided by [FiveThirtyEight's Github Repository](https://github.com/fivethirtyeight/data "FiveThirtyEight Repository Homepage"). This data was provided by the contributer [Ben Casselman](https://github.com/BenCasselman "Ben's Homepage"). Ben Casselman also wrote an article, ["The Economic Guide to Picking A College Major"](https://fivethirtyeight.com/features/the-economic-guide-to-picking-a-college-major/) using the same data sets. 


All of the data is from [American Community Survey 2010-2012 Public Use Microdata Series](https://www.census.gov/programs-surveys/acs/data/pums.html). The major categories are from [Carnevale et al, "What's It Worth?: The Economic Value of College Majors."](https://cew.georgetown.edu/cew-reports/whats-it-worth-the-economic-value-of-college-majors/) Georgetown University Center on Education and the Workforce, 2011. 

I used the CSV files: ["recent grads"](https://github.com/fivethirtyeight/data/blob/master/college-majors/recent-grads.csv) and ["women stem."](https://github.com/fivethirtyeight/data/blob/master/college-majors/women-stem.csv)


The steps I took to manipulate these data sets are: 
1. I selected the "Raw" button at the top of the CSV file 
2. This opened the data in a [web browser](https://raw.githubusercontent.com/fivethirtyeight/data/master/college-majors/recent-grads.csv)
3. I then saved this data to a folder on my computer
4. Next, I opened up Google Sheets and imported the saved CSV file
5. I reviewed the more detailed file of "recent grads" first and then looked over "women stem"


As a female getting a Bachelor of Science and minor in data science I was curious about questions such as:
1. Are there more females or males in STEM majors?
3. What are the top 10 most popular STEM majors for females?
2. What STEM majors have the highest median earning?


Naturally, I was also curious about the same questions for males in STEM and comparing the results.


I then asked more general questions about all majors (STEM and non-STEM) such as:
1. Are there more females or males in all majors?
2. What are the top 10 most popular majors for females and males?
3. What non-STEM majors have the highest median earning?
4. Is there a correlation between median earning and college major popularity?


In light of COVID-19, my mother who is a high school English teacher was able to transition to part-time for this up-coming year so that she can home-school my younger sister (11) and brother (8). This propted me to ask the question:


What are the most popular majors that people work part-time in and what is the gender breakdown?


Luckily, this data was very clean and well-organized so I got straight to work with creating pivot tables to help answer my questions.

To answer my first questions about gender break down in STEM major and all majors I created a pivot table and pie chart. This consisted of:
1. Selecting the columns I needed for my pivot table: "men," "women.
2. Selecting "Data" at the top of the page and clicking on pivot table 
3. I then added "men" and "women" to the "values" section and filtered by "sum"
4. I copy and pasted the sum values of men and women into a seperate sheet
5. *when I pasted the values on the seperate sheet it was important that I clicked "paste transpose" to be in the correct format*
6. Next, I clicked insert chart and formatted my pie chart.


## Gender Breakdown of STEM and All Majors


<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  
</head>
<body>

     <iframe src=""https://docs.google.com/spreadsheets/d/e/2PACX-1vTllcGlSyCWm1mU_LrXc1Us3OFNgYt7Ip3udIiMjFefeYJrQhIB2RYR93cP6CYuNKcAr9gRC5rmwEpq/pubchart?oid=338628544&amp;format=interactive"" frameborder="0" scrolling="yes"                           
                                    style="overflow: hidden; height: 100%; 
                                                width: 49%; float: left; " height="100%" width="49%"
                                   align="left">
                                  </iframe>  

     <iframe src=""https://docs.google.com/spreadsheets/d/e/2PACX-1vSWWPsKkyUqWq9WohmUYfZGJezkVHpZ5DDST-ASzi6WsNHQ3HfhifdtUa3PLBzfoe8yhmbfVmafDrys/pubchart?oid=539747355&amp;format=interactive"" frameborder="0" scrolling="yes"  
                                        style="overflow: hidden; height: 100%;
                                        width: 49%; " height="100%" width="49%"                                 
                                         align="right">
                                        </iframe>
</body>
</html>


<iframe width="600" height="371" seamless frameborder="0" scrolling="no" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTllcGlSyCWm1mU_LrXc1Us3OFNgYt7Ip3udIiMjFefeYJrQhIB2RYR93cP6CYuNKcAr9gRC5rmwEpq/pubchart?oid=338628544&amp;format=interactive" {: style="float: left"} ></iframe>


<iframe width="600" height="371" seamless frameborder="0" scrolling="no" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vSWWPsKkyUqWq9WohmUYfZGJezkVHpZ5DDST-ASzi6WsNHQ3HfhifdtUa3PLBzfoe8yhmbfVmafDrys/pubchart?oid=539747355&amp;format=interactive" {: style="float: right"}></iframe>


## STEM Majors


To find the top 10 most popular STEM majors I used a similar process of creating a pivot table, but did not need to open a new sheet or paste transpose. I copied the data from the pivot table that was filtered by descending sum of the specified gender and pasted it in Data Wrapper to format a chart. I did the same process for all majors (depicted later on).


<iframe title="Top 10  Most Popular STEM Majors Women Graduated From" aria-label="Bar Chart" id="datawrapper-chart-YuFCQ" src="https://datawrapper.dwcdn.net/YuFCQ/2/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="378"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}}))}();
</script>


<iframe title="Top 10 Most Popular STEM Majors Men Graduated From" aria-label="Bar Chart" id="datawrapper-chart-UcE0g" src="https://datawrapper.dwcdn.net/UcE0g/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="375"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}}))}();
</script>


Taking into consideration that there is a slightly higher proportion of men than women in these STEM majors (established in pie chart), it is not suprising to see slightly higher totals of men than women in the above chart. However, there is a much bigger gap in total men and women when filtering by highest median earning salary. This visualizes **correlation**, but **not causation**. It is also important to keep in mind that these charts should not reinforce or perpetuate any gender-related STEM stereotypes, instead its a place to see where more growth can occur. 


<iframe title="Top 10 Highest Median Earnings of STEM Majors" aria-label="Grouped Bars" id="datawrapper-chart-f8Ae9" src="https://datawrapper.dwcdn.net/f8Ae9/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="830"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}}))}();
</script>


## All Majors


<iframe title="Top 10 Most Popular Majors Women Graduated From" aria-label="Bar Chart" id="datawrapper-chart-a1kZj" src="https://datawrapper.dwcdn.net/a1kZj/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="422"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}}))}();
</script>


<iframe title="Top 10 Majors Most Popular Majors Men Graduated From" aria-label="Bar Chart" id="datawrapper-chart-ttuYN" src="https://datawrapper.dwcdn.net/ttuYN/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="422"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}}))}();
</script>


<iframe title="Top 10 Highest Paying Non-STEM Majors" aria-label="Grouped Bars" id="datawrapper-chart-qXUL0" src="https://datawrapper.dwcdn.net/qXUL0/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="909"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}}))}();
</script>


The chart above was a little trickier to make because when I initially went to just filter highest median earning majors of all majors (STEM and non-STEM) the top 10 were the exact same as the top 10 for the highest median earning of the STEM chart. I went through each line to find the highest earning median majors that didn't fall under any of the categories of STEM in this data set. These results were slightly suprising to me given that women are the majority in non-STEM majors; however, it is important to note that this data is from 2010-2012, and in recent years, women have been more elevated and empowered by society to pursusue higher earning jobs. It would be interesting to compare this data to present-day data and see if there are noticable changes.


## Correlation?


<iframe title="Are Majors That Have Higher Median Earnings More Popular?" aria-label="chart" id="datawrapper-chart-rOENR" src="https://datawrapper.dwcdn.net/rOENR/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="400"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}}))}();
</script>

Here is an interactive version of the [median earning and popularity chart](https://datawrapper.dwcdn.net/rOENR/1/) where you can click on each dot and see what major it is. The results of this chart depict very little correlation between the two variables. 


## Part-Time


<iframe title="Top 10 Majors With Highest Rate of Part-Time Jobs" aria-label="chart" id="datawrapper-chart-91R62" src="https://datawrapper.dwcdn.net/91R62/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="650"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}}))}();
</script>


This chart provides corroberates that my mom has a great job for switching to part-time. 7/10 of these graphs depict a higher percentage of females. These results could be due to situations like my mom where she and other females may be the primary caregivers for their kids; however, it is important to note that this data is from 2010-2012 and gender roles are constantly transforming to be more equal between women and men.


Thanks for reading !




