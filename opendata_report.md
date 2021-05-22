# Opendata-Octupi
Team Members: Jordan Shapiro, Kreeti Gulati, Nico Santoso, Anna Chiasson, Norman Chan

Central Question: Do countries that invest in digital public services also share more open source data?

* Summary:
    * Using 2014 and 2016 data from the United Nations' E-Government Survey and the World Wide Web Foundation's Open Data Barometer, we analyzed the rank of global governments through their rankings across both datasets.
    * The datasets were combined, merged, and condenced down to 79 countries in which data was collected for within both datasets. 
    * Overall, governments that ranked high on the e-services also ranked relatively high for sourcing open data. 
    * From 2014 to 2016, most governments did not improve significatly within the e-services and open data barometer. Also, not all governments progressed equally throughout the years. 

# Do governments with higher eservices share more open data?
![egov14](https://raw.githubusercontent.com/jshapi16/opendata-octupi/main/Images/egov_odb_2014_final1.png)
![egov16](https://raw.githubusercontent.com/jshapi16/opendata-octupi/main/Images/egov_odb_2016_final.png)
* Yes, governments with more e-services share more open data. 

* A strong correlation .84 between Open Data Barometer Score vs E-Government Index shows a distinct relationship and it’s statistically significant with a p-value score close to zero. 

* We can see this from the data, that we have a high R-squared value, indicating that  the model is a good fit for the data, from there calculating a zero p-value indicated that the there is statistical significance, i.e. more e-services does equal more open data.

# How did overall ranks change between 2014 and 2016?

![bar](https://raw.githubusercontent.com/jshapi16/opendata-octupi/main/Images/download.png)

* Latin America & Caribbean and the East Asia & Pacific regions experiences the greatest average percentage increase from 2014 to 2016. 

* Middle East & North Africa and South Asia regions experiences the negative average percentage decrease from 2014 to 2016, where Europe and Central Asia experiences little to no change between the two years.

* Readiness model had the model of best-fit according to R-squared values. 

# Are there regions that are lacking in readiness?
![2014](https://raw.githubusercontent.com/jshapi16/opendata-octupi/main/Images/readiness_vs_odb-score_2014.png)
![2016](https://raw.githubusercontent.com/jshapi16/opendata-octupi/main/Images/readiness_vs_odb-score_2016.png)
* We as a group wanted to highlight the readiness factor and ODB-score because readiness is the baseline for an open data policy. In general, almost every region has at least some countries that scored poorly and had poor readiness. In particular, Europe & Central Asia and North America regions scored well for readiness whereas the Middle East & North Africa and Sub-Saharan Africa regions scored quite poorly. One might then logically ask what differences the regions have which may lead to such differences.

* What common traits do those lacking regions/countries have?
![cluster](https://raw.githubusercontent.com/jshapi16/opendata-octupi/main/Images/readiness_vs_odb-score_by_cluster.png)
    *  The cluster groups were a categorical variable describing each country’s ability to support an open data policy. Countries that are Capacity constrained can’t support open data policies even if they wanted to due to lack of infrastructure, support from the private sector, or support from the government. One sided initiatives do not have support from the private sector and are generally countries with relatively less political freedom. Emerging and advancing means that a country has an open data policy but may struggle to reap to full benefits of such policy.

# Which regions improved between 2014 and 2016? 

* Latin America & Caribbean improved the most from 2014 and 2016. 
![2014](https://raw.githubusercontent.com/jshapi16/opendata-octupi/main/Images/2014%20E-Government%20vs%20Open%20Data%20Barometer%20Score%20in%20Latin%20America%20%26%20Caribbean.png)
    * 2014: The linear regression is graphing the relationship between the E-Government Index and the Open Data Barometer. The relationship between E-Government Index and Open Data Barometer is a strong and positive correlation, meaning a high E-Government Index does associate with a relatively high Open Data Barometer score for the Latin America & Caribbean region. **An r-squared of 78% reveals that 64% of the data fit the regression model.**
![2016](https://raw.githubusercontent.com/jshapi16/opendata-octupi/main/Images/2016%20E-Government%20vs%20Open%20Data%20Barometer%20Score%20in%20Latin%20America%20%26%20Caribbean.png)
    * 2016: The linear regression is graphing the relationship between the E-Government Index and the Open Data Barometer. The relationship between E-Government Index and Open Data Barometer is a strong and positive correlation, meaning a high E-Government Index does associate with a relatively high Open Data Barometer score for the Latin America & Caribbean region. **An r-squared of 78% reveals that 64% of the data fit the regression model.**

* Europe and Central Asia, which consists of many 'developed' countries, decreased in their Open Data Barometer score and E-Government rank from 2014 to 2016.
![linear_regression](https://raw.githubusercontent.com/jshapi16/opendata-octupi/main/Images/2014%20E-Government%20vs%20Open%20Data%20Barometer%20Score%20in%20Europe%20%26%20Central%20Asia.png)
    * 2014: The linear regression is graphing the relationship between the E-Government Index (* 100) and the Open Data Barometer. The relationship between E-Government Index and Open Data Barometer is a strong and positive correlation, meaning a high E-Government Index does associate with a relatively high Open Data Barometer score for the Europe & Central Asia region. **An r-squared of 78% reveals that 78% of the data fit the regression model.**
![2016](https://raw.githubusercontent.com/jshapi16/opendata-octupi/main/Images/2016%20E-Government%20vs%20Open%20Data%20Barometer%20Score%20in%20Europe%20%26%20Central%20Asia.png)
    * 2016: The linear regression is graphing the relationship between the E-Government Index and the Open Data Barometer. The relationship between E-Government Index and Open Data Barometer is a strong and positive correlation, meaning a high E-Government Index does associate with a relatively high Open Data Barometer score for the Europe & Central Asia region. **An r-squared of 71.7% reveals that 71.7% of the data fit the regression model.**

* Overall, we can conclude that not every country in their respective regions progressed similarly, highlighting a great degree of disparity of e-servces within governments and the lack of open data policies. 

* E-Government Index Percentage Change
![LA](https://raw.githubusercontent.com/jshapi16/opendata-octupi/main/Images/E-Government%20Index%20Percentage%20Change_Latin%20America%20%26%20Caribbean.png)
    * Latin America & Caribbean: Argentina and Ecuador experiences the greatest increase in percentage change of **over 10%** from 2014 to 2016 in their e-services rating. Venezuela experiences the greatest decrease of percentage change of over 7%. 
![E](https://raw.githubusercontent.com/jshapi16/opendata-octupi/main/Images/Europe%20%26%20Central%20Asia%20E-Government%20Index%20Percentage%20Change.png)
    * Europe & Central Asia: Ukraine experiences the greatest increase in percentage change of over 20%, while France experiences the greatest decrease in percentage change of over 5% from 2014 to 2016.

* Open Data Barometer Score Percentage Change
![LA](https://raw.githubusercontent.com/jshapi16/opendata-octupi/main/Images/Open%20Data%20Barometer%20Score%20Percentage%20Change_Latin%20America%20%26%20Caribbean.png)
    * Latin America: Hati experiences the greatest increase in percentage change of **over 400%** from 2014 and 2016. Other governments in the region had a relatively slight percentage change in their open data score. 
![E](https://raw.githubusercontent.com/jshapi16/opendata-octupi/main/Images/Europe%20%26%20Central%20Asia%20Open%20Data%20Barometer%20Score%20Percentage%20Change.png)
    * Europe & Central Asia: About half the governments in this region increase their open data score, while the other half experiences a decrease in percentage change from 2014 to 2016. Ukraine experinces the greatest postive percentage change of almost 70%, while France and Hungary experinces the greatest decrease in percentage change of close to 40%.

# How Transparency Can Help the Economy
![region](https://raw.githubusercontent.com/jshapi16/opendata-octupi/main/Images/download%20(2).png)
![rank](https://raw.githubusercontent.com/jshapi16/opendata-octupi/main/Images/download%20(3).png)
![rediness](https://raw.githubusercontent.com/jshapi16/opendata-octupi/main/Images/download%20(4).png)
![economic](https://raw.githubusercontent.com/jshapi16/opendata-octupi/main/Images/download%20(5).png)
![human](https://github.com/jshapi16/opendata-octupi/blob/main/Images/download%20(6).png)
* Transparency would indirectly and directly support a broad range of objectives in government systems globally. 

* 6 key objectives that it would support are by exposing government corruption, Reducing the scope for government revenues to be siphoned offshore, increased collection of domestic tax revenues, Increasing the accountability and effectiveness of government spending, Reducing dependency on foreign aid, and, finally it would help to prevent money laundering and terrorist finance.