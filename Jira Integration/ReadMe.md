# Jira Integeration

### Problem
Jira's reporting is not at all sophisticated, so we needed a better way to visualize & report on our issues to ensure we were getting tasks done in a timely manner, as well as sticking to our goals. 

### The Solution
Using python, we will connect to the API to pull down the data and place it into a Tableau dashboard to track progress on items. 

### Decisions
While there is a Jira python library, the python-requests library is just more versatile and simpler to use (in my opinion). Also, we already have a python environment setup with the requests library, so this means less maintenance on python environments in the future. 
