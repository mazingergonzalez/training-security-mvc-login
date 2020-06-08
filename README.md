## training-security-mvc-login

`https://dzone.com/articles/spring-mvc-example-for-user-registration-and-login-1`

## TOOLS & TECHNOLOGIES
	1. Java 1.8
	2. MySQL DB
	3. Tomcat 8.5

## TOPICS COVERED
	1. XML Bean configuration
	2. Autowiring
	3. Annotation
	4. JdbcTemplate

## STEPS to run Application

### STEP 1:
Start a docker MySQL datbase: 

`docker run --name some-mysql --rm -p 3306:3306 -e MYSQL_ROOT_PASSWORD=pwd -e MYSQL_DATABASE=test -e MYSQL_USER=test -e MYSQL_PASSWORD=test -d mysql:5.7.30`

Create a mysql database & table using sql script: 

`/src/main/resources/jbr/sql/ddl.sql`


### STEP 2:
Download this project from Git and import as Maven Project in Eclipse/STS.

### STEP 3:
Download tomcat 8.5 and configure in eclipse.

### STEP 4: Run Junit Testcase
Run the junit testcase to ensure your application able to communicate to MySQL DB properly.

### STEP 4: Run the application using tomcat server
And access to the web:

`http://localhost:8080/springmvc-user-reg-login/home.jsp`