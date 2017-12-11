<H2 align='center'>Crime Scene Rochester NY </H2>
<H4 align='center'>A Big Data Case Study in Social Sciences</H4>
<H4 align='center' >E-63 Big Data Analytics</H4>
<H4 align='right'>By : Ajay Antony Kliyara Philip</H4>

<H3>Problem Statement</H3>

<b>How safe are you in Rochester, NY ? Drive decision using data as opposed to opinion.</b>

	Data > Opinion (always)

<b> The objective was to allow a rochester resident / visitor to use historical data to help determine how safe they would be visiting part of the city at a specific time. </b>

<H3>Project Objectives</H3>

1. Exploratory Data Analysis of crime incidents in Rochester, NY from 2011 to Present. This section involved visualizing the data and understanding it better.

2. Install and Configure TabPy Server and Client. This is required to deploy the predictive model to be used later by Tableau.

3. Use historical data to Predict the probability of crime using SKLearn at a given location, month of the year and time of day. This section involved building a predictive model to help predict possibility of crime at a given location and time.

4. Supplement prediction with density of specific crimes at the location. This section involved visualizing the hotspots in the data by crime time. The idea was to supplement the prediction result to help the user make their decision.

5. Build an application on top the predictive model to present the user with a user interface to consume the data. Tabpy integration with Tableau was used for this purpose.

<H3>Analysis</H3>

1. [Exploratory Data Analysis](code_notebooks/1.Exploratory_Data_Analysis.ipynb)

2. [Setting up TabPy Server / Client](code_notebooks/2.Installing and Configuring TabPy Server and Client.pdf)

3. [Predicting Crime](code_notebooks/3.Predicting_Crime.ipynb)

4. [Crime Hotspots](code_notebooks/4.Clustering_Crime.ipynb)

5. [Interface for Predictive Model using Tableau](code_notebooks/5.Application using Tableau & TabPy.pdf)


<H3>Results</H3>
All the project objectives listed above were achieved. Exploratory Analysis helped understand the data Larceny was the most frequent crime type. More violent crimes like murder was at the lower end of the spectrum. It also helped determine key features that could help in predicting crime such as location, time of year and day.
KNN Classifier was able to achieve a relatively good accuracy of 87% after balancing the dataset. It was able to predict probability of various crime types given a location, time of day and month of the year.
Hotspots for each crime type was determined using seaborn KDEPlot. These plots were supplemented with the location user plans to visit to give them a perspective and aid in the decision if they have to venture into that part of time at that time.
Tableau (Leader in BI tools per Gartner) was integrated with the previously derived KNN Classifier using the TabPy Client / Server. Allowing for a better interface for the user to interact with the data.

<H3> Demo Videos </H3>

<H3> Potential Next Steps </H3>

1. Build a website which can use this model thus allowing anyone to interact with the application

2. Analysis can be supplemented with other data sets such as population at a location etc

3. Expand the solution to other cities states

4. Build more robust, complex models for better accuracy

5. Deploy TabPy server to AWS

6. Use distributed ML such as Spark ML to help deal with even larger volumes of data.
