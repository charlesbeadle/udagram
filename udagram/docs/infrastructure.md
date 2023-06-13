## Infrastructure

This application consists of a frontend and a backend, both hosted on the Amazon Web Services (AWS) platform.

The frontend is an Angular application deployed on an Amazon S3 bucket.

The backend is a Node.js application hosted within an Elastic Beanstalk environment. Within the Elastic Beanstalk environment, an Amazon EC2 instance is utilized to run the Node.js application.

An RDS instance is used in combination with an additional S3 bucket for storing user data and images.
