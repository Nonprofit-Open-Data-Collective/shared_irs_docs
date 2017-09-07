### Shared docs

In this directory, schedule_parts.csv, groups.csv and variables.csv represent schedule parts, repeating groups and variables found in the xml 990's.


### Coverage

The material in this repo is intended to work on recent versions only: ['2013v3.0', '2013v3.1', '2013v4.0', '2014v5.0', '2014v6.0', '2015v2.0', '2015v2.1', '2015v3.0'] though the medium-term goal is to include versions back to 2009.

Not every attached form is included: this is intended to process the 990, 990EZ, 990PF, the return header, and all "lettered" schedules--schedules A through O and R. 


#### Generated docs

django\_models\_auto.py and sqlalchemy\_models\_auto.py are my most current versions of relational databases that cover the tax years 2013 and fowards. The line, description and xpath shown are from the "canonical" version chosen, 2015v2.1.

These will be transformed into two csv files, one listing the variables and the other the database table details. Some details will be repeated in both files for convenience. 

#### Variable types

Variable types are listed in the variables.csv file. This repo is under development--some variable types may change. In instances where variable data is missing, a text field is used. 