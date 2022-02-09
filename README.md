# child_care
Texas Child Care Facilities data mapped to make it easier for families to determine, which licensed facility works best for their needs. 

## Purpose
When my son was born, I had to choose a child care facility very quickly after losing in-home care when he was 15 months old. I tackled the problem like a data analyst!    

I found the list of licensed child care facilities in Texas, all 13,0000+ facilities.  For me, I needed a facility that would take infants and was relatively close to my home and work. I also did not want a large facility, so I used the capacity as a filter.    
  
Data Source: https://www.dfps.state.tx.us/Child_Care/Search_Texas_Child_Care/ppFacilitySearchDayCare.asp 


## Cleaning the data
See the geoplot python file    

I did basic cleaning and converting of the data types using Python and the Pandas library.  What was challenging was obtaining the lat-longs for 13,000+ addresses.  Working with Tableau, it does not convert street addresses, and you are limited to only doing an analysis by city.  I ended up using Geocodio to convert the addresses to lat-longs. 

## Tableau Chart
I imported the data into Tableau and created a Story board to explore the data set. 
https://public.tableau.com/app/profile/julie.pyle2236/viz/ChildCareFacilities_16443978541850/Story1?publish=yes


## Future updates to markdown
1. Add images 
2. hyperlink the links
3. explore how to web scrape the data from the .gov website, which will make the process more automated. 
