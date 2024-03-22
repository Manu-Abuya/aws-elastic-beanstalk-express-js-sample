# AWS Elastic Beanstalk Node.js Sample App

This repository contains a sample Node.js web application built using [Express](https://expressjs.com/), meant to be used as part of the AWS DevOps Learning Path.


## Overview
This project aims to demonstrate the creation of a continuous delivery pipeline using AWS services. The pipeline involves setting up a Git repository, deploying a sample web application, and automating the deployment process with a continuous delivery pipeline.

## Technologies Used
- AWS Elastic Beanstalk
- AWS CodeBuild
- AWS CodePipeline
- GitHub

## Setup Instructions
Follow these steps to set up the continuous delivery pipeline:

1. **Create an AWS Elastic Beanstalk Environment:**
   - Create an Elastic Beanstalk environment to deploy the application. You can choose the appropriate environment configuration based on your requirements.

2. **Configure AWS CodeBuild:**
   - Set up AWS CodeBuild to build the source code from the GitHub repository. Configure build specifications as per the requirements of your application.

3. **Set Up AWS CodePipeline:**
   - Use AWS CodePipeline to create the continuous delivery pipeline. Configure the pipeline with source, build, and deploy stages.
   - Define the source stage to fetch the source code from the GitHub repository.
   - Configure the build stage to use AWS CodeBuild to compile and package the application.
   - Set up the deploy stage to deploy the application to the AWS Elastic Beanstalk environment.

## Usage
To use this continuous delivery pipeline:

1. Push your application code to the configured GitHub repository.
2. AWS CodePipeline will automatically trigger the pipeline.
3. Monitor the pipeline execution in the AWS Management Console.
4. Once the pipeline completes successfully, access your application deployed on AWS Elastic Beanstalk.

## Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to submit a pull request.


## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.

