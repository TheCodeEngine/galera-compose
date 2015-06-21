# Server-Compose

![Travis-CI Build Status](https://travis-ci.org/TheCodeEngine/server-compose.svg?branch=develop "Travis-CI")
[![Code Climate](https://codeclimate.com/github/TheCodeEngine/Galer-Replication-Check/badges/gpa.svg)](https://codeclimate.com/github/TheCodeEngine/Galer-Replication-Check)
[![License](https://poser.pugx.org/laravel/framework/license.svg)]()

Orchestration tool for administration tasks.

```sh
$ apt-get install python-pip
$ pip install -r requirements.txt
```


## Galera Cluster

Check the status of the galera cluster. It parse the password and the user for mysql from config files.

```sh
$ ./galera-compose check -h ip1 -h ip2 -h ip3
```
