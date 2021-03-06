# RepoSummariser
A tool that analyses the open source contributions across GitHub of all contributors to a given project and compares that to your own activity acroos GitHub. A pdf report is generated of the same, which can help users find out how compatible they are with a given project on Github.

![image](https://user-images.githubusercontent.com/54976429/116203647-89289c00-a759-11eb-89ce-581a57a9b78c.png)


## Python Libraries
fpdf, json, numpy, matplotlib, pprint, statistics, datetime, os, random, github, requests, mimetypes.

## Instructions to run the tool
1. Download/clone the repository
2. Open a terminal window in project directory and run the following command
> python ui/
3. A web based UI will open. Fill the relevant details and click on submit.
4. The report once generated will be stored in *ui/reports* folder

**NOTE:** Due to rate limit on github API, the report generation might take some time. 
