
## Case study 

We will use a data set of 911 calls to determine the correlation with other variable from different data sets and will do a forecast  

### The different data sets are:

* the change of temprature over the year in the same county 
* the number of rainy days over the year in the same county  

### the forecast module :

* ARIMA 
* SARIMA

### Overview

* Created by Congress in 2004 as the 911 Implementation and Coordination Office (ICO), the National 911 Program is housed within the National Highway Traffic Safety Administration at the U.S. Department of Transportation and is a joint program with the National Telecommunication and Information Administration in the Department of Commerce.

* Montgomery County, is located in the Commonwealth of Pennsylvania. As of the 2010 census, the population was 799,874 making it the third-most populous county in Pennsylvania.

The data consist of 663K emergency 911 calls made in Montegomry County PA from 2015 to 2020 , these calls consist of three types "Traffic, EMS and Fire". 

For more information about dataset : <https://www.kaggle.com/mchirico/montcoalert>
download dataset : <https://drive.google.com/file/d/1pIBJzX2kbByBr_NMFarVddBNcE9XbuRl/view?usp=sharing>

### Variables

**lat**       latitude   

**lng**       longitude

**desc**      Description of location

**zip**       zipcode

**title**     type and subtype of emergency. *i.e EMS : Respiratory emergency*

**timeStamp** time of incident

**twp**       district

**addr**      street name and intersections

**e**         dummy variable (for indexing)



