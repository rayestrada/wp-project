# Project Template for Lando + WordPress + Composer Environment

## Requirements
[Lando](https://docs.lando.dev/getting-started/)

## Quick Start
1. Pull a copy of the database to the root of this directory (i.e. database.sql)
2. Pull a copy of wordpress uploaded files to `wp-content/uploads` directory
3. Initialize lando environment
```
lando start
```
4. Set your local wp-config file
```
lando set
```
5. Import your database
```
lando db-import database.sql
```
6. Access your local site at [https://wp-sbademo.lndo.site](https://wp-sbademo.lndo.site)

## Create an administrator to login
```
lando wpadmin
```
Login at [https://wp-sbademo.lndo.site/wp-admin/](https://wp-sbademo.lndo.site/wp-admin/)

user: wpadmin.  
pass: admin