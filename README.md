# infra

- nginx
- php7.4
- mysql 5.7.22

  libssl-dev \
  pkg-config \

RUN pecl install mongodb \
 && echo "extension=mongodb.so" > $PHP_INI_DIR/conf.d/mongo.ini
