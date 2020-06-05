# Traffic-Prediction-using-SVR-and-RFR
<p>Our main aim was to predict the traffic using SVR and RFR model, then compare their error and accuracy rate.</p>
<p> We build our model in python using a real time dataset.</p>
<h2>ABOUT THE DATA SET</h2>
<p><h3>Date:</h3> The Date Column consists of the date on which the data were recorded in the
format DD/MM/YYYY</p>
<p><h3>Day:</h3> The Day Column consists of the day of the week on which the data was
recorded. This is done to facilitate the use of the dataset for further usability to
predict the possibility of traffic based on what day of the week it is.</p>

<p><h3>Coded Day:</h3> The coded day gives code numbers to each day of the week. This makes
the prediction of traffic based on the day much easier since we are not bound to
implement string functions for converting the given days to codes. The day codes
are as follows: -</p>
<ul>Monday - 1
Tuesday - 2
Wednesday - 3
Thursday - 4
Friday - 5
Saturday - 6
Sunday - 7</ul>
<p><h3>Zone:</h3> This Column is for the zone number from which the traffic data is recorded.
Weather: The weather in this column is coded. This is based on the various standard
weather conditions. The traffic varies based on the weather of the given zone. This
includes aspects like humidity, mist, visibility, precipitation, etc.</p>
<p><h3>Temperature:</h3> This column has the recorded temperature for the given zone on the
particular day. Temperature plays a major role in traffic prediction.</p>
<p><h3>Traffic:</h3> This is the column used as the training dataset, and is also used for
prediction. The traffic in this column is coded in 5 levels. The levels are as follows: -</p>
<ul>1 - Less than 5 cars.
2 - 5 to 15 cars.
3 - 15 to 30 cars.
4 - 30 to 50 cars.
5 - More than 50 cars.</ul>
