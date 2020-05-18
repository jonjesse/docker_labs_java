FROM mysql:5.7

# Copy the database initialize script: 
# Contents of /docker-entrypoint-initdb.d are run on mysqld startup
COPY  docker-entrypoint-initdb.d/ /docker-entrypoint-initdb.d/

# Default values for passwords and database name. Can be overridden on docker run
# ENV MYSQL_ROOT_PASSWORD=my-secret-pw # Not defaulted for security reasons!
ENV MYSQL_DATABASE=dockercon2035
#ENV MYSQL_DATABASE=mysql
ENV MYSQL_USER=gordon
#ENV MYSQL_USER=root
#ENV MYSQL_ROOT_PASSWORD=password
ENV MYSQL_PASSWORD=password

