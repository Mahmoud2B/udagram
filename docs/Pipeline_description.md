# Pipeline

We are using CircleCI as a pipeline service for our application. The configuration can be found here [config.yml](https://raw.githubusercontent.com/Mahmoud2B/udagram/master/.circleci/config.yml).

CircleCI is connected to the project github repo (listening on branch master), once we push something to that branch CI/CD processes starts automatically.

### How it works

First we define our orbs

```
node:  circleci/node@5.0.2

eb:  circleci/aws-elastic-beanstalk@2.0.1

aws-cli:  circleci/aws-cli@3.1.1
```
Then here are the jobs/workflow:

![enter image description here](https://github.com/Mahmoud2B/udagram/blob/master/Screenshots/Circle%20CI_CD-Map%201.png?raw=true)

