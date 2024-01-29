Please find [here](https://git.sbg.ac.at/s1095729/sdi_sudan_migration/-/wikis/Home) the project Wiki. 

## Project title
SudMig - **Sud**an: monitoring **Mig**rant movements related to the 2023 conflict.

## Description
The SudMig project aims at developing an interactive dashboard that provides valuable insights on the latest Sudanese internal migration. This is done by developing a well-founded underlying SDI (Spatial Data Infrastructure) strategy for the efficient and transparent gathering, processing and sharing of the migration geodata and the effective visualization in an informative dashboard. The SudMig dashboard, thereby, supports United Nation’s decision-making processes related to the 2023 military conflict which causes millions to flee to other parts of the country and neighbouring countries.    

Different parameters related to Sudanese internal migration, such as the number of Internally Displaced People (IDPs), their origin and destination within Sudan, the demographics as well as geocoded data, like Sudan’s administrative boundaries, will be collected, organized, and visualized effectively. The data will be organized and stored in a PostgreSQL (PostGIS) database management system and published with web-services, such as the OGC Web Map Service and Web Feature Service. Finally, the data will be integrated into the SudMig dashboard, so that our important migration parameters and trends can create impact by being communicated to the decision-makers briefly and at a glance.  

## Contribution
Suggestions or comments from other students and external interested people are highly appreciated! 

## Authors and acknowledgment
Stamatina Tounta - 3rd Semester Student M.Sc. A. Geoinformatics at the Paris-Lodron-University Salzburg (stamatina.tounta@stud.plus.ac.at) <br>
Noah Greupner - 3rd Semester Student M.Sc. A. Geoinformatics at the Paris-Lodron-University Salzburg (noah.greupner@stud.plus.ac.at) 

## Project status
The project is currently active and will be finished in early 2024. 

## Folder structure
Please find in the repository the SudMig documents and data.

In the '**Project_management**' folder you find the following documents:
- Gantt Chart (PDF)
- Time sheets of the authors (EXCEL)
- Project proposal (PDF)
- Mid-term project presentation (PDF)
- Milestones (PDF)
- Work breakdown structure (PDF)
- Initial project idea (PDF)
- Final project presentation (will be added by end of January 2024)
- Final project report (will be added by mid of February 2024)

In the '**Data**' folder you find:
- the geodata ('SudMig_Sudan_AdmBoundaries_Level1.zip') that was used to geocode the actual migration data (.shp) <br>
- the geocoded migration data ('SudMig_Monthly_IDPs_Displacement.zip') which was joined with the geodata by using the state of displacement of IDPs (.shp) <br>
- the geocoded migration data ('SudMig_Monthly_IDPs_Origin.zip') which was joined with the geodata by using the state of origin of IDPs (.shp) <br>

In the '**Metadata**' folder you find:
- the ISO19139-compliant metadata of the SudMig dataset in XML format ("SudMig_Monthly_IDPs_2023_ISO19139.xml") as well as in human-readable format ("SudMig_Monthly_IDPs_2023.pdf and .html)
- the ISO19139-compliant metadata of the administrative boundaries of Sudan also in XML, PDF, and HTML format ("SudMig_Sudan_AdmBoundaries_Level1_ISO19139")    
