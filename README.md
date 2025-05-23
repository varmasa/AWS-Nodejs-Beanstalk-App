AWS Node.js Application with Elastic Beanstalk and CI/CD Pipeline

This repository contains an AWS Elastic Beanstalk Node.js application deployed using AWS CodePipeline for continuous integration and continuous deployment (CI/CD). It demonstrates deploying two environments: a test environment and a production environment.

Project Overview

Application Name: MyApp

Platform: Node.js 18

Deployment Method: AWS Elastic Beanstalk

CI/CD Tool: AWS CodePipeline

Source Control: GitHub

Repository Structure

AWS-Nodejs-Beanstalk-App
├── app
│   ├── index.html
│   └── package.json
└── buildspec.yml

Features

Automated deployment using AWS CodePipeline.

Separate test and production environments.

Manual approval step before production deployment.

AWS Components

Elastic Beanstalk

Test Environment:

URL: http://myapp-env-test.eba-xxxxx.us-east-1.elasticbeanstalk.com

Node.js version: 18.x

Production Environment:

URL: http://myapp-env-prod.eba-xxxxx.us-east-1.elasticbeanstalk.com

Node.js version: 18.x

CodePipeline

Pipeline name: My-CICD

Source stage linked to GitHub.

Automatic deployment to test environment upon new commits.

Manual approval step for deployment to production.

Deployment Workflow

Code Commit: Commit changes to the GitHub repository.

Automatic Deployment to Test:

CodePipeline fetches the latest commit and automatically deploys to the test environment.

Manual Approval for Production:

After validating the test environment, manually approve the deployment to production.
