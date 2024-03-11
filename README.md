# Prerequisites
# test a commit push with the AWS pipeline setup
# test a commit2 push with AWS pipeline setup. The Quality Gate in SonarCloud is set to fail with a 
# threshold of >20 bugs in the Overall Code. There are currently 24 bugs in the code.
#
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


