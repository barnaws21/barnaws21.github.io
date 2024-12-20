---
title: "Geoprocessing and Buffers to Evaluate the Effect of Road Proximity on Vegetation"
collection: publications
permalink: /publications/
excerpt: 'The ability to autonomously navigate safely, especially within dynamic environments, is paramount for mobile robotics. In recent years, DRL approaches have shown superior performance in dynamic obstacle avoidance. However, these learning-based approaches are often developed in specially designed simulation environments and are hard to test against conventional planning approaches. Furthermore, the integration and deployment of these approaches into real robotic platforms are not yet completely solved. In this paper, we present Arena-bench, a benchmark suite to train, test, and evaluate navigation planners on different robotic platforms within 3D environments. It provides tools to design and generate highly dynamic evaluation worlds, scenarios, and tasks for autonomous navigation and is fully integrated into the robot operating system. To demonstrate the functionalities of our suite, we trained a DRL agent on our platform and compared it against a variety of existing different model-based and learning-based navigation approaches on a variety of relevant metrics. Finally, we deployed the approaches towards real robots and demonstrated the reproducibility of the results.'
# date: 2022-10-01
# venue: 'Robotics and Automation Letters (RA-L)'
# paperurl: 'https://arxiv.org/abs/2206.05728'
# citation: 'L. Kastner et. al. (2022) "Arena-Bench: A Benchmarking Suite for Obstacle Avoidance Approaches in Highly Dynamic Environments" Robotics and Automation Letters.'
---
## Project Aim:
This project aims to evaluate how road proximity affects vegetation health, including changes in density, species diversity, and land cover. By creating buffer zones around roads and analyzing vegetation data within these zones, we seek to quantify the impact of roads on vegetation and provide insights for sustainable transportation planning and conservation efforts.

Steps to Work on the Project:
1. Define Study Area
Choose the region or geographic area you wish to research. A national park, a particular urban or rural location, or a biodiversity hotspot where roads meet natural landscapes could be examples of this.
Obtain spatial information about the vegetation cover and roadways in this research area.

2. Collect Data:  
Road Data: Access road network data, typically in the form of Shapefiles. These might come from satellite images, open data sources, or government transportation bureaus.  
Vegetation Data: Acquire information on the amount of vegetation. Remote sensing data (e.g., NDVI from Landsat or Sentinel), GIS-based land cover data, or ecological surveys.
Other Environmental Data: Take into account any pertinent environmental data, such as terrain, soil type, elevation, and climate, that may have an impact on vegetation.(If I need)

3. Preprocess Data:  
Make that the vegetation and road datasets are in projections and formats that work together. If required, re-project them.
Remove any faulty or unnecessary data points from the datasets to clean them up.

4. Buffer Creation:  
Road networks can be surrounded by buffer zones created using GIS software ( ArcGIS or QGIS). To assess the effects of varying road proximity on vegetation, buffers can be established at varied distances (e.g., 100m, 500m, and 1 km).
To create these zones, use GIS tools such as the Buffer Tool.

5. Overlay and Spatial Analysis:  
Examine the intersections between the vegetation and various buffer zones by comparing the vegetation data with the road buffers.
Determine Vegetation Measures: In each buffer zone, compare the species variety or health of the vegetation (near vs. far from roadways). The Normalized Difference Vegetation Index (NDVI), which is based on land cover classification data or satellite images, is one example of an index that I might utilize.

6. Analyze Proximity Effects:  
Analyze the health, diversity, and density of the plants in areas nearer highways versus those farther away.
Examine the potential effects of road proximity on vegetation:
The Noise and Air Pollution: Noise pollution and air pollution from roads may have a detrimental effect on the health of plants.
Roads have the ability to reduce biodiversity by causing habitat fragmentation.
Road Salt and Chemicals: Roads in colder climates may utilize salt or de-icing chemicals that harm flora.
Effects at the Edge: Because roads frequently generate edge habitats, variations in moisture, temperature, and sunlight can affect plant growth.

7. Statistical Analysis and Visualization:  
To measure the relationship between road proximity and vegetation parameters, conduct statistical analyses (e.g., regression analysis or correlation analysis).
Make charts and maps to help you see your results. I may create clear maps that display vegetation in relation to highways and buffer zones using GIS software.

8. Interpretation and Conclusions:  
Explain the wider ramifications of these effects on ecosystems, wildlife, and conservation efforts. For example, if road proximity dramatically reduces vegetation diversity, I can recommend mitigation measures like wildlife corridors, road underpasses, or vegetation restoration near roads. Interpret the results of your analysis to understand how road proximity affects vegetation.
9. Recommendations:  
Provide possible remedies or tactics to lessen the detrimental effects of highways on vegetation based on my research. This could involve suggestions for buffer zones, green infrastructure, or road design.


#[GIS Final Project Code here](https://github.com/barnaws21/GIS_Project_Code/blob/7cfc8a3c0ddb76795524461a6e2e994e9bdb5624/Final_project(Jetra).ipynb)


