# gunicorn-config:

***Gunicorn(green unicorn)*** is an application server that is used to server python applications. It seats in between the
***Web server*** and the ***django apllication***.

This Repository illustrates sample configuration for the gunicorn WSGI server.

Gunicon configuration files are convectionally kept in ***/etc/*** folder

the extact location of config files can be:`/etc/systemd/system/`

The two crucial gunicorn configuration files are:
1. gunicorn_service.service
   
    This file contains gunicorn commands

2. gunicorn.config.py
