
# This README is for project 9

## Introduction:

This is a special project.  

Project9: push from VSCode CodeCommit OR push from VSCode to VPS gitlab pipelline. The first option uses CodeCommit as source for CodeBuilds whereas second option uses VPS gitlab repo as source for CodeBuilds.
Maven is used to build and CodeArtifact used to fetch dependencies from maven repo. pom.xml settings.xml
The CodeBuilds are integrated into discrete CodePipelines for each option. S3 bucket stage is last stage.

Project9: push from VSCode CodeCommit OR push from VSCode to VPS gitlab pipelline. Option1:uses CodeCommit as source for CodeBuilds Option2:uses VPS gitlab repo as source for CodeBuilds.Maven is used to build.CodeArtifact used to fetch dependencies from maven repo.CodeBuilds are integrated into discrete stages for each CodePipeline type. S3 bucket stage is last stage.

This uses CodeCommit, CodeArtifact, CodeBuild, and Code Pipeline to build, sonar cloud test and analyze, then rebuild the artifact .war if passes and deploy to S3 bucket. Maven is used to build and CodeArtifact used to fetch dependencies from maven repo. pom.xml settings.xml

The CodePipepline has to be reconfigured as a new pipeline to support the gitlab VPS as source rather than the CodeCommit as source because the CodeBuilds are unique for each option.

The project has 2 modes of operation, and push from VSCode on mac to CodeCommit on AWS to kick off the CodePipeline OR a push from VSCode to gitlab repo which then relays to the AWS CodePipeline

The gitlab self managed instance is on the private DevOps VPS linode ecosystem and requires an AWS Connection configuration from AWS to the gitlab docker instance.
The traefik reverse proxy on the linode VPS that hosts the gitlab self managed docker instance has to be configured to whitelist the AWS source ip address blocks for us-east-1 where my developer tools CodePipeline and its constituents are configured. Otherewise the AWS connection to gitlab VPS instance fails.

NOTE: the relevant branch here is ci-aws.



# test8 after adding CodeCommit repo project11 to the project9 IAM user
# test again after removing project11 IAM user and using project9 IAM user for both project9 and 11 after adding ARN of project11 
# test
# test



# Prerequisites
- JDK 11 
- Maven 3 
- MySQL 8

# Technologies 
- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- Tomcat
- MySQL
- Memcached
- Rabbitmq
- ElasticSearch
# Database
Here,we used Mysql DB 
sql dump file:
- /src/main/resources/db_backup.sql
- db_backup.sql file is a mysql dump file.we have to import this dump to mysql db server
- > mysql -u <user_name> -p accounts < db_backup.sql


