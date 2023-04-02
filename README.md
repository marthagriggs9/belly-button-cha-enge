# belly-button-challenge


## Background

In this assignment, you will build an interactive dashboard to explore the [Belly Button Biodiversity](http://robdunnlab.com/projects/belly-button-biodiversity/) dataset, which catalogs the microbes that colonize in human navels. 
The dataset reveales that a small handful of microbial species (also called operational taxonomic units or OTUs in the study) were present inmore that 70% of people, while the rest were relatively rare.

1. Use the D3 library to read in `samples.json` from the URL https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json. 

![image](https://user-images.githubusercontent.com/115905663/229384695-7a739e1a-853d-45f7-a0f2-9793de12a0bf.png)

![image](https://user-images.githubusercontent.com/115905663/229384834-c09f59aa-78ae-4510-9a63-65ed8bab6b36.png)

2. Create a horizontal bar chart with a drop down menu to display the top 10 OTUs found in that individual. 
   * Use `sample_values` as the values for the bar chart. 
   * Use `otu_ids` as the labels for the bar chart.
   * Use `otu_labels` as the hovertext for the chart.

![image](https://user-images.githubusercontent.com/115905663/229384900-5729cb5b-72c4-46f3-aabd-fbcb524213ff.png)

3. Create a bubble chart that displays each sample.
   * Use `otu_ids` for the x values.
   * Use `sample_values` for the y values. 
   * Use `sample_values` for the marker size.
   * Use `otu_ids` for the marker colors. 
   * Use `otu_labels` for the text values. 

![image](https://user-images.githubusercontent.com/115905663/229384959-59c9f338-fdc4-48b4-8096-1887f06007b4.png)

4. Display the sample metadata, i.e., an individual's demographic information. 

![image](https://user-images.githubusercontent.com/115905663/229385195-9a3e11c2-2ff2-4847-9937-e68ac1080161.png)


5. Display each key-value pair from the metadata JSON object somewhere on the page. 

![image](https://user-images.githubusercontent.com/115905663/229385206-b04c6e73-c9ad-4693-b950-63eda854c529.png)

6. Update all the plots when a new sample is selected. Additionally, you are welcome to create any layout that you would like for your dashboard. 

![image](https://user-images.githubusercontent.com/115905663/229385259-f23acbfe-f4f3-4874-9f9a-9d38b8bcdbea.png)

7. Deploy your app to a free static page hosting service, such as GitHub Pages. Submit the links to your deployment and your GitHub repo. Ensure that your respository has regular commits and thorough README.md file. 

[My Belly Button Biodiversity Static Page](https://marthagriggs9.github.io/belly-button-challenge/)
