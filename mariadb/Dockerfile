FROM mariadb:10.3.2

COPY ./mariadb/conf/* /etc/mysql/conf.d/

# Make the conf files not writeable so mysql will read them
RUN chmod a-w /etc/mysql/conf.d/*
