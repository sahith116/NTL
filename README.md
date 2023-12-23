NTL
Night Time Light Analysis.
NTL is an inexpensive, unbiased and easy-to-obtain source for estimating GDP,and analysing of socio-Economic parameters in India.


GOALS:
The Main Aim of This project is to Collect and Analysis of NTL data ,Examine urbanization ,Socio_Economic Activities,Environmental Changes.
Study the Impact of Electrification on Rural Sectors,Education,Agricultural Activities,Settlements Expansion.
Identifing Electrification status Through NTL data and its co-relation with Educational outcomes,other parameters  in Specific state/rural areas.
Night Lights can provide reliable predictions of short-term impact of economic shocks
State-level and sectoral GSVA predictions using VNP46A1 and making them usboptimal.

DATA SOURCES:
Three major sources of data have been used in this study - Indian economic data, nightlights data and  electricity usage data.

 INDIAN ECONOMY DATA:
 Real GDP and GSVA data at 2011-12 constant prices were downloaded from the Indian Ministry of Statistics MOSPI (2011) for the timeframe shown below:
  • Quarterly National Level Data: FY2012Q1-FY2019Q4
  1. Gross Domestic Product (GDP)
  2. Gross Value Added (GVA)
  • Annual State Level Data: FY2012-FY2019
  1. Gross State Value Added (GSVA)

ELECTRICITY USAGE DATA:
Data on state-level electricity usage was obtained from from monthly reports on national power consumption from Power System Operation Corporation (POSOCO). 
The usage is recorded as actual drawal, i.e. usage (as opposed to scheduled, i.e., projected usage) for the period between April 2012 to
June 2020 measured in units of MU, i.e., 1 Million KWh. The data was only available as an embedded table or image, in each report. A custom tool was developed using Adobe Java Libraries for MS Office to automatically extract the data from nearly 6,700 pages of PDF reports. Thereafter, using pattern matching in R, the relevant table with drawal data i have extracted for each month.

NIGHT LIGHTS DATA:
The VNP46A1 nightlights data was downloaded from NASA’s Level 1 and Atmosphere Archive and Distribution System Distributed Active Archive Center Data Center (LAADS DAAC).
Data from Feb 1, 2012 - June 30, 2020, i.e., 3072 days of data, i.e., 24,576 files containing a total of 149 million GeoTIFF files was downloaded from the website.
FILE NAME: VNP46A1 (Black Marble Dataset)
Resolution:Daily with 8 HDF5 Compressed Files (Geographic Tiles) Per Day.
Required Layers :Cloud Quality Flag, Moon Illumination, Solar Zenith, NTL Radiance
Net Files/Day:8 HDF5 Tiles × 4 Layers Each = 32 Layers.
Date Range :1 Feb. 2012 - 30 Jun. 2020.
File Info:3,072 Days × 8 HDF5 Files/Day = 24,576 HDF5 Files.
GeoTIFFs Extracted:24,576 HDF5 Files × 4 GeoTIFFs/File = 98,304 GeoTIFFS.
Total Size :98,304 × 12 MB Per GeoTIFF File = 1.18 TB.


ANCILLARY DATASET:
Data on quarterly precipitation in India has been obtained from the website of Indian Agricultural Research .Population data has been obtained from Trading Economics (2019).
Electricity Usage and Nightlights data was available for FY2012Q1 - FY2020Q1. GDP and GSVA  data was available for FY2012Q1 - FY2019Q4.



