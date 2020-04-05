### download the jdbc driver for postgresql
in matlab type version -java for java version

https://jdbc.postgresql.org/download.html

jdk 8 - PostgreSQL JDBC 4.2 Driver, 42.2.12

jdk 7 - PostgreSQL JDBC 4.1 Driver, 42.2.12.jre7

jdk 6 -PostgreSQL JDBC 4.0 Driver, 42.2.12.jre6

### set java classpath in matlab
cd (prefdir)
edit javaclasspath.txt

add the location of postgresql jdbc driver
${path to jdbc driver}/postgresql-42.2.12.jar

e.g. C:/opt/libs/postgresql-42.2.12.jar

restart matlab
