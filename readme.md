## Demo Application 

The purpose of this demo app is to show a front end web server which gives you the ability to upload a picture and store this within a MySQL database and AWS S3 bucket. 

You upload your picture to the site > this is stored in the database and bucket and displayed from the bucket on the site. 

## Goals

- Deploy within AWS 
- Use MySQL RDS 
- Deploy Application to either EC2 or another option? 
- What would be a good failure scenario here? 
- Deploy Veeam Backup for AWS to protect our application  

## Deployment 
For the frontend deployment you can check out [FrontEnd Deployment](/frontend/README.md)

## template.env
template.env can be used to understand the environment variables required this should be completed and added to the /backend folder for the application to work. 