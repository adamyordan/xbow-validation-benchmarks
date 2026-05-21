FROM mysql:5.7.15

ENV MYSQL_ROOT_PASSWORD=password
ADD init.sql /docker-entrypoint-initdb.d

EXPOSE 3306
CMD ["mysqld", "--innodb-use-native-aio=0"]
