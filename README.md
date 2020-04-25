# beertome installation guide

Before we start, we're going to be using the sudo command in the terminal. You'll need to use the password that you used to SSH into your server.

Any time the install stops with a y/n, type y and press enter.

Step 1: Install apache2

sudo apt-get update sudo apt-get install apache2

Step 2: Install mysql database

sudo apt-get install mysql-server

You will be prompted for a password, default username will be root remember your_password

sudo apt-get install phpmyadmin

Step 3: Install PHP

  sudo apt-get install php7.0 php7.0-mysql libapache2-mod-php7.0 php7.0-cli php7.0-cgi php7.0-gd
  sudo service apache2 restart
  
Step 4: FTP
  
  Using Filezilla or a similar FTP service, transer you files into the /var/www/html/ folder.
  
Step 5 PHPMYADMIN

Sign into php myadmin using *your domain name* /phpmyadmin. Sign in using your mysql credentials, then upload your MYSQL file with the brewery data.

Step 6 Success

Your site should now be functioning at *your domain name*.


  
  
