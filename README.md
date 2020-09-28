#  **Weather Analysis Using Python and GoogleMaps API**

**Weather Analysis:** Created a dataset of 500+ random cities using OpenWeatherMap API to analyze weather patterns as a function of equatorial distance.  
**Vacation Analysis:** Filtered cities based on weather variables and used GoogleMaps API to find ideal vacation spots. 

Data Analysis, linear regression and visualizations conducted using Python, Pandas, Citipy, Plotly, and Matplotlib.

<project visuals>

## **Weather Analysis**

### **Step 1:**
Used Python, Numpy, and Citipy to generate a list of 500+ cities based on random latitude and longitude coordinates.  

<city list>
  
### **Step 2:**
Made an API call (get request) on 7/12/2020 to OpenWeatherMap to grab weather data for each of the cities which was then converted into a pandas dataframe.

<OpenWeatherAPI>
  
### **Step 3:**


<Linear Regression>
  
### Weather Observations:

1. There is a significant correlation between latitude and Max Temp as run on July 12, 2020, so that the further away from the equator, the warmer the max temperature.  The effect size is stronger in the southern hemisphere (r2 = .65), than in the northern (r2 = .44)

2. Latitude is not a significant preditor of Humidity, Cloudiness, or Wind Speed

3. It would be interesting to run the same numbers or these variables in the winter to see if time of year impacts the strength of the relationships between the variables.
