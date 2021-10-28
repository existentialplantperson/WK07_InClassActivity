# WK07_InClassActivity
Angela Spencer 10/27/2021

1. Create an account on lucidchart.com and create an ERD diagram for the following
scenario:
A grocery store owner would like to store all their data in a database. Some important
facts you need to include are
1) The owner has multiple stores
2) The owner has multiple employees and the managers report to him, but all other
employees report to store managers
3) The store has a membership program, but not all customers need to be members
Aside from this, use what you know about grocery stores to create a logical data model.

https://lucid.app/lucidchart/04cdde93-b419-4b65-90d8-2392cd84ac0c/edit?viewport_loc=140%2C50%2C1300%2C954%2C0_0&invitationId=inv_b5a8089c-049d-4556-9fa3-ddb3a4834c77

2. With your group, create a list of at least 5 and no more than 10 ways data can be “dirty”.
Perhaps think back to some data sets we have used that have had weird stuff in them. Discuss
how you would resolve each of these and briefly explain.
#1. missing values 
 -- replace with 0 or drop data depending on data type; can also consider taking an average to replace the value
#2. white spaces 
--rename columns or row entries
#3. string data in a value column
--remove characters that are non numerical
#4. grammar errors/typos
--update and standardize, can use LIKE % to group
#5. spelling variance
--update and standardize, can use LIKE % to group

3. Look at the requirements for the exploratory data analysis project. List at least 2 APIs that
have data interesting to you. Please pick at least one API that’s not listed in the project
instructions.
I am interested in the NASA API and the Music API for a potential project.

Other interesting APIs:
COVID19 API https://covid19api.com/
OpenLibrary API https://openlibrary.org/developers/api

