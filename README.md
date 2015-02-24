MySQL2Redshift
====

## Overview
MySQL2Redshift is for converting MySQL data into Amazon Redshift.

## Requirement

 * AWS-cli
 * mysql-client
 * postgresql-client

## Usage

```
$ ./m2r
```

## Install

```
$ git checkout git@github.com:nobu666/mysql2redshift.git
$ cd mysql2redshift
$ edit m2r
```

You need to edit some parameters
 * mysql_server
 * mysql_user
 * mysql_password
 * mysql_port
 * logfile
 * s3base
 * rsworkdb
 * rsdb
 * rsurl
 * rsport
 * rsuser
 * s3accesskey
 * s3secretkey
 * sensu_api_endpoint
 * dump_database

## Licence

This software is released under the MIT License, see LICENSE.txt.

## Author

[nobu666](https://github.com/nobu666)
