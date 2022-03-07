# Union_Membership_2021
These datasets depict union membership and collective bargaining in four metropolitan areas in the United States in 2021. The intended stakeholder groups for these datasets are policymakers, researchers, and workers themselves. These datasets were curated for LIS 545 at University of Washington, Winter 2022.

These datasets are available in .csv format. 

## Table of Contents
General information

Data Dictionary

Metadata

Security

Contact

## General Information

1. Title of Datasets:
   
   File #1: Union_Membership_2021.csv
   
   File #2: Collective_Bargaining_2021.csv

2. Author Information:

    Name: Taylor Agajanian & Emma May
    
    Institution: University of Washington
   
    Email: tjaggie@uw.edu

3. Date of data collection

    Data was consolidated from original Union Stats sources the week of 2022-02-27.

    The original Union Stats data was collected by Union Membership and Coverage Database (UMC) researchers in May 2021.

4. Geographic location of data collection (where was data collected?): 

    UMC data used in this dataset cover union membership and collective bargaining in four metropolitan areas including Los Angeles — Long Beach, 
    Seattle — Tacoma, Dallas — Fort Worth, and Johnson City — Kingsport — Bristol.
    
## Data Dictionary

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
