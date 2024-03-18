# Prerequisites
# test a commit push with the AWS pipeline setup
# test a commit2 push with AWS pipeline setup. The Quality Gate in SonarCloud is set to fail with a 
# threshold of >20 bugs in the Overall Code. There are currently 24 bugs in the code.
# test3
# test4
# test5 with second SNS target
# test6 fixed code Quality Gate. Code should pass now.
# test7 after reboot
# test8 after adding CodeCommit repo project11 to the project9 IAM user
# test again after removing project11 IAM user and using project9 IAM user for both project9 and 11 after adding ARN of project11 
# test
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


