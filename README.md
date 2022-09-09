Ansible-Wordpress Role
=========

This role install and configure Wordpress CMS to your server.

Requirements
------------

Installed and configured Linux server with the following installed soft:
- Nginx
- MySQL
- PHP
- Ansible 2.7 or higher

Role Variables
--------------
 - (mysql_version) - Version of MySQL to be installed thought the playing this Ansible role   ackage_name - Since G 
 - db_user # Name of Wordpress database owner-user
 - db_name # Name of database for Wordpress
 - db_password # Password of database
 - db_host # Database host
 - db_user_priv # Privileges that you will grant to your database user
 - nginx_version # Nginx (Web-server) version to be installed thought the playing this Ansible role
 - user # Name of remote user that you want to create
 - group # Group for created remote user
 - your_domain # Your site ip-address or domain name
 - php-fpm_version # Version of PHP that you want to install
 - wordpress_version # Wordress release version
 
Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
=======
