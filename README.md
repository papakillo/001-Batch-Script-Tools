# Tools
This batch script is a file monitoring tool that waits for files in a folder and processes them once they are present, you can follow these steps:
The script checks for the presence of for four files (or any number you choose to specify) with the specified pattern.
If the count of found files with the pattern is greater than or equal to the expected file count, it triggers the SQL Server Agent job.
The script then waits for a specified time (e.g., 5 minutes) before checking again.
