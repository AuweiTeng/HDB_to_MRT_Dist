HDB Blocks to MRT Distance Datasets
*** Description ***
This provides a dataset of HDB addresses along with their nearest MRT (Mass Rapid Transit) stations. 
It utilizes geocoding to determine the coordinates of each HDB address and 
then calculates the distance between each HDB address and its nearest MRT station 
using the Haversine formula.

These are made using OneMap geocoding REST API calls and Python libraries Request and Pandas.

You can directly use Excel to vlookup your HDB address dataset to obtain the distance. =vlookup( *Cell of interest* , *my .csv table with the full address without unit number*, *the column number of the distance you want to obtain*) 

Feel free to cite Teng Hau Wei 2023 in your citations. 
