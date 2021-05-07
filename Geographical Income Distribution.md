## Geographic Income Distribution of Singapore

### Introduction
This project involves building an analysis of the geographical income distribution of Singapore. The client is a data analytics company that partnership with the telecommunications industry to sieve through and analyze the multitude of data the telcos generate. In this project, the data is sourced from publicly available domains and the goal is to build a mapping of each resedential district in Singapore to the average income of its residents.

### Data Sources
The data is obtained from government website domains where datasets are publicly available.
- Department of Statistics Singapore (singstat.gov.sg)
- Singapore's open Data portal (data.gov.sg)
- Some flat files obtained from the client itself includes work and home correlations

### Approach
The geographical aspect of this visualisation takes reference first with the official 28 residential districts of Singapore. After which, it is further narrowed geologically down to 300+ subzones of Singapore. Based on this 300+ subzones, and with the corresponding average income of each subzone, the visualisation is created using geographic information system (GIS). 

The first step is to obtain a shape file of Singapore with the correspodning subzones, and then to port the delimited text layer containing the csv file into the GIS system. Since the subzones should be matched up with the shape file, there should be a correlation between subzone names and polygon shapes in the file. 

After the correlation is performed, a heat map is then generated for the distribution of the income, with the intensity denoting the magnitude of the average incomes of the subzones.

<img src="Images/Geographical Income Distribution.jpg?raw=true"/></a>
