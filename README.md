# linux server configurations for [Catalog project](https://github.com/beshoy-samy/catalog-web-nd)

## Server Details
- IP address: 35.188.85.58
- SSH Port: 2200
- Username: grader
- URL: http://35.188.85.58/

## Installed softwares
- Apache2
- Postgresql
- Sqlalchemy
- Git
- Flask
- Libapache2-mod-wsgi
- Requests
- Httplib2
- Oauth2client

## Changes made:
- Update all currently installed packages
sudo apt-get update
sudo apt-get upgrade

- Change the SSH port from 22 to 2200
1. Use `sudo vim /etc/ssh/sshd_config` and then change Port 22 to Port 2200 , save & quit.
2. Reload SSH using `sudo service ssh restart`

- Configure the Uncomplicated Firewall (UFW)

## Sources
- [changing ssh port](http://ubuntuforums.org/showthread.php?t=1591681)
- [postgresql on ubunto](https://www.digitalocean.com/community/tutorials/how-to-secure-postgresql-on-an-ubuntu-vps)
- [flask deployment](https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps)
- [linux server configurations](https://discussions.udacity.com/c/nd004-p7-linux-based-server-configuration)
