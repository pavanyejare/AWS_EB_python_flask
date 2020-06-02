# AWS_EB_python_flask
Setup to application on AWS elastic beanstalk use the following setps

1. install aws cli and configure it 
2. install awseb cli to setup the code using cicd or post git commit
3. confiure .ebextensions/  and .elasticbeanstalk/ as per  requirement 
4. run following command to deploy application 
    eb init 
    eb create APP_NAME
    eb deploy
