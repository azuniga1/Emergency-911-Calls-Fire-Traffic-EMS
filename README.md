# Emergency-911-Calls-Fire-Traffic-EMS-for-Montgomery-County-PA
For this project I will be analyzing some 911 call data from [Kaggle](https://www.kaggle.com/mchirico/montcoalert). The data 
contains the following fields:

* lat : String variable, Latitude
* lng: String variable, Longitude
* desc: String variable, Description of the Emergency Call
* zip: String variable, Zipcode
* title: String variable, Title
* timeStamp: String variable, YYYY-MM-DD HH:MM:SS
* twp: String variable, Township
* addr: String variable, Address
* e: String variable, Dummy variable (always 1)

## Technology Used 
### Python Libraries 
  * pandas library
  * numpy Library
  * matplotlib
  * seaborn

## Process

I used pandas to read in the csv data set from Kaggle to create a dataframe and analyse the data

```python
data = pd.read_csv('data/911.csv')
data.head()
```
![dataframe]('dataframe.png')
