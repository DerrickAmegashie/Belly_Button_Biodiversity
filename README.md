# Belly_Button_Biodiversity

## Overview
The project involved creating an interactive dashboard to explore the belly button biodiversity datasets using JavaScript, Plotty, and D3.js. The dataset catalogs the microbes that colonize human navels. The dashboard displayed a drop down menu, demographic information and three diffferent visualization of the dacteria dataset. 

## Results
1. Use the D3 library to read in samples.json.

2. Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.

- Use sample_values as the values for the bar chart.

- Use otu_ids as the labels for the bar chart.

- Use otu_labels as the hovertext for the chart.

<img width="261" alt="Screen Shot 2021-07-21 at 9 08 16 PM" src="https://user-images.githubusercontent.com/78401776/126577957-a4adb3c0-e595-40ff-9077-71cf2ed43210.png">


3. Create a bubble chart that displays each sample.
- Use otu_ids for the x values.

- Use sample_values for the y values.

- Use sample_values for the marker size.

- Use otu_ids for the marker colors.

- Use otu_labels for the text values.

<img width="687" alt="Screen Shot 2021-07-21 at 9 10 22 PM" src="https://user-images.githubusercontent.com/78401776/126578071-3502ff85-9aa6-42f2-a95d-b5b7cf4d3b77.png">


4. Display the sample metadata, i.e., an individual's demographic information.

5. Display each key-value pair from the metadata JSON object somewhere on the page.

<img width="129" alt="Screen Shot 2021-07-21 at 9 12 52 PM" src="https://user-images.githubusercontent.com/78401776/126578206-651dd706-661e-4df8-809e-25ab8f1487e3.png">


6. Create a guage chart that displays the Belly Button Washing Frequency

- Get the Gauge Chart from https://plot.ly/javascript/gauge-charts/ to plot the weekly washing frequency of the individual.

- Modify the example gauge code to account for values ranging from 0 through 10.

- Update the chart whenever a new sample is selected.

<img width="374" alt="Screen Shot 2021-07-21 at 9 18 55 PM" src="https://user-images.githubusercontent.com/78401776/126578513-819ead9e-9b98-45c4-98fc-14536a34c845.png">


7. Update all of the plots any time that a new sample is selected. Combined all visualizations into a single dashboard

<img width="1079" alt="Dashboard" src="https://user-images.githubusercontent.com/78401776/126578330-3419590e-a574-4291-9452-bf320f9af555.png">


## Summary
The project allows one to develop an interactive dashboard which highlighs various visualizations through the use of JavaScript, Plotty and D3.js. The interactive dashboard allows it's information to be updated anytime an ID is selected.

