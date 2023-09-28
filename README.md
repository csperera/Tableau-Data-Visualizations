# The Canadian Real Estate Market
## "Where It's Been & Where It's Going"


## Project/Goals
I have a keen interest in real estate and considering my degree is in economics and finance; and my work is in finance, Option 1 of the “Data Visualizations With Tableau” Project really appealed to me – so much so that I decided that it would be a project I would use in my personal Data Science Portfolio.  However, I was dismayed with the questionable quality of the data provided, particularly since some datasets were 6 years old, others ended in 2020 (misleading the audience) and others had questionable data from a data quality point of view.  Considering these shortcomings, I proposed to the Mentors (see Jae Duk Seo, September 21st, 2023) that I would update the datasets to present day and complete a “hybrid” of Option 1 and Option 2, answering questions that were relevant, timely and informative to the audience which happens to be anyone who would like to be involved in owning real estate – likely almost everybody!

### Goals 
With this project I wanted to accurately show where house prices have been in the last 50 years, show any trends related to this, and predict with some quantitative measure what the reduction in house prices would be in the years going forward.  Additionally, I wanted to show the trend of contributing factors including CPI and Building Permits.  Finally, I wanted to show the difference in house prices between provinces. 

## Process
My process followed the steps detailed below:
### Step 1
Finding Current Datasets:  The first issue I had was to find current datasets for House Prices, Weekly Earnings, Construction Starts, House Price Index and Consumer Price Index.  After consulting with mentors, I was able to drop the requirement for “Office Real Estate” because finding a current database was not possible. For the other requirements I located the following: 
i) Bank for International Settlements (BIS) Canadian Housing Price Index current to present day
ii) Canadian Real Estate Association House Price Index (HPI) “Canada” current to present day
iii) Canadian Real Estate Association House Price by province current to present day
iv) Stats Canada Average Weekly Earnings – current to present day
v) Stats Canada Total Building Permits – current to present day
vi) Stats Canada Consumer Price Index – current to present day
I did find some other datasets which I did download, but were not used in the project due to time constraints. 
### Step 2
Data Cleaning – many days were spent cleaning the data, deleting data which would not be usable in the visualizations, refactoring and transposing data for the vagaries of Tableau and other data wrangling issues.  I found that Tableau is not particularly data friendly, and much pre-treatment needs to occur for Tableau to accommodate the data I wanted to use. 
### Step 3
Exploratory Data Analysis – The exploratory data analysis was very exciting because we were dealing with current data which was very timely.  We did find an interesting pattern in the BIS house price data, and also interesting patterns with respect to house price decline differences depending on which province the homes were located in.  CPI and Building Permit data also showed the starts of reversals for the market at large.  I’ll go more into each of these findings in the Results section. 
### Step 4
Visualizations – In total, 3 dashboards and 7 visualizations were created to tell the story “The Canadian Real Estate Market – Where It’s Been & Where It’s Going”.  The story we told during the presentation was (if I do say so myself 😊 ) captivating and well received by the very interested audience, because all of them had an interest in where their current or future house price was headed.

## Results
### Dashboard 1:
The first page is Dashboard 1 which shows the “BIS Canadian House Prices” chart with clustering, the “CREA HPI House Prices” chart with clustering, and the DailyFX “Market Cycles” Schematic

### BIS Canadian House Prices: 
This chart is the centerpiece to the whole presentation because of the discovery I found when applying clustering to the annual datapoints.  It turns out that when you apply clustering to the datapoints, and then impose a trendline on each of the clusters, you get some surprising discoveries! The first cluster (+/- 2 standard deviations) starts at 1970 and ends about 2005 which can be considered our “cool” market accordingly shaded blue.  The second cluster and steeper trendline starts in 2006 and ends in 2016 which is our “warm” market shaded in yellow.  The third cluster starts in 2017 and ends in the 2nd quarter of 2022 which is our “hot” even steeper still trendline.  My experience in finance has shown me that markets which increase-at-an-increasing-rate are termed “Parabolic” markets and tend to have an ultimate “blow-off-top” and then crash.  It is my contention that this is what is happening now.  Using my experience in equity market analysis, it is my contention that a Fibonacci Retracement of 61.8% of the total move from cold trendline to peak will occur, reducing prices by about 38.16% on average – slightly more in Ontario and British Columbia, slightly less in Alberta and Newfoundland, but around that figure on average. 

### Dashbord 2
DailyFX Market Cycles:  This 3rd Party graphic was expressly included in the presentation to educate my audience about how market trends – particularly Parabolic markets – usually resolve.  Of particular interest was the “Euphoria” segment of the “Blow-Off-Top” phase which we went through in the 2nd Quarter of 2022, then the resulting “Bull-Trap” waypoint this past summer and the “Lower-High” waypoint that we’re just hitting now.  This schematic educated my audience about what to expect from the Market Cycle going forward. 

### CREA HPI House Prices
The CREA HPI House Prices chart translated the housing index figures from the BIS Canadian House Prices Chart into actual house prices Canada-wide.  Using clustering on this chart confirmed the presence of two trendlines (only since 2005 due to data constraint) but on precisely the same dates as indicated by BIS data which served to confirm our early findings.  On a national level, average house prices peaked in the 2nd quarter of 2022 at $780,458 and have come down since.  Ultimately, over the course of 24 to 48 months, we expect house prices to reduce to $482,619 on average nationwide which is a reduction of the aforementioned 38.16%.

### Dashbord 3
Explored a heatmap of price declines across the country by province, a study of StatsCan Building Permits and the Bank of Canada CPI rate prediction.

### Canada Heat Map
We produced a study of price reductions across the country since the peak of the real estate market in the 2nd quarter of 2022.  We found that the largest decliner was Ontario, going down an average of 18.13%, then British Columbia declining 8.02%, followed by Manitoba, Quebec and Nova Scotia all below 5%.  Surprisingly Alberta, Sasketchewan and Newfoundland all benefitted from slight price increases during this “dead cat bounce” period. 
Building Permits – Stats Canada Building Permits showed a slight increase overall mainly driven by government building permits which are not affected by the economy.  When broken out, residential building permits showed a sharp decrease with commercial/government building permits still rising. 

### Average Monthly Wages
although charted, they did not provide more resolution to our data but did serve to show an animation for display purposes. 

### CPI, CPI Rate:
The CPI and CPI rate did show a sharp reduction from 6.8% on average in 2022 down to 4.58% in 2023 with a wide prediction between 0 and 6.8% by Tableau.  My personal feeling is that it will continue lower at its present slope down to the denoted average value of 2.44%. 

## Challenges 
The major challenges involved finding the datasets that could be used during the timeframe required.  Many datasets are more short dated meaning only the last 10 years or so.  Finding 50 year datasets is difficult. Secondly dealing with the vagaries of Tableau, particularly with data import and transposition was a PITA. 

## Future Goals
As I mentioned, I intend to use this project as a portfolio piece for my Data Science Portfolio, and will continue to add segments to it including a study of Canadian Mortgage Rates and Canadian 10 Year Bond rates.  I simply ran out of time this time around. 
