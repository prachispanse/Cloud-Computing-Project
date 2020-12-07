This cloud application uses the Expressframework and Bootstrap to build a simple, scalable customer signup form that is deployed to AWS Elastic Beanstalk. The application stores data in Amazon DynamoDB and publishes notifications to the admin through Amazon Simple Notification Service (SNS) when a customer registers for events by filling the form.

The ebextensions folder contains SNS(Simple Notification Sysytem) and DynamoDB configuration files.

The static folder contains the bootstap folder and jquery folder for GoodReads website.

The views folder has the index.ejs file which is the source code for the website.

The app.js takes care of the website's user interface.

The nodejs-tutorial.zip is the folder that has the entire application which was used to deploy on Elastic Beanstalk environment.

The iam_policy.json, npm-shrinkwrap.json and package.json contains all the necessary dependency packages to support node.js application.
