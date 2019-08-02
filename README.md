# Do Open Source Projects Deliver Pull Requests Faster Using CI? 

This repository includes data and scripts from the paper  [**Do Open Source Projects Deliver Pull Requests Faster Using CI? A Conceptual Replication Study**](#)

This study collected data from many GitHub open source projects, empirically investigated whether Continues Integration (CI) affects the delivery rate of Pull Requests (PR).
        

File [RQ1.ipynb](RQ1/RQ1.ipynb) analyzed metadata from [pull_requests_meta_data.csv](RQ1/pull_requests_meta_data.csv) and [releases_meta_data.csv](RQ1/releases_meta_data.csv). 

[RQ2.1.Rmd](RQ2/RQ2.1.Rmd) and [RQ2.2.Rmd](RQ2/RQ2.2.Rmd) analyzed the two questions of RQ2 in the paper respectively. Tabular data in [pull_requests_csv.rar](RQ2/pull_requests_csv.rar) and [pull_requests_raw_csv.rar](RQ2/pull_requests_raw_csv.rar) were used. 

[RQ3.ipynb](RQ3/RQ3.ipynb) analyzed 54 new projects with CI adopted and 28 projects that never adopted CI. [RQ3_projects_info.csv](RQ3/RQ3_projects_info.csv) lists the created time and whether it has adopted CI of each 82 projects. csv files with _-ci_ at the end are dataset of projects with CI. csv files with _-nci_ at the end are datasets of projects without CI.

util folder contains helper functions of calculating Cliff's Delta. The scripts were created by [neilernst](https://github.com/neilernst/cliffsDelta). 
