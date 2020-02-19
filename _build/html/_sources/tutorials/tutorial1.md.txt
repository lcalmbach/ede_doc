## Tutorial 1 Exploring a data collection

### Introduction
This tutorial will guide you through the workflow of discovering a data collection using EDE. It is based on the Ontario Provincial Groundwater Monitoring Network (PGMN) data and aims at getting an overview on this data collection. The second and third tutorials will cover the steps to take to look specifically at the data for a set of wells or a single a well of interest.

When opening EDE, PGMN should already be the first item in the listbox, otherwise select it from the data collection list box.

<p align="center">
<img src="../_static/tutorial_data_collection.png" id = "img70"/>
</p>

### Information on the data collection
By default, the first menu item **Info** is selected. On the view panel you will find a overview on the data collection comprising an introductary text and a list of links, related to the data. The info menu provides a summary on what to expect from the selected data collection, for example: how many parmeters were measured, how many stations were sampled, how many years of data are available. For the Provincial Groundwater Monitoring Network (PGMN) data collection you will find the following: an introductionary text, metadata from the owner (Ontario.ca), a list of links with additional information on the data collection and metadata for two datasets included in this collection: water quality (chemistry) data and water levels. 

### Information on stations
Clicking on the **Stations info** menu item will show specific information on the stations included in the current dataset. You find again the number of all stations in the title above the first data table. The data table holds all information on the stations as well as on the number of samples taken at each station and on the timeframe the sample were collected. The table may be downloaded using the link below the table. You may also enlarge the table using by clicking in the upper right corner of the table. 
Below the table a map plot showing the position of all stations is shown. Below the map, you find an additional link to a googlemap site, showing the same dataas in the map above in a more interactive way and with a high resolution satellite backgroundimage. Google map also allows to measure distances and add lines and markers.

<p align="center">
<img src="../_static/tutorial_1_googlemap.png" id = "img70"/>
</p>

The PGMN network has a second dataset with water levels, this second dataset can be activated by selecting the **Water levels** menu item from the **Select a dataset** selectbox. It can then be explored in the same way as the water quality. The station names are largely identical with the water quality sampling stations explored in the previous step. Nearly all wells are equipped with a piezometer. Wells with names such as W0000114-2/3/4 have multiple pizometer at different depth intervals.

### Information on analysed parameters
Return to the ede page and click on the parameters menu item. A single page with all parameters having at least one observation in the dataset is shown. The minimum, maximum and average value as well as the number of observations and sampling years are shown. It can be noted, that most organic parameters and pesticides have been sampled only once at most stations whereas most inorganic parameters where sampled yearly. In order to focus on specific parameter groups and parameters during an analysis, you may filter the parameter displayed in the viewport using the data filters on the sideboard. For example to gain more insight in the parameter arsenic, enable both the parameter_group and parameter filter in the data filter select box. Then select the parameter group 'inorganic parameters' and from the parmaeter list in the select box below, which now only contains inorganic parameters, type in arsenic or select the parameter from the list. You may skip the step of preselecting the parameter group and select arsenic directly from the full list. However, if your analysis will only require inorganic parameters, all operations will be faster if the parameter list is filtered first.

<p align="center">
<img src="../_static/tutorial_1_parameter_filter.png" id = "img70"/>
</p>

The viewport now contains again the parameter summary table, however in a transposed format where each row holds a separate value. This makes it easier to read. Below the summary table, an additional table shows the statistical values for each station. At the bottom of the page a map is rendered. Concentrations are rendered in the following colors:

* < 10 percentile: blue
* 10-90 percentile green
* > 90 percentile: red

The map allows to detect spatial patterns. A more detailed analysis can be done using the plotting menu item, explained in tutorial 2 and 3. You should by now have a good understanding on the number, spatial distribution and sampling frequency of of stations and on the availabe parameters.