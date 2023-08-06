# CCAPDEV-Phase3-Group2

This project is meant to be a multipurpose platform for Lasallian students, wherein it provides students with a singular repository for them to socialize as well as view information that is regularly sought out by students such as "Profs to Pick" and Announcements.


How To Run

1. Execute this command into your terminal: node server
2. Press Ctrl+C to disconnect from the server after running

## Switcher()

To populate and delete the database, change this line of code inside database/index.js for the async function switcher():
const lever = your number here;
0 - to delete all contents of the database
1 - to populate the database
and any other number to stop it from deleting or populating, similarly, after populating it you may comment out this function with double dashes in front //switcher()


