# Tools
This repository documents productivity tools that can be utilised in daily routines to automate repetitive tasks.

## monitor_specific_files_before_processing
This batch script is designed to monitor a specific folder for the most recent files that match certain patterns. It then checks if all the specified files are present before triggering a SQL Server Integration Services (SSIS) job.
[Click to access : Monitor Files In Folder]()

This batch script is a file monitoring tool that waits for files in a folder and processes them once they are present, you can follow these steps:
The script checks for the presence of for four files (or any number you choose to specify) with the specified pattern.
If the count of found files with the pattern is greater than or equal to the expected file count, it triggers the SQL Server Agent job.
The script then waits for a specified time (e.g., 5 minutes) before checking again.


