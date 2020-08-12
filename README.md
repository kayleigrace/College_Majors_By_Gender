# Interrogating College Data on Graduates
## *A data analysis of college graduates and their majors sorted by gender, STEM and non-STEM, and median earnings.*

By Kaylei Nilson-Pierce


For this data analysis, I will be using the data sets under [College Majors](https://github.com/fivethirtyeight/data/tree/master/college-majors "College Majors Data Set") provided by [FiveThirtyEight's Github Repository](https://github.com/fivethirtyeight/data "FiveThirtyEight Repository Homepage"). This data was provided by the contributer [Ben Casselman](https://github.com/BenCasselman "Ben's Homepage"). Ben Casselman also wrote an article, ["The Economic Guide to Picking A College Major"](https://fivethirtyeight.com/features/the-economic-guide-to-picking-a-college-major/) using the same data sets. 


All of the data is from [American Community Survey 2010-2012 Public Use Microdata Series](https://www.census.gov/programs-surveys/acs/data/pums.html). The major categories are from [Carnevale et al, "What's It Worth?: The Economic Value of College Majors."](https://cew.georgetown.edu/cew-reports/whats-it-worth-the-economic-value-of-college-majors/) Georgetown University Center on Education and the Workforce, 2011. 

I used the CSV files: ["recent grads"](https://github.com/fivethirtyeight/data/blob/master/college-majors/recent-grads.csv) and ["women stem"](https://github.com/fivethirtyeight/data/blob/master/college-majors/women-stem.csv). 


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


In light of COVID-19, my mother who is a high school English teacher was able to transition to part-time for this up-coming year so she can home-school my younger sister (11) and brother (8). This propted another question for me:


What are the most popular majors that people work part-time in and what is the gender breakdown?


Luckily, this data was very clean and well-organized so I got straight to work with creating pivot tables to help answer my questions.

To answer my first questions about gender break down in STEM major and all majors I created a pivot table and pie chart. This consisted of:
1. Selecting the columns I needed for my pivot table: "men," "women.
2. Selecting "Data" at the top of the page and clicking on pivot table 
3. I then added "men" and "women" to the "values" section and filtered by "sum"
4. I copy and pasted the sum values of men and women into a seperate sheet
5 *when I pasted the values on the seperate sheet it was important that I clicked "paste transpose" to be in the correct format*
6. Next, I clicked insert chart and formatted my pie chart.


#Here are the results of gender breakdown of all majors:
<iframe width="600" height="371" seamless frameborder="0" scrolling="no" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vSWWPsKkyUqWq9WohmUYfZGJezkVHpZ5DDST-ASzi6WsNHQ3HfhifdtUa3PLBzfoe8yhmbfVmafDrys/pubchart?oid=539747355&amp;format=interactive"></iframe>


#Here are the results of gender breakdown in STEM majors:
<iframe width="600" height="371" seamless frameborder="0" scrolling="no" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTllcGlSyCWm1mU_LrXc1Us3OFNgYt7Ip3udIiMjFefeYJrQhIB2RYR93cP6CYuNKcAr9gRC5rmwEpq/pubchart?oid=338628544&amp;format=interactive"></iframe>




