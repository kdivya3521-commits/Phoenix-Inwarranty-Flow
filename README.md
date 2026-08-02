# Postman API Automation Integration with Github Actions #

This repository demonstrates the running the Postman collection scripts with Github Actions with newman and newman reports on Virtual machines
The Github actions are trigger when the push even is going to happen in main branch.The workflow can be executed on workflow_dispatch and it 
runs on cron jobs.

The HTML report can be archived section for team to download.Along with that report can be access using : https://kdivya3521-commits.github.io/Phoenix-Inwarranty-Flow/
and the report can be email using GMAIL SMTP

## About me ##
Iam Functional test engineer learning API Automation testing
!(https://www.linkedin.com/in/divyasai-k/)

## Test Coverage ##
1. Happy flow testing
2. Negative Testing
3. Token testing
4. Data driver testing
5. Schema Validation
6. Secrets Management with Github secrets

## HTML Report ##
The report will be created in newman folder
![Postman Report](https://github.com/kdivya3521-commits/Phoenix-Inwarranty-Flow/blob/static-branch/Screenshot%202026-08-02%20at%208.30.31%20PM.png)

## Project Structure ##
```
Phoenix Inwarranty Flow
├─ Inwarranty-flowCollectionEX.postman_collection.json
├─ QA.postman_environment.json
└─ testdata.csv

```

## Tech Stack ##
1. Postman
2. Node js
3. Newman
4. Newnan html reports
5. Github Actions
6. Github pages
7. Gmail SMTP
8. CSV for data driven testing
9. AWS-EC2 for Github self host runner

## Github Pages ##
You can view the latest the report Postman test link at : https://kdivya3521-commits.github.io/Phoenix-Inwarranty-Flow/

## How to run Project ##

1. Run the Postman collection locally
2. Clone the Postman collection in to git hub repo
3. Install node js
4. Install newman and reports
5. Run the newman command

