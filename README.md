# Note
For the above problem statement we have tried to make a dashboard using python and extracted the information from the respective websites. This code can be run everyday to get results daily. This is  can help automate the process. Further we have also done data analytics to get important results to help traders and institutions analyze data well.
There is a shortage of datapoints in the given datasets(csv files) or lack of data so using ml algorithms creates overfitting and underfitting issues.That's why we use Python libraries for better data visualisation.
# Citbank_Hackathon
The above repository is the solution for the problem statement specified for the Hackathon.
There are 4 files in this repository:
1. NSE_200 ipynb
2. NSE_200.docx
3. Citibank_report_code.ipynb
4. report.html

# How to view the report
Download the report.html file and open it on the web browser to view the report.

# Contents
NSE_200.ipynb - This file contains the code for Data Analytics on the different csv files from Bhavcopy.zip and other csv files
along with the various plots.

NSE_200.docx - This file contains the data analytics performed on Excel. It contains the graphs of various results obtained while doing the analysis.

Citibank_report_code- This file contains the code for the report made on html.

# Assumptions made:

The analysis done is for a particular day. Whereas this can be replicated for all the days by running the code everyday at a fixed time using windows scheduler.
The target customers can be both the institutions as well as a consumer. We have used two different tools to look at a variety of different results and tried to 
analyse each part as much as possible. Some inbuilt APIS have been used to make the process faster.

References:
1. NSE website: https://www1.nseindia.com/products/content/equities/equities/homepage_eq.htm
https://www1.nseindia.com/products/content/derivatives/equities/homepage_fo.htm

2. ETA and Other financial websites 

3. Python apis and documentation for report

# Info through Bhavcopy:

List of the gainers and losers for Nifty Securities, Nifty Next 50 Securities, and for other Securities- There are 90 companies that are gainers and 47 companies that are losers at different securities.

Security-wise market data information along with the Index details-
Total trades are 2447.
Trades that happen are 2377(amount>0).
Profit happens when the trading amount is between OPEN_PRICE to HIGH_PRICE.
Loss may happen when the trading amount is between OPEN_PRICE to LOW_PRICE.
For every securities index values(Open price, low price, higher price) differ. 

# Conclusion-
All the trading done is related to the previous closed price trading. If the trading has been done during the same duration as the previous close price trading had been done, then companies will generate more profits than their exisisting profits .


Sample report screenshots:
![image](https://github.com/user-attachments/assets/44cb9e0f-68f2-4fca-9694-2cc90431eac2)


