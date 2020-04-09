# ATMS 597 SP 2020
## Project 4 - Using regression for prediction (version 1.0)

### Due Thursday, April 3, at midnight

You will work in groups of 3 to complete this assignment, which are assigned on Learn@Illinois. Students who are not taking the course for credit may join to form their own groups, however their assignment will not be graded.

Tasks: Use supervised classification techniques to predict frozen vs. liquid precipitation type (i.e., when it is *not* raining, so rain and freezing rain vs. other categories such as snow, sleet, etc.) at the surface in ASOS weather observations.

Model 1: Support Vector Machine classification with default values (baseline)
Model 2: Your pick!

Data: You will use 5-minute Automated Surface Observation System data available from NCDC (ftp://ftp.ncdc.noaa.gov/pub/data/asos-fivemin/).  Data from 2000-2020 is available.  Use a 70-30 random split to perform training and validation.

You can use Temperature, Dewpoint, Wind Direction, Wind Speed, and other derived variables from those data, or synthetic variables such as solar zenith angle, time of day, etc.

Each group will have a separate Midwest US city to examine:

Group A: KDBQ (Dubuque, IA)
Group B: KDSM (Des Moines, IA)
Group C: KMSN (Madison, WI)
Group D: KASX (Ashland, WI)
Group E: KSAW (Marquette, MI)
Group F: KMKG (Muskegon, MI)
Group G: KBJI (Bemidji, MN)
Group H: KRST (Rochester, MN)

The group with the improvement of values of Briar Skill Score for their Model 2 over the baseline SVM model will be given a prize.

Good luck!