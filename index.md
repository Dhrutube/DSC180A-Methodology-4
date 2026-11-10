# Dhruv Sehgal

dsehgal@ucsd.edu

## Section: European Wildfire and Property Intelligence Modeling with Cotality (2) Property Intelligence: Enhancing Geospatial Data Quality for Risk Assessment (D11)

#### Mentor: Lawrence Vulis
<br/>

**What is the most interesting topic covered in your domain this quarter?**<br/>
My capstone is focused on improving and increasing the accuracy of automatic building footprint drawings using open-source satellite or aircraft imagery. My favorite (most interesting topic) was open-source mapping services like OpenStreetMap, an online service maintained entirely by volunteers. Through assignments, we got to make contributions as volunteers to it such as updating operating hours of locations, adding new locations not updated yet, and even outlining building footprints both manually as well as with the Rapid editor (which uses AI). 

**Describe a potential investigation you would like to pursue for your Quarter 2 Project.**<br/>
Most companies have their own aircrafts flying at low altitudes to minimize distortion in their maps, but further work is still required to completely remove it. Hence most sources hence still have some distortions, especially open-source sources, with the roof and base of a building being out of line. This causes many building footprint drawings to follow the roof of a building instead of the base, causing inaccuracies in location. I want to look at different orthorectification (eliminating distortions and getting a perfect top-down view) techniques used by different satellite imagery providers. Investigating this could provide very valuable insights into how machine learning algorithms should deal with distortions for our project.

**What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**<br/>
Our quarter 1 project started with mostly readings and following coding tutorials to get familiar with the domain and setting up coding environments. Our assignments involved making contributions to OpenStreetMap. The readings taught us that there are various variables involved in property insurance and every company handles them differently. One thing I would change is getting into the coding earlier to get familiar with those tools and reading papers alongside or a bit later to understand the importance of said variables. In my opinion, this would have made us familiar with the domain in a coding context better instead of the domain overall. The rest of the quarter involves coding assignments in DuckDB and working with mapping editors, so I would not change anything there.

**What other techniques would you be interested in using in your project?**<br/>
Our project involves using DuckDB SQL to extract the number of points in a building footprint. This is the fastest approach given DuckDB's optimization for large-scale SQL queries. However, I would want to explore computer vision techniques for drawing building footprints as well. While this is much more resource-intensive, it could be useful at smaller scales for areas with imagery that is not very clear, has a lot of obstructions (such as vegetation coverage), or for sources with bad orthorectification.
