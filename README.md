# mysql-vagrant

mysql-vagrant is a quick way to run mysql locally for development without an ssh tunnel

### Start server

     $ vagrant up

### Connect to mysql:

- host: 33.33.33.33
- port: (from your host) 12233, or 3306 on the same guest private network
- username: root
- password: root

And because I never like plugging in root into my app, there is an app user that has full privileges to the database app
- database: app
- username: app
- password: app

### From sequel pro

<img src="sequel-pro.png"/>

### Warning

For development use only, do not use in production.
Also, make sure your mysql port (3306) is not open on your computer for a local network or in general.

### License

MIT
