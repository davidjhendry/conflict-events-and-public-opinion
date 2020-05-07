# Conflict Events and Public Opinion Project: How Subjective Grievances Relate to Conflict Incidence

Repository for project merging survey data with conflict events. This is a collaborative project with Sunhee Park.

The goals:
1. Use geographic id number and codebook information to give Afrobarometer survey respondents sub-national geography names that match ISO codes and Global Administrative Dataset.
2. Use ISO codes and sub-national geography names to merge in sub-national demographic and other characteristics.
3. Construct subjective grievance scores for sub-national units using synthetic multilevel regression with poststratification.
4. Geolocate conflict events within subnational units and construct aggregate conflict measures (e.g., does conflict exist or not, number of deaths, etc.)
5. Examine relationship between subjective grievance scores and conflict measures.

Structure of the repo:
* `analysis` folder contains scripts for data cleaning
* `geolocate_survey_respondents.Rmd` constructs sub-national geographic names for Afrobarometer respondents


Current status:
* In the process of constructing sub-national geographic names for Afrobarometer respondents

