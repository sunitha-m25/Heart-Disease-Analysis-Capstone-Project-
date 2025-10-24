## Accident Report Analysis

On this project, you'll be working with data from [Gray Line Tennessee](https://graylinetn.com/), a company which offers charter bus service, sightseeing tours, black car service, and airport shuttles. You have been provided several years of accident history. 

**Objective 1: Data cleaning and organization**  
For the first objective, ingest, organize, and standardize the XLSX files for all available years into a single file. Final outputs could be XLSX, Microsoft Access (bonus if this is provided, so it can be linked to PostGRES), or another format of your choice.

The prepared data will be used to filter by year, by driver, by vehicle, by location, etc., so that we can easily search prior accidents.

Some challenges to be aware of are spelling errors, lack of address convention, lack of naming conventions, lack of driver names always matching between files (misspellings and nicknames sometimes used). Please create a unique Driver ID for the file. Some files may have one, but if not all files have one, we need a master unique identifier, if there is no natural key you must create one, that is called a “Surrogate Key”.

**Objective 2: Data visualization**  
Explore the cleaned data and create data visuals to report your findings. This is totally free for you to choose and design. You will determine the insights, use exploratory data analysis to find patterns or trends.
Some questions to get started: 
* Do accidents occur most at a certain time of day?
* What about a certain location?
* What is the most common accident type?
* Is there disparity between male and female drivers?
* Is there a correlation between certain types of accidents and different vehicle types?

A vehicle file will be provided to you so that make and model information can be LEFT joined into your repository. 