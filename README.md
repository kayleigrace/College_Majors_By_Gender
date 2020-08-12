# Interrogating College Data on Graduates
## *A data analysis of college graduates and their majors sorted by gender, STEM and non-STEM, and median earnings.*

By Kaylei Nilson-Pierce


For this data analysis, I will be using the data sets under [College Majors](https://github.com/fivethirtyeight/data/tree/master/college-majors "College Majors Data Set") provided by [FiveThirtyEight's Github Repository](https://github.com/fivethirtyeight/data "FiveThirtyEight Repository Homepage"). This data was provided by the contributer [Ben Casselman](https://github.com/BenCasselman "Ben's Homepage"). Ben Casselman also wrote an article, ["The Economic Guide to Picking A College Major"](https://fivethirtyeight.com/features/the-economic-guide-to-picking-a-college-major/) using the same data sets. 


All of the data is from [American Community Survey 2010-2012 Public Use Microdata Series](https://www.census.gov/programs-surveys/acs/data/pums.html). The major categories are from [Carnevale et al, "What's It Worth?: The Economic Value of College Majors."](https://cew.georgetown.edu/cew-reports/whats-it-worth-the-economic-value-of-college-majors/) Georgetown University Center on Education and the Workforce, 2011. 

I used the CSV files ["recent grads"](https://github.com/fivethirtyeight/data/blob/master/college-majors/recent-grads.csv) and ["women stem"](https://github.com/fivethirtyeight/data/blob/master/college-majors/women-stem.csv). 


The steps I took to manipulate these data sets are: 
1. I selected the "Raw" button at the top of the CSV file 
2. This opened the data in a [web browser](https://raw.githubusercontent.com/fivethirtyeight/data/master/college-majors/recent-grads.csv)
3. I then saved this data to a folder in my computer
4. Next I opened up Google Sheets and imported the saved CSV file
5. I reviewed the more detailed file of "recent grads" first and then looked over "women stem"


As a female getting a Bachelor of Science and minor in data science I was curious about questions such as:
1. Are there more females or males in STEM majors?
3. What are the top 10 most popular STEM majors for females?
2. What STEM majors have the highest median earning?


Naturally, I was also curious about the same questions for males in STEM and comparing the results.


I was also curious about the information on all majors in general such as:
1. Are there more females or males in all majors (STEM and non-STEM)?
2. What are the top 10 most popular majors for both females and males?
3. What non-STEM majors have the highest median earning?
4. Is there a correlation between median earning and college major popularity?


In light of COVID-19, my mother who is a high school English teacher was able to transition to part-time for this up-coming year so that she can also home-school my younger sister (11) and brother (8). This propted another question for me:
What are the most popular majors people graduate with and work part-time, and what is the gender break-down?


Luckily, this data was very clean and well-organized so I go straight to work with creating pivot tables to help answer my questions.


