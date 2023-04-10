# Infrastructure Description
## AWS Services
___
1. AWS RDS 
   - It's a service provided by AWS to create a database to be used in your applicatin 
   - Connected to the api application
2. AWS Elastic Beanstalk
  - It's a service provided by AWS to host backend applications 
  - We use it to host the node application on it
  - Recives requests from the frontend and process that request (maybe connect to the database or not),then respode to the frontend 
3. AWS S3 Bucket 
 -  It's a service provided by AWS as a storage or to host a static websites 
 -  Here we use it to host our frontend application
  ___


## Circle Ci
- Connected with  github repo that triger any edit to the repo (master branch) ,then it start the workflow that is in  circleci/config.yml  file  