1. Download entries from milesplit as a csv file
2. Delete all columns except for Event LName, FName,Team, Grade
3. Organize so the the columns are in the following order
Event | Team | Grade | LName | FName
4. Insert the column Name between Team and Grade
Event | Team | Name | Grade | LName | FName
5. Use the =concanate function in the name column to concanate FName & LName
example 

=CONCATENATE(F2," ",E2)

6. Select all of the content to be copied from Team | Name | Grade | LName | FName without the column headers and don't need the event data. But use the Event to know which gender is to be included

7. Paste the selected data in CC.xls file (https://scottssoftware.wordpress.com/scotts-software/cross-country-scoring-software)
8. Select how you want to order the Bib column
9. Open xnotestopwatch (if using excel integration)
9a. Select excel integration select spreadsheet and start below below
CC.xls::Score 
Cell C2 and use text value
9b. Timing will be placed in the spreadsheet time location
10. Can print results
11. Also export results from excel as a text document to be uploaded to milesplit.


