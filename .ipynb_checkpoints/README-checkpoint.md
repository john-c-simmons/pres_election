# Election Prediction through Logistic Regression
##### Authors: Will Cline, CeCe Lacey, John Carter Simmons
***
## Goals
* We sought to build an accurate predictor of Presidential election outcomes by county for 4 states: California, Florida, Illinois, and Texas.
* We also sought to determine as a proof of concept whether vaccination rates for the county are useful in vote outcomes.

***
## Data
We utilized 2015 and 2019 census data along with geographical and vaccination data by county in tandem with their following year’s election results.2016 data was used to predict election results of 2020
#### Sources:
* Census Data from 2015 and 2019 from Five Year American Community Survey
* Data on Kindergarten vaccination rates from individual states reported at the county level 
* Geographic data from Wikipedia 
* Election data from MIT Election Data + Science Lab

***
## Modeling Process
OSEMN: Obtain, Scrub, Explore, Model, Interpret
* Obtained data from various sources
* Scrubbed vaccination data, census data, and election data
* Explored all of our data by bringing together and feature engineering
* Model: Created baseline logistic regression model, tried random forest classifier
* Interpret

***
## Visualizations

***
### Total Votes
![Total Votes](images/Total-Votes.png)

***
### Best Model Results
![Best Model Results](images/Best-Model_Results.png)

***
### Confusion Matrix
![onfusion Matrix](images/Confusion-Matrix.png)

***
### Feature Importance
![Feature Importance](images/Feature-Importance.png)

***
### Typical Margin of Victory
![Win Margin Distribution](images/Win-Margin-Distribution.png)

***
### Counties the Model Predicted to Flip from 2016 to 2020
![Counties the Model Predicted to Flip from 2016 to 2020](images/Predicted-Flip.png)


## Next Steps
* Midterm election data may be collected and used on our same model.
* Census and vaccine data for prior years may be collected to enhance model with data of elections from 2000 onward.
* We would like to include COVID Vaccination rates in predicting midterms or 2024 general election
* In the upcoming 2024 election, predictions can be made using 2016 and 2020 data for an even more accurate prediction.

## Contacts
#### Github:
* Will: https://github.com/willcline613/
* CeCe: https://github.com/cclacey/
* John Carter: https://github.com/john-c-simmons/
#### Linkedin:
* Will: https://www.linkedin.com/in/will-cline-9924a1183/
* CeCe: https://www.linkedin.com/in/cece-lacey-13a389b8/