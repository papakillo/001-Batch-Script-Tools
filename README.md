# Tools
This repository documents productivity tools that can be utilised in daily routines to automate repetitive tasks.

## Monitor specific files before processing
This batch script is designed to monitor a specific folder for the most recent files that match certain patterns. It then checks if all the specified files are present before triggering a SQL Server Integration Services (SSIS) job. This is useful when the availability of files for downstream processing is erratic. So this batch script, when activated, would just wait for the files to arrive and then subsequently start the SQLAgent job.
1. [Click to access : Monitor Files In Folder](https://github.com/papakillo/Tools/blob/papakillo_file_upload_changes/monitor_specific_files_before_processing.bat)

## Monitor files of a specified pattern before processing
This batch script is a file monitoring tool that waits for files in a folder and processes them once they are present, you can follow these steps:
The script checks for the presence of for four files (or any number you choose to specify) with the specified pattern.
If the count of found files with the pattern is greater than or equal to the expected file count, it triggers the SQL Server Agent job.
The script then waits for a specified time (e.g., 5 minutes) before checking again.
1. [Click to access : Monitor Specific Files Before Processing](https://github.com/papakillo/Tools/blob/papakillo_file_upload_changes/monitor_specific_files_before_processing.bat)



