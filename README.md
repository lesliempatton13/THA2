# THA2-README
## **The Effect of Natural Disasters on Student Learning**

**Title of Research:**
The Effect of Natural Disasters on Student Learning: A Case Study of Hurricane Harvey and Gulf Coast School Districts 

**Research Question:** Is student learning affected by the presence of a natural disaster and what policies does the State of Texas have in place to combat this? 

**Objectives:**
* To identify any significant changes in student learning after a natural disaster using STAAR (State of Texas Assessment of Academic Readiness) data of secondary students
* To asses current strategies used by the state of Texas in addressing and accommodating student learning amidst a natural disaster

**Data Sets Used:** 
* STAAR aggregated 2016-2017 English I and 2017-2018 English II campus level data
* High Water Mark and Peak Summaries of Incidents Data from USGS during Hurricane Harvey




**Overview:** 

To date, little research has been done on the effects of student learning and overall achievement after a natural disaster in the community at the secondary level. Hurricane Harvey hit in late August of 2017, damaging regions from the southern Gulf Coast of Texas all the way to the borders of Louisiana. Houston, the largest city affected by the storm, received an unprecedented amount of rainfall causing flood waters to rise throughout the suburbs and city in areas around bayous. Surrounding school districts were shut down for a few weeks to over a month as families were displaced from their homes and lost all belongings to flood waters. 

Post Hurricane Harvey, students eventually returned to schools but remained in a state of recovery in rebuilding their family homes and acquiring new belongings. While much psychological work has been done school-age children and post-natural disaster recovery, far fewer investigations have looked at how these ramifications have impacted student learning in the classroom. The scope of this project seeks to fill that gap in identifying any significant decreases in student learning and achievement in areas affected by Hurricane Harvey along the Gulf Coast of Texas.

The STAAR English I and II data sets reports a variety of indicators to assess student learning. The ones of particular interest are at the campus level of: 
* The percentage of all students tested for a campus 
* The percentage of students that did not meet grade level performance
* The percentage of students approaching grade level performance
* The percentage of students that meets grade level performance
* The percentage of students that master grade level performance

In an attempt to get an accurate snapshot of student learning, the same set of students will be analyzed by looking at the English I 2017 STAAR scores compared to the English II 2018 STAAR scores. Using these indicators, a **T-test** will be run to determine significant changes at the campus level pre- and post-Harvey. Any significant change will be identified and mapped onto the state of Texas along with all other non-significant change at the campus level using qGIS, and overlaid with high water mark data to determine areas where both extensive flooding and a decreases in academic achievement occurred. 

The expectation is to find areas where this paradigm exists and run a chi-square test to ensure that the level of flooding is in fact correlated with student learning. Upon looking at campuses and districts heavily effected, the accommodations the campus/district provides will be examined. To date, there exists no natural disaster 504 accommodations, which are accommodations normally given to students with emotional distress, attention deficit disorder, etc. I propose the State of Texas should adopt an “emergency” 504 plan for students immediately after a natural disaster whose families incurred damage and loss of possessions. 

### Data Management Plan ###
**Data Collection**
* Collected STAAR aggregate campus level data from the TEA website; data is open source and anonymized.
* Downloaded CSV data from USGS that reports on high water level areas during Hurricane Harvey as well as reports of incidents processed as "Peak Summaries Data"
* *Still need to create/collect database for all high school locations and further clean data to only include schools with documented coordinates*

**Documentation and Metadata**
* Data manipulation (calculating T-Tests) will be done and document in Colab, and each indicator T-Test Colab file will be downloaded and put into this repository.

**Ethics and Legal Compliance**

**Storage and Backup**
* The data will be stored in this repository, and backed up via Colab. The data will thus be stores in three places: on my personal computer, in Colab (which automatically saves), and in this repository.

**Selection and Preservation**
* Data that is both shareable and long-term is the geographic locations of the high schools in Texas, as well as the resulting data showing any significant changes in test scores before and after Harvey. 

**Data Sharing**
* The database created for coordinates of Texas High Schools will be shared publicly.The location of sharing this data is to be determined. 

**Responsibilities and Resources**






