# Belly_Button_Biodiversity

## Project Overview
The purpose of our study is to find the bacterial species that have the abilities to synthesis proteins to taste like beef for Improbable Beef, a food startup company. Since the human body is the source of thousands types of bacteria and different parts of the body harbor differnt species, we believe the ideal bacterial species to make synthetic beef can be found in the belly button or at least in someone's belly button. To test our hypothesis, we have sampled the navel of people across the U.S., to identify the bacterial species that colonize our belly buttons. Each participant's identiy is anonymous, and have been assigned an ID number. We have used JavaScript, Plotly, and D3.js to created a dashboard for participants and fellow researchers to access the data. Those who participated can select their id number to see which bacterial species lives in their navel.

### Resources
- Source Files: [samples.json](/static/js/samples.json), [jumbotron_bg.jpg](/static/image/jumbotron_bg.jpg)
- Result Files: [charts.js](/static/js/charts.js), [index.html](index.html),[app.css](/static/css/app.css)
- Software: HTML, JavaScript, Bootstrap, CSS, Plotly, and D3.js

## Summary
Using JavaScript, Plotly, and D3.js, we have created a dashboard to enable participants and researchers to search for bacterial species that lives in their navel. 

There are 3 charts to showcase our findings:
- Bar Chart - display the top 10 bacterial species (OTUs) when an individual’s ID is selected from the dropdown menu.
- Gauge Chart - displays the weekly washing frequency's value, and display the value as a measure from 0-10 on the progress bar in the gauge chart when an individual ID is selected from the dropdown menu.
- Bubble Chart - display the following when an individual’s ID is selected from the dropdown menu:
	- The OTU ID on the x-axis.
	- The Sample Values on the y-axis.
	- The Sample Values as the marker size.
	- The OTU ID as the marker colors.
	- The OTU Labels as the hover-text values
