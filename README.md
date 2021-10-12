# ansible-ovms-server

# password for the mysql database root user
mysql_root_password: somesecureRANDOMpassword(or even better use ansible vault)

# password for the ovms database user
ovmsdbuser_db_pw: someDIFFERENTsecureRANDOMpassword(or even better use ansible vault)

# configuration for letsencrypt certbot (will use the hostname of the linux machine)
# if you don't want to use letsencrypt just leave this out of your playbook
letsencrypt:
  email: example@example.exam


note: for the mysql tasks to work you need python3-pymysql on the ansible machine
