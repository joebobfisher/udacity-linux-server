# udacity-linux-server

IP Address: 18.222.4.27

URL: http://18.222.4.27/

SSH Port: 2200

## Software Installed

* Apache
    * With mod_wsgi
* PostgreSQL

## Configurations Made

* Added "grader" user
    * And added to `sudoers`
* Generated SSH key pair for "grader" and added public key to `authorized_keys`
* Configured firewall to:
    * Allow TCP connections on port 2200
    * Deny standard SSH (port 22) connections
    * Allow HTTP and NTP connections
* Created "catalog" user as limited PostgreSQL role
* Created mod_wsgi app for my catalog project
* Set Google API key to allow from URL
