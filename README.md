# mogodb
installation and commands

```bash
vi /etc/yum.repos.d/mongodb-org-4.2.repo

[mongodb-org-4.2]
name=MongoDB Repository
baseurl=https://repo.mongodb.org/yum/redhat/$releasever/mongodb-org/4.2/x86_64/
gpgcheck=1
enabled=1
gpgkey=https://www.mongodb.org/static/pgp/server-4.2.asc

yum update

install:
sudo yum install -y mongodb-org

startdb:
sudo service mongod start

use:
mongo

run start:
sudo chkconfig mongod on
```
