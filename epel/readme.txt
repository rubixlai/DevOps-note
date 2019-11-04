

###CentOS/RedHat 6
https://dl.fedoraproject.org/pub/epel/epel-release-latest-6.noarch.rpm


###CentOS/RedHat 7

https://dl.fedoraproject.org/pub/epel/epel-release-latest-7.noarch.rpm


###CentOS/Redhat 8 
https://dl.fedoraproject.org/pub/epel/epel-release-latest-8.noarch.rpm

###wildcard
rpm -Uvh https://dl.fedoraproject.org/pub/epel/epel-release-latest-$(awk -F. '{print $1}' /etc/redhat-release| grep -o '[0-9]').noarch.rpm 
