#!/bin/bash yum -y install httpd systemctl enable httpd systemctl start httpd echo '
Hello From Pallavi!' > /var/www/html/index.html
