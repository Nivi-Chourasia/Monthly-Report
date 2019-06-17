# Monthly Report Presentation
 
June 28, 2019. 

### Purpose

To help build the Monthly Report Presentation. 

### Tableau Books Requirement
|Amounts_August_Nivi.twb|
|Platform_Data.twb|
|Spend.twb|
|Threshold.twb|


### Data Requirements (From the Script)
PO Amounts
Platform Data2
SB SS Data
Buyer Counts and Spending Sheet


### Data Manipulation
##### Platform Data2: (changing 'Method')
1. For all the inventory purchases, anything that is not a sole source but is below 50K as an "Fairmarkit Quote" (except for     DMartinos)
2. EWELSH, JDELLALA, TDIONNE : Not Fedral + filter out SWC -> should be marked as Commbuys Market
3. KLOVE, PHONG, TSULLIVAN1: all Sole Sources - OEM below 50K as a Fairmakit Quote.
4. Convert these to Commbuys Market
     
  | PO. No.  |  
|---|
|9000006897  | 
|9000006795  | 
|9000006794  | 
|9000006763  |
|4000091212  |
|4000091025  |
|4000091023  |
|4000091022  |
|4000091495  |
|4000091496  |
|4000091497  |


##### PO Amounts: (changing 'Bid Type')
1. All MBTAI below 50K, From 'IFB' to 'Request for Quote' (except (2000108600/01)
2. All unspecifed to 'Request for Quote' (except 2000107343,4000092098/214/215)



### Presentation Slides:
|     Slide     |     Tableau Book    | Sheet/ Dashboard |   Excel Sheet   |
| ------------- |:-------------------:| ----------------:|----------------:|
|       3       |      Spend.twb      |    Dashboard 1   |   PO Amounts    |
|       4       | Amounts_August_Nivi |    Totals        |   PO Amounts    |
|       5       |    Platform_Data    |    Dashboard 1   | Platfrom_data2  | 
|    6(Graph)   |    Threshold.twb    |    Dashboard 1   |   PO Amounts    |
|       6       |         N/A         |        N/A       |PO Amounts/Vendors Sheet|
|       7       |         N/A         |        N/A       | SB SS Data File |
|       8       |  Amount_August_Nivi |    Dashboard 7   |   PO Amounts    |


