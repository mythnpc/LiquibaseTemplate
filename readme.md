LiquibaseConstruct

The purpose of this repo is to provide a template\scaffold for future liquibase usage.


Usage:

SQL Server:
liquibase --driver=com.microsoft.sqlserver.jdbc.SQLServerDriver  --changeLogFile="_master.xml"  --url="jdbc:sqlserver://localhost:1433;"  --username=sa --password=Password update