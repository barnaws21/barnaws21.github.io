---
title: "Geoprocessing and Buffers to Evaluate the Effect of Road Proximity on Vegetation"
collection: projects
permalink: /projects/
excerpt: 'The ability to autonomously navigate safely, especially within dynamic environments, is paramount for mobile robotics. In recent years, DRL approaches have shown superior performance in dynamic obstacle avoidance. However, these learning-based approaches are often developed in specially designed simulation environments and are hard to test against conventional planning approaches. Furthermore, the integration and deployment of these approaches into real robotic platforms are not yet completely solved. In this paper, we present Arena-bench, a benchmark suite to train, test, and evaluate navigation planners on different robotic platforms within 3D environments. It provides tools to design and generate highly dynamic evaluation worlds, scenarios, and tasks for autonomous navigation and is fully integrated into the robot operating system. To demonstrate the functionalities of our suite, we trained a DRL agent on our platform and compared it against a variety of existing different model-based and learning-based navigation approaches on a variety of relevant metrics. Finally, we deployed the approaches towards real robots and demonstrated the reproducibility of the results.'
# date: 2022-10-01
# venue: 'Robotics and Automation Letters (RA-L)'
# paperurl: 'https://arxiv.org/abs/2206.05728'
# citation: 'L. Kastner et. al. (2022) "Arena-Bench: A Benchmarking Suite for Obstacle Avoidance Approaches in Highly Dynamic Environments" Robotics and Automation Letters.'
---
## Project Aim:
The project "Geoprocessing and Buffers to Evaluate the Effect of Road Proximity on Vegetation" aims to determine how road proximity affects flora diversity, health, and dispersion. This project aims to utilize geographic information systems (GIS) and other geospatial analysis tools to establish buffers around highways and examine the effects of different distances from these roadways on the local vegetation. Through the integration of road network and vegetation cover data, the project will investigate the connections between environmental issues including pollution, biodiversity, and habitat fragmentation and human infrastructure.

Steps to Work on the Project:
1. Define Study Area
Choose the region or geographic area you wish to research. A national park, a particular urban or rural location, or a biodiversity hotspot where roads meet natural landscapes could be examples of this.
Obtain spatial information about the vegetation cover and roadways in this research area.

2. Collect Data
Road Data: Access road network data, typically in the form of GeoJSON or Shapefiles. These might come from satellite images, open data sources (like OpenStreetMap), or government transportation bureaus.
Vegetation Data: Acquire information on the amount of vegetation. This could include data from field surveys that identify various plant types or data from remote sensing photography (like Landsat) that classifies land cover.
Other Environmental Data: Take into account any pertinent environmental data, such as terrain, soil type, elevation, and climate, that may have an impact on vegetation.

3. Preprocess Data
Make that the vegetation and road datasets are in projections and formats that work together. If required, re-project them.
Remove any faulty or unnecessary data points from the datasets to clean them up.

4. Buffer Creation
Road networks can be surrounded by buffer zones created using GIS software (like ArcGIS or QGIS). To assess the effects of varying road proximity on vegetation, buffers can be established at varied distances (e.g., 100, 500, and 1 km).
To create these zones, use GIS tools such as the Buffer Tool.

5. Overlay and Spatial Analysis
Examine the intersections between the vegetation and various buffer zones by comparing the vegetation data with the road buffers.
Determine Vegetation Measures: In each buffer zone, compare the species variety or health of the vegetation (near vs. far from roadways). The Normalized Difference Vegetation Index (NDVI), which is based on land cover classification data or satellite images, is one example of an index that you might utilize.

6. Analyze Proximity Effects
Analyze the health, diversity, and density of the plants in areas nearer highways versus those farther away.
Examine the potential effects of road proximity on vegetation:
The Noise and Air Pollution: Noise pollution and air pollution from roads may have a detrimental effect on the health of plants.
Roads have the ability to reduce biodiversity by causing habitat fragmentation.
Road Salt and Chemicals: Roads in colder climates may utilize salt or de-icing chemicals that harm flora.
Effects at the Edge: Because roads frequently generate edge habitats, variations in moisture, temperature, and sunlight can affect plant growth.

7. Statistical Analysis and Visualization
To measure the relationship between road proximity and vegetation parameters, conduct statistical analyses (e.g., regression analysis or correlation analysis).
Make charts and maps to help you see your results. You may create clear maps that display vegetation in relation to highways and buffer zones using GIS software.

8. Interpretation and Conclusions
Explain the wider ramifications of these effects on ecosystems, wildlife, and conservation efforts. For example, if road proximity dramatically reduces vegetation diversity, you can recommend mitigation measures like wildlife corridors, road underpasses, or vegetation restoration near roads. Interpret the results of your analysis to understand how road proximity affects vegetation.
9. Recommendations
Provide possible remedies or tactics to lessen the detrimental effects of highways on vegetation based on your research. This could involve suggestions for buffer zones, green infrastructure, or road design.


#[Download paper here](https://arxiv.org/abs/2206.05728)

#Recommended citation: L. Kastner et. al. (2022) "Arena-Bench: A Benchmarking Suite for Obstacle Avoidance Approaches in Highly Dynamic Environments" Robotics and Automation Letters.
