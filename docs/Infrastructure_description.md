# Infrastructure

## Project structure on AWS
Udagram project AWS resources are:
1.  An S3 bucket
2.  A PostgreSQL database
3.  An Elastic Beanstalk environment

Here's how it works
![enter image description here](https://github.com/Mahmoud2B/udagram/blob/master/Screenshots/Screenshot%202022-12-13%20125150.png?raw=true)

### AWS RDS (PostgreSQL)
A PostgreSQL database to store our app data with the following properities

![enter image description here](https://github.com/Mahmoud2B/udagram/blob/master/Screenshots/Screenshot%202022-12-12%20203214.png?raw=true)

### AWS Elasitc Beanstalk
The API project is hosted on AWS EB env you can access it [here](http://udagram-api-final-dev.us-east-1.elasticbeanstalk.com/api/v0/feed/)
the API is working and successfully connected to the RDS.

![enter image description here](https://github.com/Mahmoud2B/udagram/blob/master/Screenshots/Screenshot%202022-12-12%20203058.png?raw=true)

### AWS S3 Bucket

This bucket is to host the frontend project and it can be found [here](http://udacity-circle-ci.s3-website-us-west-2.amazonaws.com/)

![enter image description here](https://github.com/Mahmoud2B/udagram/blob/master/Screenshots/Screenshot%202022-12-12%20203121.png?raw=true)