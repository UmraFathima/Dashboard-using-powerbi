
# T20 cricket Analysis-Dashboard


## Problem Statement

This dashboard for a T20 analysis helps to identify the key performance indicators (KPIs) that are most relevant to the team’s or player’s success in T20 matches. The KPIs could include batting average, strike rate, economy rate, wickets taken, catches, run-outs, etc. 

Once the KPIs are identified, the dashboard can be designed to provide a visual representation of these metrics, allowing teams and players to analyze their performance and identify areas for improvement.


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty values were present except column named "Arrival Delay".
- Step 5 : For calculating number of matches win, null values were not taken into account as only less than 1% values are null in this column(i.e column named "number of matches win") 
- Step 6 : In the report view, under the view tab, theme was selected.
- Step 7 : Since the data contains various cricekt attributes, thus in order to represent attributes, a new visual was added using the three ellipses in the visualizations pane in report view. 
- Step 8 : A bar chart was also added to the report.

  (a) Top scorrers in T20 world cup

  (b) Number of matches won by per team
  
  (c) Best stadium to bat first or chase
  
  (d) Player of MAtch awards in T20 worls cup
  
  (e) Number of matches won by wickets or runs

  
In our dataset, Some parameters were assigned value 0, representing those parameters are not applicable.

All these values have been ignored while calculating average rating for each of the parameters mentioned above.

- Step 9 : In the report view, under the insert tab, oned text boxes were added to the canvas, in one of them name of the T20 Analysis dashbord was mentioned.

 
 # Report Snapshot (Power BI DESKTOP)

 
![Dashboard_upload](https://github.com/UmraFathima/Dashboard-using-powerbi/assets/154687173/e35b1fd6-c058-4f1b-961c-bdd000c1bdd3)


A single page report was created on Power BI Desktop.
