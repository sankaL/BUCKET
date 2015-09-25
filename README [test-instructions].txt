Group 2
Sankalpa Lokuliyana
Meenakshisundaram Murugesan

scripts: runTESTS, compareTESTS

Make sure the following files are present in the current directory:
- ticketV3.jar (the program itself)
- AvailableTickets.txt
- CurrentUserAccounts.txt
- DailyTransactionFile.txt (will be created dynamically)
- runTESTS [shell script]
- compareTESTS [shell script]


Inorder to run the test do the following:

1) run testcases --> ./runTESTS
	this will create the RUN directory and store all the dynamically created output files
2) make sure testcases pass --> ./compareTESTS
	this will compare the files in the RUN dir to the files in the EXP dir.
	Any mismatches will be reported at the end of test script, with the .err file to check for error.
	As of now all testcases are clean.

If you want to just run the program itself
> java -jar ticketV3.jar


SOUCE CODE --> "./TICKET_SERVICE"