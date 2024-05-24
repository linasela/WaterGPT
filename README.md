
# WaterGPT
examples for AI use in water operations.
> [!NOTE]
> The responses and not deterministic and you might need to adjust your prompts. 

Example 1 - Missing data imputation
-----------

Upload the [flow excel file](data)

> **User:** *plot the attached data*.

> **ChatGPT:** *Here is the plot of the flow data over time based on the provided dataset.*

> <img src="data/flow_missing_data_output1.png" alt="output1" width="500" height="300">

> **User:** fill in the missing flow data based on the daily pattern, plot again, and indicate the filled in data using red color

> **ChatGPT:** *Here is the updated plot showing the flow data over time, with missing values filled based on the daily pattern.* 

> <img src="data/flow_missing_data_output2.png" alt="output1" width="500" height="300">



Example 2 - Importing, processing, and visualizing asset data
-----------

Upload the [pipes and junctions files](data)

> **User:** *Open the zip files and examine the files*.

> **ChatGPT:** *the contents of the zip files are as follows: ...These files are components of shapefiles typically used in geographic information systems (GIS) for mapping and spatial analysis. Would you like to explore the data within these files further? ​.*

> **User:** *Plot the water pipes and junctions*.

> **ChatGPT:** *Here is the plot showing the water pipes and junctions. The blue lines represent the pipes, and the red dots represent the junctions*.

> <img src="data/GIS_output1.png" alt="output1" width="700" height="300">

Upload the [meters file](data)

> **User:** *This is a water meters layer. Load the file and add the meters to the plot*.

> **ChatGPT:** *Here is the updated plot, now including the water meters. The green "x" markers represent the meters, alongside the blue pipes and red junctions*.

> <img src="data/GIS_output2.png" alt="output2" width="700" height="300">

> **User:** *I want to associate each meter with the closest junction. Plot a gray line connecting the meters with their associated junction*.

> **ChatGPT:** *The plot now includes gray lines connecting each water meter to its closest junction*.

> <img src="data/GIS_output3.png" alt="output3" width="700" height="300">

> **User:** *I want to associate each meter with its closest pipe. Add a line perpendicular to the pipe*.

> **ChatGPT:** *The plot now includes gray lines connecting each water meter to its closest pipe with a perpendicular connection*.

> <img src="data/GIS_output4.png" alt="output4" width="700" height="300">

<!-- 

Upload the [flow excel file](data)

> **User:** *plot the attached data*.

> **ChatGPT:** *Here is the plot of the flow data over time based on the provided dataset.*

> <img src="data/flow_missing_data_output1.png" alt="output1" width="500" height="300">

> **User:** fill in the missing flow data based on the daily pattern, plot again, and indicate the filled in data using red color

> <img src="data/flow_missing_data_output2.png" alt="output1" width="500" height="300">

-->














<!-- 
> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

.. _`MAGNets: Model Reduction and Aggregation of Water Networks`: https://ascelibrary.org/doi/full/10.1061/JWRMD5.WRENG-5486


> fasdf `#RRGGBB`
-->
