# PlotlyDiploy

## Project Overview

In this module, we will use Plotly.js, a JavaScript data visualization library, to create an interactive data visualization for the web. 

## Resources

* Data Source: index.html, samples.json, plots.js
* Software: VS Code, Web browser, Command-line interface, GitHub

## Challenge Overview

In this challenge, we have a partially completed dashboard, but need to finish it. We have a completed panel for demographic information and now need to visualize the bacterial data for each volunteer. Specifically, the volunteers should be able to identify the top 10 bacterial species in their belly buttons. That way, if Improbable Beef identifies a species as a candidate to manufacture synthetic beef, our volunteers will be able to identify whether that species is found in quantity in their navel.

## Challenge Summary

I. When an individual’s ID is selected, the top 10 bacterial species (OTUs) should be visualized with a bar chart.

* Use sample_values as the values for the bar chart.
* Use otu_ids as the labels for the bar chart.
* Use otu_labels as the hover text for the chart.

![1](https://user-images.githubusercontent.com/73450637/105662484-d3218d80-5e9d-11eb-8f48-141cfb276f36.png)

II> In the Demographics Info panel, display all the key-value pairs of the selected individual’s demographic data.

![3](https://user-images.githubusercontent.com/73450637/105662562-049a5900-5e9e-11eb-9420-bac797cafb4a.png)

III. Creating a bubble chart that displays each sample:

* Use otu_ids for the x-axis values.
* Use sample_values for the y-axis values.
* Use sample_values for the marker size.
* Use otu_ids for the marker colors.
* Use otu_labels for the text values.


IV. Adapt the gauge chart from Plotly documentation to plot the weekly washing frequency of the individual.

* Modify the example gauge code to account for values ranging from 0 through 9.
* Update the chart whenever a new sample is selected.

