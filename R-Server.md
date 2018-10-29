Install R-Server on VM Ware (Debian9)
```
$ apt-get update
$ apt-get install sudo
$ apt-get install gdebi-core
$ wget https://download2.rstudio.org/rstudio-server-stretch-1.1.453-amd64.deb
$ gdebi rstudio-server-stretch-1.1.453-amd64.deb
$ sudo apt-get install libdbd-mysql libmysqlclient-dev
```
