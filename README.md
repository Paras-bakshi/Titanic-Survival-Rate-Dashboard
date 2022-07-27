# Titanic-Survival-Rate-Dashboard
Dashboard of Exploratory Data Analysis of Titanic Dataset using Streamlit

<img width="613" alt="1" src="https://user-images.githubusercontent.com/63099028/181268507-431fc8b9-7055-4dcf-b416-358a43a5605c.PNG">

Used titanic dataset from Kaggle

The csv file contains data for 887 of the real Titanic passengers. Each row represents one person. The columns describe different attributes about the person including whether they survived (SS), their age (AA), their passenger-class (CC), their sex (GG) and the fare they paid (XX)
Libraries used
1. Pandas 
2. Numpy 
3. Plotly(plotly.figure_factory, plotly.offline, plotly.graph_objs, plotly.express) 
4.Streamlit
 I have explained all the Charts and representation that I used in the dashboard in the report. The Screenshots of the report are as follows:
 Calculated observations observations:-
 Number of Fist class Passenger Survived : 120
 Number of Second class Passenger Survived : 83
 Number of  class Passenger Survived : 85

 Number of Fist class Passenger Deaths: 64
 Number of Second class Passenger Deaths: 90
 Number of Third class Passenger Deaths: 270

Number of Fist class Passenger Deaths: 34
 Number of Second class Passenger Deaths: 10
 Number of Third class Passenger Deaths:20
 
 
<img width="276" alt="1" src="https://user-images.githubusercontent.com/63099028/181269326-ed993f66-b59b-479a-bdd7-b43f5393f0e1.PNG">

Passenger belonging to Embarked % (Pie Chart)
Shows that the highest % of the passengers belong to embarked class Q 
That is 77.8 ,next 18.39 from the embarked class S and leaving 3.93 from class C.

<img width="286" alt="2" src="https://user-images.githubusercontent.com/63099028/181269365-628462c8-b3a6-4cc1-8c87-cd348bc97806.PNG">

Survival Histogram based on Pclass
Number of Fist class Passenger Survived : 120
Number of Second class Passenger Survived : 83
Number of  class Passenger Survived : 85

Number of Fist class Passenger Deaths: 64
Number of Second class Passenger Deaths: 90
Number of Third class Passenger Deaths: 270

From this we can conclude that the people who travel in the first class
Have the maximum survival rate than class second and third , where as people who travel in the third class have the maximum death rate.


<img width="281" alt="1" src="https://user-images.githubusercontent.com/63099028/181269704-8f261352-d75c-4001-9a3a-f02fdd30b3b1.PNG">


Box plot Based on Pclass vs age
This box plot shows the presence of outliers in case of class 2 and 3 in term of ageWhere as there no presence of outlier in case of class 1.


<img width="284" alt="1" src="https://user-images.githubusercontent.com/63099028/181269882-cd39b4fc-b5cd-46a6-a32f-8f3d915f0fd5.PNG">


Line plot for Fare_Tax,Luggage Charges,Food Charges
Shows linear relationship between the Fare_Tax,Luggage 
Charges,Food Charges.


<img width="283" alt="1" src="https://user-images.githubusercontent.com/63099028/181270093-b47a294b-bf8f-4934-b080-d005ccea1e9a.PNG">

Survival Histogram Based on Sex
This clearly shows that death rate of male is more than female.
Survival rate of female is more than male.


<img width="284" alt="1" src="https://user-images.githubusercontent.com/63099028/181270353-b0a57712-bf4a-49f0-ade0-9ee33b68df8e.PNG">

Survival Rate %(Pie Chart)
survival rate=59.6
Death rate=40.49


















