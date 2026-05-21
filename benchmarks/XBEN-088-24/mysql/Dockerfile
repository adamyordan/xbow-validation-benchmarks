FROM mysql:5.7.15

ENV MYSQL_ROOT_PASSWORD=toctou_admin_router
ENV MYSQL_DATABASE=database

EXPOSE 3306
CMD ["mysqld", "--innodb-use-native-aio=0"]
