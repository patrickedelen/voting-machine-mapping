# voting-machine-mapping

## Rationale

This project aims to highlight regional differences in voting machines across counties in Texas. It will help us better understand vulnerabilities by location, and the number of voters who could be affected by compromised equipment. 

In Texas, elections are administered at the county level. The State of Texas issues a pre-approved list of voting machines that can be bought and implemented at each county's discretion. 

Over time, equipment is upgraded and replaced by the counties. In order to understand the "inventory" of voting machines, the State conducts an annual survey of the counties.

This data is publicly available, but it is difficult to access. It is published as a PDF.

We will create a dataset of voting equipment and known vulnerabilities. We will also map the data.

## Additional Features

This project could also educate people on what to expect when they get to the polls from a simulator for their specific voting machine to a virtual ballot that allows them to easily reach the candidate's websites. 

The voting machine map could be a one-stop-shop to get people ready to vote.


## To Do
### Research
Our data is helpful, but incomplete. We will need help to:
- Determine age of each voting machine and its version
- Determine which threats exist to currently deployed voting machines
- Examine the union of existant, known threats and deployed voting machines

### Data Management
- Combine voting machine data with Texas counties shapefile
- Set up combined data as a service on ArcGIS.com 

### Data Analysis
- Count of voting machines and average age
- What counties rely on the most varied tech (different types of voting machines)?

### UX Development
- Decide on a mapping service to suit the dataset
- Evaluate most useful information and prioritize showing that

### Search Tool
Voters should be able to search for their name and find their voting location. Harrisvotes.com has a search tool that could be used to search for precinct locations if we can get the API requests to work correctly.


## Useful Links:
- [Current Vote Texas webform to educate citizens on voting machine availability by county and use](http://www.votetexas.gov/voting/how/)
- [Open Texas plotting of counties with the state (look here to download GeoJSON or Shapefiles)](https://data.texas.gov/dataset/County-Map/48ag-x9aa)
- [Data source for voting system by county: Texas Secretary of State](http://www.sos.state.tx.us/elections/forms/sysexam/voting-sys-bycounty.pdf)
