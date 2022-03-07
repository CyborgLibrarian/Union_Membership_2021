# Union_Membership_2021
These datasets depict union membership and collective bargaining agreements in four metropolitan areas in the United States in 2021. The intended stakeholder group for these datasets are policymakers. These datasets were curated for LIS 545 at University of Washington, Winter 2022.

These datasets are available in .csv format.

## Table of Contents
1. [General information](#GeneralInformation)

2. [Data Dictionary](#datadictionary)

3. [Metadata](#metadata)

4. [Security](#security)

5. [Contact](#contact)

## General Information <a name="GeneralInformation"></a>

1. Title of Datasets: 

   Labor Union Membership and Collective Bargaining Agreement Coverage
   
   File #1: Union_Membership_2021.csv
   
   File #2: Collective_Bargaining_2021.csv

2. Author Information:

    Name: Taylor Agajanian & Emma May
    
    Institution: University of Washington
   
    Email: tjaggie@uw.edu

3. Date of data collection:

    Data was consolidated from the original dataset on unionstats.com the week of 2022-02-27.

    The original UMC data was collected from the United States’ Census Bureau’s Current Population Survey in May 2021.

4. Geographic location of data collection (where was data collected?): 

    UMC data used in this dataset cover union membership and collective bargaining in four metropolitan areas including Los Angeles — Long Beach, 
    Seattle — Tacoma, Dallas — Fort Worth, and Johnson City — Kingsport — Bristol.
    
## Data Dictionary <a name="datadictionary"></a>

|CSV File(s)                                         |Variable Label    |Variable Type|Measurement Unit|Allowed Values                    |Description                                                                                                                   |
|----------------------------------------------------|------------------|-------------|----------------|----------------------------------|------------------------------------------------------------------------------------------------------------------------------|
|Union_Membership_2021 and Collective_Bargaining_2021|csa               |string       |varchar         |n/a                               |Name of Combined Statistical Area (CSA), excluding state information                                                          |
|Union_Membership_2021 and Collective_Bargaining_2021|csa_Code          |integer      |varchar         |Integers greater than 0           |Code assigned to Combined Statistical Area (CSA) by the US Census Bureau                                                      |
|Union_Membership_2021 and Collective_Bargaining_2021|employed          |integer      |numeric         |Integers greater than 0           |Total number of employed wage and salary workers, ages 16 and over                                                            |
|Union_Membership_2021                               |employed_Members  |integer      |numeric         |Integers greater than 0           |Total number of employed workers (ages 16 and over) who are union members                                                     |
|Union_Membership_2021                               |p_employed_Members|integer      |numeric         |Numbers between 0-100 (percentage)|Percent of employed workers who are union members                                                                             |
|Collective_Bargaining_2021                          |employed_Covered  |integer      |numeric         |Integers greater than 0           |Total number of employed workers who are covered by a collective bargaining agreement                                         |
|Collective_Bargaining_2021                          |p_employed_Covered|integer      |numeric         |Numbers between 0-100 (percentage)|Percent of employed workers who are covered by a collective bargaining agreement                                              |
|Union_Membership_2021 and Collective_Bargaining_2021|private           |integer      |numeric         |Integers greater than 0           |Total number of private sector wage and salary workers, ages 16 and over                                                      |
|Union_Membership_2021                               |private_Members   |integer      |numeric         |Integers greater than 0           |Total number of private sector wage and salary workers (ages 16 and over) who are union members                               |
|Union_Membership_2021                               |p_private_Members |integer      |numeric         |Numbers between 0-100 (percentage)|Percent of private sector wage and salary workers (ages 16 and over) who are union members                                    |
|Collective_Bargaining_2021                          |private_Covered   |integer      |numeric         |Integers greater than 0           |Total number of private sector wage and salary workers (ages 16 and over) who are covered by a collective bargaining agreement|
|Collective_Bargaining_2021                          |p_private_Covered |integer      |numeric         |Numbers between 0-100 (percentage)|Percent of private sector wage and salary workers (ages 16 and over) who are covered by a collective bargaining agreement     |
|Union_Membership_2021 and Collective_Bargaining_2021|public            |integer      |numeric         |Integers greater than 0           |Total number of public sector wage and salary workers, ages 16 and over                                                       |
|Union_Membership_2021                               |public_Members    |integer      |numeric         |Integers greater than 0           |Total number of public sector wage and salary workers (ages 16 and over) who are union members                                |
|Union_Membership_2021                               |p_public_Members  |integer      |numeric         |Numbers between 0-100 (percentage)|Percent of public sector wage and salary workers (ages 16 and over) who are union members                                     |
|Collective_Bargaining_2021                          |public_Covered    |integer      |numeric         |Integers greater than 0           |Total number of public sector wage and salary workers (ages 16 and over) who are covered by a collective bargaining agreement |
|Collective_Bargaining_2021                          |p_public_Covered  |integer      |numeric         |Numbers between 0-100 (percentage)|Percent of public sector wage and salary workers (ages 16 and over) who are covered by a collective bargaining agreement      |

## Metadata <a name="metadata"></a>
Schema Used: Project Open Data

|Attribute  |Value                                                                                                                                                                                             |
|-----------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|accessLevel|public                                                                                                                                                                                            |
|fn         |Taylor Agajanian                                                                                                                                                                                  |
|hasEmail   |mailto:tjaggie@uw.edu                                                                                                                                                                             |
|conformsTo |https://project-open-data.cio.gov/v1.1/schema                                                                                                                                                     |
|description|This dataset concerns labor union membership rates in Seattle, Los Angeles, Dallas-Fort Worth and Johnson City areas. The dataset was curated for a class at the University of Washington in 2022.|
|format     |CSV                                                                                                                                                                                               |
|issued     |3/7/20                                                                                                                                                                                            |
|keyword    |"union", "labor", "workers", "seattle", "los angeles", "dallas", "johnson city"                                                                                                                   |
|license    |http://creativecommons.org/publicdomain/zero/1.0/                                                                                                                                                 |
|language   |en-us                                                                                                                                                                                             |
|modified   |3/7/20                                                                                                                                                                                            |
|publisher  |Taylor Agajanian and Emma May                                                                                                                                                                     |
|references |https://www.unionstats.com/; https://www.unionstats.com/Met_121.xlsx                                                                                                                                                                       |
|rights     |These data are freely available to all people, both in this repository and their respective government repositories.                                                                              |
|temporal   |2021                                                                                                                                                                                              |
|theme      |unions                                                                                                                                                                                            |
|title      |Labor Union Membership and Collective Bargaining Agreement Coverage                                                                                                                               |
## Security <a name="security"></a>

These curated datasets are freely available to all people, both in this repository and their respective government repositories.

Original data citation: Barry T. Hirsch and David A. Macpherson, "Union Membership and Coverage Database from the Current Population Survey: Note," Industrial and Labor Relations Review, Vol. 56, No. 2, January 2003, pp. 349-54 (updated annually at unionstats.com). 

## Contact <a name="contact"></a>

Taylor Agajanian tjaggie@uw.edu
