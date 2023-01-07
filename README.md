<p align="center"> 
</p>
<h1 align="center"> Seoul Bike Sharing Demand Prediction </h1>
<h3 align="center"> AlmaBetter Verfied Project - <a href="https://www.almabetter.com/"> AlmaBetter School </a> </h5>

<p>In this project I explored over the previous data in order to predict the number of bikes that can be rented per hour by the company. So that customers can get the best experience without any delays.</p>

**Links:**
Presentation: [Slideshow](https://docs.google.com/presentation/d/1wzqfaKUjBtX8FeTKpKsxlLXe9WXFpYx8/edit#slide=id.p1)

<h2> :floppy_disk: Content </h2>
The data are downloaded from the South Korean website named SEOUL OPEN DATA PLAZA. One-year data are used in this research. The period of the dataset is 365 days (12 months) from December 2017 to November 2018. From the data, the count of the rental bikes rented at each hour is calculated.

<h2> :book: Steps Involved in this Project </h2>

**Loading and Discovering Data:**

Here, we need to load our data from the external source, which in this case is uploaded to the drive. The data is in the format of the CSV (Comma Separated Values) file.

**Data Cleaning and Null values treatment:**

Data cleaning is an important step in the data analytics process in which you either remove or update information that is incomplete or improperly formatted. Null values Treatment by different methods. We have our dataset in hand which is raw and unfiltered. This step involves cleaning our data first by eliminating the columns which are not needed for our analysis. We have around 8760 rows × 14 columns in our dataset.Since, there were no null values, we have left it untouched.

**Exploratory Data Analysis:**

Exploratory Data Analysis is the approach of analyzing data, gathering and summarizing the important characteristics of the information, and using simple visualization that makes it easier to understand.

<h2> :clipboard: Conclusions </h2>

Comparison of RMSE values for Test Data as lower the RMSE better the model performance:

LinearRegressor RMSE: 7.487 

Ridge Regression RMSE: 7.485 

Lasso Regression RMSE: 7.741 

Elastic Net Regression RMSE: 8.788

DecisionTreeRegressor RMSE: 5.233 

RandomForestRegressor RMSE: 4.027 

XGBoostRegressor RMSE: 4.824 

GradientBoostingRegressor RMSE: 4.824

• XGBoost Regressor and Gradient Boost Regressor give the highest R2 score of 98% and 96% respectively for the Train dataset and 91% for both regressor's Test dataset.So, We can deploy these models. 

• The Temperature, Hour & Functioning Day are the most important features that positively drive the total rented bikes count. 

• In conclusion, the demand prediction for the given Seoul bike sharing dataset can be accurately predicted using XGBoost Regressor and Gradient Boost Regressor.

<!-- CREDITS -->
<h2 id="credits"> :scroll: Credits</h2>

Kunika Gupta | Data Science Enthusiast | Python | Alteryx | MySql | Tablaeu | Excel | Machine Learning


<p> <i> Contact me for Data Science Project Collaborations</i></p>


[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kunika0927/)
[![GitHub Badge](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/kunikagupta27)
[![Medium Badge](https://img.shields.io/badge/Medium-1DA1F2?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@kunika.gupta27)
[![Resume Badge](https://img.shields.io/badge/resume-0077B5?style=for-the-badge&logo=resume&logoColor=white)](https://drive.google.com/drive/folders/1sM1uv2UDomAGUR6ayLgp_wMvkbSbcZIH?usp=share_link)






