# DATA

The data used for this study has been collected and shared by the Seattle Police Department (recorded by Traffic Records). This data is provided by Coursera for downloading through a link (provided below).

The dataset reports all collisions which occurred in the period from 2004 to the date issued (updated weekly).  The dataset provides information regarding the severity of the traffic accident, location, type of collision, weather, road and light conditions, visibility, number of people involved, etc.

The data set provided for this work allows the analysis of a record of about 200,000 accidents in the state of Seattle. This set is sufficiently large for an accurate prediction of the accident severity.  There are 38 labels in the dataset. The label 'SEVERITYCODE' is the target variable, which is 1 for non severe accident and 2 for severe accident. The remaining 37  are the which can be used to predict the target variable. Several attributes such as ‘UNDERINF’, SPEEDING’, ‘ROADCOND’, (i.e. whether or not a driver involved was under the influence of drugs or alcohol, whether or not speeding was a factor in the collision (Y/N), the condition of the road during the collision. ) can be analyzed for understanding how gravely they contribute to the accidents.  Only those attributed which are essential for the accident severity prediction would be used to train the models. Further, the data is also coded in accordance with the State Collision Code Dictionary, describing various factors such as the direction of vehicles involved, type of vehicle, etc.  Some of the attributes which would be helpful in predicting the accident severity are:

1) Road Condition - Values of Road condition are shown below

Dry               124510
Wet                47474
Unknown            15078
Ice                 1209
Snow/Slush          1004
Other                132
Standing Water       115
Sand/Mud/Dirt         75
Oil                   64

2) Light Condition - Values of Light condition are shown below

Daylight                    116137
Dark - Street Lights On      48507
Unknown                      13473
Dusk                          5902
Dawn                          2502
Dark - No Street Lights       1537
Dark - Street Lights Off      1199
Other                          235
Dark - Unknown Lighting         11

3) Speeding -
Y     9333 (Means Yes)
Remaining are NaN - We will consider it to be no

4) Collision Type - Values of Collision Type are shown below

Parked Car    47987
Angles        34674
Rear Ended    34090
Other         23703
Sideswipe     18609
Left Turn     13703
Pedestrian     6608
Cycles         5415
Right Turn     2956
Head On        2024

5) Weather - Values of Weather are shown below

Clear                       111135
Raining                      33145
Overcast                     27714
Unknown                      15091
Snowing                        907
Other                          832
Fog/Smog/Smoke                 569
Sleet/Hail/Freezing Rain       113
Blowing Sand/Dirt               56
Severe Crosswind                25
Partly Cloudy                    5

The data will be cleaned and used so that we can determine which attributes are most common in traffic accidents in order to target prevention at these high-incidence points.

* Data Source: These data have been collected and shared by the Seattle Police Department (Traffic Records) and are provided by Coursera for downloading through a link.

* Data Location: https://www.coursera.org/learn/applied-data-science-capstone/supplement/Nh5uS/downloading-example-dataset
Data set name: Data-Collisions.csv

This analysis should help anyone interested, to focus their resources on handling the most contributing factors and determine 
a prevention strategy.


