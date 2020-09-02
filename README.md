#Project name: 
Implementation of Concept for Web-based Visualitation of Machine Scheduling of a Production Process 

#Task: to create a gantt-diagram designer for tables with production plans.

#Idea:
This is a university project. Any Tech-Stack could be chosen. Restrictions were only for the table formatting. The tables have a certain form as shown in Table-Example.csv. 
The program should create a gantt-diagram based on the data from this table, which will not be shamed to use when preparing educational materials.
So I tried to programm a basic interface with HTML und a little bit CSS with university-colors for "style-scores". The programm logic was implemented on JavaScript (ESCMA 6). 
The programm can open csv-table with FileAPI, extract data and if csv-table has same formating as Table-Example.csv it will create a SVG with gantt-chart. After creating user can save it as png-picture.

>>about gantt-charts: https://www.gantt.com/ 
>>about production plan scheduling: https://www.finanzen.net/wirtschaftslexikon/maschinenbelegungsplan


#How to Start:
Just open index.html and import Table-Example.csv to see a gantt-chart.


#Tech-Stack: 
>>D3.js: https://d3js.org
>>saveSvgAsPng: https://github.com/exupero/saveSvgAsPng


#Soll-Ist-Analysis:
>Good points:
1. App works
2. Extracting and matching of data works
>Still in Progress:
1.Bugs
2.Table import via cloud
3.Customize options for chart
