# surfs_up
Tools used: Jupyter Notebook, VS Code. 
Programming Language: Python

## Overview of the statistical analysis
W. Avy wants more information about temperature trends before funding for opening the surf shop. Specifically, he wants temperature data for the months of June and December in Oahu,Hawaii in order to determine if the surf and ice cream shop business is sustainable year-round.

### Determine the Summary Statistics for June and December months: 
* Using Python, Pandas functions and methods, and SQLAlchemy, we will filter the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the month of June and also for December. 
* Then convert those temperatures to a list, create a DataFrame from the list, and generate the summary statistics.

The summary statistics for the month of June and December is below:

![image](https://user-images.githubusercontent.com/111020934/194429194-d4742214-7b4b-464d-ab2a-adb4f81c1618.png)
![image](https://user-images.githubusercontent.com/111020934/194429571-2c899033-f620-4f88-afd2-8f4bfe65587f.png)


## Analysis Results 
* There are 1700 and 1517 temperature records, recorded for the month of June and December.
* The average temperature is close for the month of June and December between 71 and 75 deg F.
* The minimum and maximum temperatures are close for the month of June and December.
* Hence we can say that the temperature fluctuations is very minimum. 
* This is favorable for opening Surf n' Shake shop.

## Summary
* In general the temperature records for Oahu look favorable.
* For our business to run profitably we also need to take a look at the rainfall Oahu recieved that might tamper surfing conditions and thereby bring more loss than profit.
* So, we will next check on the amount of rainfall Oahu recieved for these months and also throughout the year 2017.
* For that we calculate the minimum, maximum and average precipitation records of Oahu for June and December months. We also calculate for the entire year.

![image](https://user-images.githubusercontent.com/111020934/194689918-ae02af0b-ec83-4865-a3c2-993aeda7fe99.png)
![image](https://user-images.githubusercontent.com/111020934/194689936-2353be03-efaa-483d-9df4-91c80cab8069.png)
![image](https://user-images.githubusercontent.com/111020934/194689957-a6e59f94-fdd4-4b72-a136-9cf80879a877.png)

* The average precipitation for December is bit higher at 22% than in June which has 13%.
* Overall average precipitation througout the year is 17%.
* We plot distribution of precipitation for temperatures throughout the year and can say that it still favors the opening of Surf n' Shake in Oahu.
* There might be slow business during the winter months due to higher precipitaion.

![image](https://user-images.githubusercontent.com/111020934/194690257-c6c93744-3662-4c22-93dc-1cec8f548299.png)


