This is a personal project that I created when searching for jobs. To make my own life easier, and also to learn more about cloud and devops practices.

How does it work?
The script scrapes an Indeed search url, and collects the job information for each job. It then connects with openAI to extract and categorize variables such as programming langages, frameworks, seniority level, etc.

**Input:**
The input is an indeed filter, like: "https://nl.indeed.com/jobs?q=python+developer&l=Randstad&from=searchOnDesktopSerp&vjk=20f5fbb9784589b5"

**Output:**
The output is a csv file with extracted and enhanced job position data.

![image](https://github.com/user-attachments/assets/bab1f00a-3e9e-4cf4-9f93-7438ace584dd)

This project is still a work in progress. Next steps are to enable the app on aws-lambda so that the scrape can be called with a post-request. The return value would be the link where the completed file can be downloaded.
