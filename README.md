#
<h1 align="center">Udacity Advanced Cloud DevOps<br></h1>  

<!-- Adding Status Badges circleci Template
# Template:
[![<ORG_NAME>](https://circleci.com/<VCS>/<ORG_NAME>/<PROJECT_NAME>.svg?style=svg)](<LINK>)

# Example:
[![CircleCI](https://circleci.com/gh/Mohamedelfal/udapeople-cicd.svg?style=svg)](https://app.circleci.com/pipelines/github/mohamedelfal/udapeople-cicd/5)

# Example for specific branch:
[![CircleCI](https://circleci.com/gh/circleci/circleci-docs/tree/teesloane-patch-5.svg?style=svg)](https://circleci.com/gh/circleci/circleci-docs/?branch=teesloane-patch-5)
<PROJECT_NAME> - Your project’s name. Example: circleci-docs
<ORG_NAME> - The organization or user name the project in question belongs to
<VCS> - your VCS provider (gh for “github” and bb for BitBucket)
<LINK> - The link you want the status badge to go to when clicked (example: the pipeline overview page)
Optional: an API token (to create badges for private projects)
-->

<h3 align="center">Build CI/CD Pipelines, Monitoring & Logging<br>Give Your Application Auto-Deploy Superpowers<br>UdaPeople<i>(Cloud-Based Software)</i></h3>  
  


# 

[![CircleCI](https://circleci.com/gh/mohamedelfal/udapeople-cicd.svg?style=shield&circle-token=499c794914a6668bd794027edc74d9400d7a361f)](https://app.circleci.com/pipelines/github/mohamedelfal/udapeople-cicd?branch=master&filter=all)
<a rel="Udacity" href="./screenshots/passed.md"><img alt="Udacity Project"  src="https://img.shields.io/badge/Udacity-PASSED-brightgre?style=plastic&logo=Udacity" /></a> <a rel="Udacity" href="./2-udacity-passed.jpg">
[![GitHub language count](https://img.shields.io/github/languages/count/mohamedelfal/udapeople-cicd)](https://github.com/mohamedelfal/udapeople-cicd)
[![GitHub top language](https://img.shields.io/github/languages/top/mohamedelfal/udapeople-cicd)](https://github.com/mohamedelfal/udapeople-cicd)
## Table Of Contents
📌 [Udapeople](#udapeople)

📌 [Prerequisites](#prerequisites)

📌 [Tools](#tools)

📌 [Files](#files)

📌 [Project_Review](#project_review)

📌 [License](#license)

<h3 align="center">UdaPeople</h3>   

<p align="center">
  <img width="" height="" src="./Screenshot/RESULTS_SCREESHOT.png">
</p>
<p align="center">
  A CI-CD pipeline for a client/server TypeScript project 
hosted on AWS EC2 and CloudFront and monitored with Prometheus,<br>
with Slack and E-mail notifications used for alerts.<br>"<small><i>the fictional "UdaPeople" Product is  (Cloud-Based Software) Product,  a revolutionary concept in Human Resources which promises to help small businesses care better for their most valuable resource: their people."</i></small>
</p>


<h3 align="center">UdaPeople Pipeline</h3>   

<p align="center">
  <img width="" height="" src="./Screenshot/pipeline.jpg"  
</p>

## Prerequisites

🪡 [Nodejs 13](https://nodejs.org/en/) ![Nodejs 13](https://img.shields.io/badge/Node.js-white?style=plastic&logo=Node.js)

🪡 [Docker](https://www.docker.com/) ![doker](https://img.shields.io/badge/Docker-white?style=plastic&logo=Docker)

🪡 [GitHub account](https://github.com/) ![GitHub account](https://img.shields.io/badge/GitHub-black?style=plastic&logo=GitHub)

🪡 [CircleCi account](https://circleci.com/) ![CircleCI](https://img.shields.io/badge/CircleCI-black?style=plastic&logo=CircleCI)

🪡 [AWS account](https://aws.amazon.com/) ![Amazon_AWS](https://img.shields.io/badge/Amazon_AWS-orange?style=plastic&logo=Amazon%20aws)

🪡 [kvdb api bucket](https://kvdb.io/) ![kvdb api bucket](https://img.shields.io/badge/kvdb-black?style=plastic&logo=kvdb)


## Tools

🧵 [Circle CI](https://www.circleci.com) - Cloud-based CI/CD service ![CircleCI](https://img.shields.io/badge/CircleCI-black?style=plastic&logo=CircleCI)

🧵 [Amazon AWS](https://aws.amazon.com/)- Cloud services ![Amazon_AWS](https://img.shields.io/badge/Amazon_AWS-orange?style=plastic&logo=Amazon%20aws)

🧵 [AWS CLI](https://aws.amazon.com/cli/) - Command-line tool for AWS [![AWS CLI](https://img.shields.io/badge/AWS_CLI-orange?style=plastic&logo=Amazon%20aws)](https://aws.amazon.com/cli/)

🧵 [CloudFormation](https://aws.amazon.com/cloudformation/) - Infrastrcuture as code ![CloudFormation](https://img.shields.io/badge/CloudFormation-orange?style=plastic&logo=Amazon%20aws)

🧵 [Ansible](https://www.ansible.com/) - Configuration management tool [![Ansible](https://img.shields.io/badge/Ansible-black?style=plastic&logo=Ansible)](https://www.ansible.com/)

🧵 [Prometheus](https://prometheus.io/) - Monitoring tool ![Prometheus](https://img.shields.io/badge/Prometheus-white?style=plastic&logo=Prometheus)
#
<h2 align="center">Project Submission</h2>  

<p align="center">
  <img width="" height="" src="./Screenshot/pipelineresult.png"  
</p>
    
## Files
🗂️ [.circleci](./.circleci)

🗂️ [.cloudformation](./.circleci/cloudformation)

🗂️ [.ansible](./.circleci/ansible)

🗂️ [backend](./backend)

🗂️ [frontend](./frontend)

🗂️ [util](./util)

🗂️ [.gitignore](./.gitignore)

🗂️ [Screenshots](./screenshots/)

🗂️ [presentation.pdf](./Presentation.pdf)

🗂️ [urls.txt](./urls.txt)

🗂️ [README.md](./README.md)

🗂️ [LICENSE.md](./LICENSE.md) 


## Project_Review

https://review.udacity.com/#!/reviews/3915432

## License  

<a rel="license" href="./LICENSE.md"><img alt="Udacity License"  src="https://img.shields.io/badge/license-Udacity-blue.svg" /></a>

<!-- small <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/80x15.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License</a>. -->


 
