# ssh-network-up-monitor-using-php-and-mysql
The script uses ssh to check if a device is up or down.
Easy to use.
Devices can be added and deleted from the front end page.

# configuring the mysql database
1. Create a database named dev
2. Create three columns in the db as
    id INT UNIQUE AUTO INCRIMENT,
    name VARCHAR,
    ip VARCHAR

# installation
Upload the index.php file in your server and make sure that the db config in the php file is correct. That's it folks !!
