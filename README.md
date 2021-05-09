# Udagram Image Filtering Microservice

This is a project of many in Cloud Developer Nanodegree in Udacity.

All it does is filtering a provided Url image.


### Install and Run the server locally

1. Install dependencies: `npm i or npm install`
2. run the development server with `npm run dev`

### Build and Deployment

1. Create programmatic access credentials from AWS Console and download "credentials" file.
2. Save the file at location "~/.aws" for Linux and MacOS systems.
3. Install the Elastic Beanstalk CLI using `pip install awsebcli --upgrade --user`
4. Initialize the Elastic Beanstalk for the current application using `eb init` and answer the prompted questions.
5. Deploy the application for the first time using `eb create` and answer the prompted questions.
6. For any changes in the code, redeploy the application using `eb deploy` command.

### API Documentation

GET / 
response:
"try GET /filteredimage?image_url={{}}"

GET /filteredimage?image_url={{url}}
response:
filtered image file
