# Pipeline

The application uses CircleCI platform to create a pipeline for Continuous Integration and Deployment. CircleCI integrates with github repo, and after each push to the master branch it will trigger CircleCI pipeline to deploy the application on AWS.
![screenshot](pipeline.png)
## Steps 



## CircleCI and AWS :

### Build

- Install Node/NPM
- Checkout the github repo code
- Install the dependencies for the Backend
- Build the Backend
- Install the dependencies for the Frontend
- Build the Frontend
- Lint FrontEnd

### Hold

- Need manual approval on CircleCI to trigger deployement

### Deploy 

- Setup AWS CLI
- Setup AWS Access Key ID
- Setup Elastic Beanstalk CLI
- Deploy API to EB
- Deploy frontend to S3 bucket
