# ssh-network-up-monitor-using-php-and-mysql
The script uses ssh to check if a device is up or down.
Easy to use.
Devices can be added and deleted from the front end page.

# how it works
It uses a mysql db to fetch the host name and ip address. Then it tries connecting to the host using ssh. If it connects it shows that the host is up and if not then the host is down.

# configuring the mysql database
1. Create a database named dev
2. Create a table named host and then create three columns in the host table as
    id INT UNIQUE AUTO INCRIMENT,
    name VARCHAR,
    ip VARCHAR

# installation
Upload the index.php file in your server and make sure that the db config in the php file is correct. That's it folks !!
