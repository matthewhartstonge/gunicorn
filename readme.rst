======================
Gunicorn init.d
======================

*********************************************************************************
This is a simple script to allow normal init.d servicing of gunicorn under Debian
*********************************************************************************

1) To make this work copy 'gunicorn' into /etc/init.d/
2) Edit the settings to point to your gunicorn config.py, the django directory you are using, and the project wsgi name
3) Then run $chmod 775 gunicorn 
4) To enable script to run on startup run $update-rc.d gunicorn defaults