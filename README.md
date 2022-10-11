# LAB 16 - Class 401d48

## Project: Cloud Servers

### Author: Junyoung Son

### Problem Domain  

Successfully create a simple server using AWS. Deploy a simple Node.js server to EC2, using Elastic Beanstalk
  Task1:  
    1. Create a new environment, using Elastic Beanstalk from the AWS Control Panel (GUI)
    2. Manually deploy your application to this environment by uploading a .zip file

  Task 2:
    1. Using the same server, create a new environment using Elastic Beanstalk from your terminal
    2. Manually deploy your application to this environment by using eb deploy

### Links and Resources

- [GUI DEPLOY](http://lab16-env.eba-fz3iirss.us-west-2.elasticbeanstalk.com/) (GUI)
- [CLI DEPLOY](http://lab16awscloudserver-env.eba-y8zejjis.us-west-2.elasticbeanstalk.com/) (EB OPEN)
<!-- - [front-end application](http://xyz.com) (when applicable) -->

### Setup

  npm i express
  AWS - Elastic Beanstalk - New Application
  ZIP index & package.json file

#### `.env` requirements (where applicable)

- `PORT` - 3002
- `DATABASE_URL` - URL to the running Postgres instance/db

#### How to initialize/run your application (where applicable)

npm commands:
- `npm start`
- `npm i express`

eb commands:
- eb init
- eb create
- eb deploy
- eb open

#### How to use your library (where applicable)

#### Features / Routes

- Feature One: Details of feature
- GET : `/hello` - specific route to hit

#### Tests

- How do you run tests?
- Any tests of note?
- Describe any tests that you did not complete, skipped, etc

#### ![UML]()
