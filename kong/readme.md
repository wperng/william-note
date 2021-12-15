# Kong

## Install Postgresql database
1. [Install Postgres Database](https://www.digitalocean.com/community/tutorials/how-to-install-postgresql-on-ubuntu-20-04-quickstart)
2. [Update password for user 'postgres'](https://chartio.com/resources/tutorials/how-to-set-the-default-user-password-in-postgresql/#:~:text=For%20most%20systems%2C%20the%20default,connect%20as%20the%20postgres%20user.&text=If%20you%20successfully%20connected%20and,the%20Changing%20the%20Password%20section.)
3. [Install PgAdmin](https://www.pgadmin.org/download/pgadmin-4-apt/)
4. [UI](https://github.com/pocketdigi/kong-admin-ui)
5. [Ingress](https://dzone.com/articles/kubernetes-full-stack-example-with-kong-ingress-co)

## start/stop Kong
1. start kong: kong start -c /etc/kong/kong.conf
2. stop kong: kong stop 
3. restart kong: kong restart -c /etc/kong/kong.conf
