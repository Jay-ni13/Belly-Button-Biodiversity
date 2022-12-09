# Belly-Button-Biodiversity
## Project Overview
Creating an interactive dashboard for individuals who submitted test samples to Improbable Beef--for their study on protein synthesizing bacteria that colonize the human navel--to review the species of bacteria found in their samples and learn whether or not a unique bacteria found in their belly button is selected for further study.

## Resources
 - Data Source: Improbable Beef; samples.json
 - Bacteria Image Source: https://news.un.org/en/story/2021/04/1089822
 - Software: JavaScript vES6+, Bootstrap v5.2.3, CSS v3, VS Code v1.73.1
 
## Summary
After reading about the purpose of the dashboard and its associated study, a [Belly Button Biodiversity](https://jay-ni13.github.io/Belly-Button-Biodiversity/) visitor can scroll through the test subject ID numbers of the entire study, select an ID, compare and contrast the data from each sample through the four charts created to visualize different aspects of the metadata, and form a conclusion based on the displayed information.

The first panel displays the demographic information associated with the selected test subject ID, the bar chart display's the top 10 bacterial species (OTUs) found in the test subject's sample, and the gauge shows the average number of times per week the selected individual washes their navel.

<img src="https://github.com/Jay-ni13/Belly-Button-Biodiversity/blob/main/static/images/bar_and_gauge_charts.png" width=95%>

The bubble chart shows all the different kinds of bacteria detected--and their concentration--in an individual's sample.

<img src="https://github.com/Jay-ni13/Belly-Button-Biodiversity/blob/main/static/images/bubble_chart.png" width=75%>

### Recommendations
Though the webpage is made mobile-responsive through the inclusion of
```<meta http-equiv="X-UA-Compatible" content="ie=edge">```
in the head of the index.html file, the layout of the page could be further edited to improve readability on cell/tablet screen.

The webpage should also be ammended to include a panel on any bacteria species that show promising results for sythetic protein flavor, with an adjacent article section that contains updates on how Improbable Beef's study is progressing with those bacteria strains.
