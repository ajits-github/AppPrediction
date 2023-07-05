# AppPrediction
Design a model to predict the likelihood of installation of an app based on the available parameters

The data (CSV file) contains information on all the ads a user has seen, including the expenditure to show the ad to the user and the earning from the user. The following table details the key
information regarding the data:

| Column | Description |
| -------- | -------- |
| install  | 0 or 1 with 1 indicating an installation |
| user id  | Unique ID of the users |
| game app  | Unique ID of the gaming app the user was active in and the platform at which the user saw the ad |
| country | Country of the user |
| advertiser | Unique ID of the advertiser |
| createdat | Unix timestamp in UTC and second |
| spending | The spending amount in USD |
| earning | The earning amount in USD |
| age | 1, 2, 3, 4, 5, for 18-30, 30-40, 40-50, 50-60, 60-70 |
| User quality score | 1, 2, 3, with 1 being the highest, 2 mid-range and 3 the lowest quality |
| carrier | Mobile carrier that the user is using |
| mccmnc | Mobile country code information that is coming from the user device |


Conversion rate is defined as the total number of installs for all the seen ads.

* Q1: Which game app has had the best performance in terms of spending, earning, and the
number of installs?
* Q2: In which country, game, and for which advertiser, we had the highest conversion rate? Why
we cannot trust this number fully?
* Q3: Plot the conversion rate per country per calendar date for all the datasets.
* Q4: Design a model to predict the likelihood of installation based on the available parameter.
What is the accuracy of the model and what are the other metrics that might be useful here?
