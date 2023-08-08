# SSTS_Disc_Golf
*Repository for disc-golf related stats collection and data analysis.*

## Overview:
This project is currently not ready to data intake. When proof-of-concepts are complete, the intiial pipeline will look like the following:  
Scorecard submitted to Aaron -> Scorecard parsed and added to database -> Periodic data analysis performed and shared to a public Jupyter notebook  
Please reference the Projects and Issues tabs for current progress.

## Contribution Guide:

### Altering Static Data for the Database:
1) Feel free to contribute directly to the main branch for any of the following:
  - Adding a course
  - Adding a layout
  - Adding a player
  - Adding new holes  
Anytime the database the updated CSV files are submitted to the database, existing entries should not be affected.

2) Please make a new branch for the following:
  - Updating the existing database schema
  - Adding a new table  
This could break some stuff and be a pain to fix after the fact. When you create your new branch and are done with updates, submit a pull request and assign @pr1malbyt3s (Aaron) as the reviewer. If the updates are good, changes will be merged and the branch closed. Otherwise, some tasks will be reassigned to you for fixes.

### Updating the Codebase:
Please make a new branch for every change to the code. The issues queue contains tasks to be completed. If a relevant issue does not exist for the change being made, please create one. Once your changes are complete and ready for review, please do the following:
1) Link the issue in the commit message.
2) Submit a pull request and assign @pr1malbyt3s (Aaron) as the reviewer.  
If the updates are good, changes will be merged and the branch closed. Otherwise, some tasks will be reassigned to you for fixes.

### Resources:
Helpful for understanding the schema:
- https://medium.com/geekculture/my-golf-data-storage-and-entry-d816546bae68
- https://stackoverflow.com/questions/11615572/mysql-database-scheme-for-golf-scores

Helpful for data analysis programming and tasks:
- https://kaggle.com
