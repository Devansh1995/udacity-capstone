# Serverless Capstone TODO Project

The project aims to create a application to serve as a To-Do task list for students/workers. The user can create a Todo task with a name and a due date. The User can also had an image to identify the task with. The task can be marked complete on completion and can be deleted if needed.

# Functionality of the application

This application will allow creating/removing/updating/fetching TODO items. Each TODO item can optionally have an attachment image. Each user only has access to TODO items that he/she has created.

# Components

Client: React
BackEnd: AWS Lambda, API Gateway, S3 Bucket, DynamoDB

# Run the project

Backend: 

cd backend
npm install
sls deploy -v

Client:

cd client
npm i
npm run start
