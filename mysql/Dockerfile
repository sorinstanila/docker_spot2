FROM mysql:latest
# disable only full group by
RUN yes | echo 'sql_mode = "STRICT_TRANS_TABLES,ERROR_FOR_DIVISION_BY_ZERO,NO_AUTO_CREATE_USER,NO_ENGINE_SUBSTITUTION"' >> /etc/mysql/mysql.conf.d/mysqld.cnf
