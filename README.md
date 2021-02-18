# run-Requirement

A webscraping python script I implemented to force myself to get out of bed to run in the morning.

The script downloads a spreadsheet file from the Garmin Connect database, (Which I use to track running data with my watch) and checks the spreadsheet to verify if I ran that morning.

If I don't run, the script will autonomously cut off networking capabilities on my desktop system.

The current version is being automated with crontab on Ubuntu 20.04. 
