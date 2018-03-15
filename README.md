# Create-A-Tableau-Story
udacity nano degree project 8 term 2

PURPOSE

The purpose of this document is to communicate the insights and visualizations produced as a result
of exploring the Titanic Dataset

SUMMARY:

The dataset explored contains demographic and passenger information from a subset of the 2224 passengers and crew on board of Titanic. The main objective of visualizations produced is to show the demographics or passenger information between those passengers who survived and those who died

INITIAL VISUALIZATION
  - https://public.tableau.com/profile/bibhash.kalita#!/vizhome/TitanicSurvivalCountInitialVisualization/Story1
  
FINAL VISUALIZATION
  - https://public.tableau.com/profile/bibhash.kalita#!/vizhome/TitanicSurvivalFinalVisualization/TitanicSurvivals_Final

DESIGN:

I have based my visualizations on survival count because it is the main highlights of the Titanic tragedy and created the following charts for the initial visualizations:

Survival Count per Gender
Age Distribution of Titanic Passengers
Survival Count per Ticket Class
Survival Count Based on Embarkation Port
All visualizations have been created using Bar charting because data shown are related to counts of survivals. Also, I have converted (Survived, Fare, Parch, Passenger Id, Pclass, Sib Sp) to Dimensions since Tableau interprets these variables as measures After receiving the feedback on the initial visualizations, I have added these calculations to improve the story telling:

Dead --> Count of dead passengers [survived = 0]
Alive	--> Count of alive passengers [survived = 1]
Survival Rate % -->	Percentage of passengers who survived: Count of alive passengers / Total Count of passenger
In addition, I have created “Age Range” to address one of the comments in the feedback as below:

Babies -->	0-1 Years
Toddlers -->	1-3 Years
Kids -->	3-5 Years
Children -->	5-12 Years
Teens	--> 12-18 Years
Early Adults -->	18-45 Years
Middle Adults -->	45-65 Years
Later Adults -->	65+ Years
The final visualizations contains the following charts:

Passengers Count per Gender
Survival rate per Gender
Survival Rate VS. Age Distribution of Titanic Passengers
Survival Rate per Ticket Class
Survival Rate Based on Embarkation Port
FEEDBACK:

Below is the feedback I received from a colleague: •	What are the survival rates of male and female? •	What does ‘0’ and ‘1’ mean in the axis? •	Can you more explain your findings in these charts? What are you trying to communicate? •	Age chart is condensed.

RESOURCES:

https://www.kaggle.com/kabure/titanic-eda-simple-keras-model-acc-0-8575
https://community.tableau.com/thread/129566
http://onlinehelp.tableau.com/current/pro/desktop/en-us/help.html
https://community.tableau.com/thread/156968
https://community.tableau.com/thread/149814
https://github.com/bcko/Ud-DA-Tableau-Titanic/blob/master/writeup.md
