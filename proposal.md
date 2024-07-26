# Final project proposal


Please prepare a short proposal on your final project idea by **Nov 2**. The proposal should include:

- Title & description of the project
- Your name & partner's name
- A description of the data required, and how it will be obtained (e.g. URL/DOI to data source)
- 3 questions / analysis tasks you will perform on the data; in the spirit of the assignments we have been doing.


What kind of environments are bigfeet most likely to live in and appear and what environments are most likely to be protected if Bigfoot was ever found real?
Melody Lui


Bigfeet are supposedly mythical creatures, but why do they have a whole website with sightings all around the United States (BRFO.net)? In order to protect the diversity of species, these big feet should be preserved. We want to find out where we can find these creatures, not only to acknowledge their existence, but to help preserve areas that are prone to bigfeet exposure. We also want to figure out where Bigfeet are most found and what they are attracted to in terms of the United States and its sightings. Why are Bigfeet more concentrated in some areas than others? 


Bigfeet sighting data: https://hub.arcgis.com/datasets/TrainingServices::-bigfoot-sightings/explore?location=37.785340%2C-100.424539%2C4.37

NDVI data to view greenness

Precipitation data, solar radiation, etc precipitation.zip 
https://corgis-edu.github.io/corgis/csv/weather/

https://cal-adapt.org/data/download/ (LOCA DOWNSCALED CMIP5 CLIMATE PROJECTIONS) 


1. What States have the most Bigfoot sightings in the United States. Construct a visual to understand where in the United States it is more likely to spot a Bigfoot. 

2. Why are some states/areas more capable of seeing bigfeet? Compare several different states and counties to understand the trends of sightings. (vector data/raster)

3. Construct a map determining how likely it would be to see Bigfoot in that area, then construct a map of areas where it is the most likely to see Bigfoot (raster data).





*You may choose to work with your partner or independently on the final project. Please indicate which clearly in your proposal.*

Replicating results of an existing study and exploring the impact of alternative assumptions in the data preparation, statistical methods chosen etc can provide an excellent template for an analysis (you'll see more of this in units 3 & 4)


Please create your proposal in a markdown file called `proposal.md` in the root directory of the final project repo.  


## Project Guidelines

### Project questions must illustrate all of the following tasks:

- Some form of data access / reading into R
- Data tidying preparation
- Initial data visualization
- Use of GitHub
- Reproducible execution with use of Travis
- RMarkdown writeup, with final submission as a nicely formatted PDF document that includes code and results.
- Overall clean and clear presentation of repository, code, and explanations.

### and at least three of the following skills (this list may be modified/extended):

- Use of at least 5 `dplyr` verbs / functions x
- Writing / working with custom R functions
- Creating an R package for functions used in the analysis
- Interaction with an API
- Use of regular expressions
- Use of an external relational database
- Preparing processed data for archiving / publication
- Parsing extensible data formats (JSON, XML)
- Use of spatial vector data (`sf` package) and visualization of spatial data x
- Creation of an R package
- Expansion of ggplot functions (to include more than default characteristics) x
- Making layout and presentation into secondary output (e.g. .pdf, website) - should enhance presentation 
- use lintr to clean code (checks adherence to a given style, syntax errors and possible semantic issues)

# Final Rubric 30 pts total

 - 5pts Proposal, turned in on time and with team member names, background, dataset, and 3 potential questions.

 - 10pts Polished github repository, including:
	 -  3pt updated readme with functional travis badge 
	 -  2pt passing travis build 
	 -  2pt clean and well formatted output document (html, pdf, or md with associated files). 
	 -  3pt enough supporting text that we can easily understand the project undertaken.
	 
 - 15 pts Project Substance: Objectives, Code, Visualization. Do you meet all of the required project objectives and at least 3 of the supplementary objectives.
	 - 15pts: exceptional
	 - 13pts: adequate and complete
	 - 11pts: adequate 2 questions, meeting 3 supplementary objectives
	 - 9pts: adequate 2 q, meeting 1-2 supplementary objectives
	 - 7pts: adequate 1 q, meeting 3 supplementary objectives
	 - 5pts: adequate 1q, meeting 1-2 supplementary objectives
