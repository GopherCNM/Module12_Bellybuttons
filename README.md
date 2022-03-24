# Plotly & Belly Button Biodiversity

## Overview of the project

Dashboard page: https://gophercnm.github.io/Module12_Bellybuttons/

For this project, we have been contracted to help Roza, a microbiologist, to create a dashboard to help visualize data from a research study. In the study, samples were taken from the navels of participants to determine which bacterial species are present, and in what quantities. The goal is to use this research to understand which bacteria can be used to synthesize the taste of beef, for use by a company called Improbable Beef. The dashboard will be used to post results for each participant.  

Using JavaScript, D3, and Plotly we built code to summarize and visualize the study data stored in a JSON file. We then created a webpage using HTML to display the dashboard and used Bootstrap and CSS to prettify the page. To facilitate access for both study participants and other researchers, we leveraged GitHub’s servers to deploy the project using GitHub Pages.  

Using the dropdown list in the upper left corner of the page, site visitors may select a research participant ID. The demographic info table and the 3 visualizations will refresh to reflect the results of the selected participant.  

- Bar chart: Top 10 bacteria present in the participant’s belly button.  
- Gauge chart: Weekly belly button washing frequency for the selected participant.  
- Bubble chart: Shows the bacteria present in the participant’s naval samples, with the size of the bubble depending on the quantities of the bacterial sample.
