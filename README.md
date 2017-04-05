# how to use

$ vagrant box add centos65 ../centos65-x86_64-20140116.box
$ vagrant init centos65


安装完以后
$ vagrant up
$ vagrant ssh
$ sudo systemctl start nginx
$ sudo systemctl start php-fpm
$ sudo systemctl start mysqld