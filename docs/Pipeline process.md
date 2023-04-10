# Pipeline process
## Using Circle Ci  we can automate the building and deploying phases for our app
___
### Steps
- Update the code locally ,then push it to the repo
- Circle  Ci will triger that change ,then go through the workflow 
   -  Install Node
   -  Install AWS Elastic Beanstalk
   -  Install AWS CLI
   -  Install Front-End Dependencies
   -  Install API Dependencies
   -  Front-End Build
   -  API Build
   -  **wait for user approval**
   -  Deploy Frontend
   -  Deploy API