Local WordPress Installation Shell Script

This script is designed to streamline the process of developing with WP locally on your machine.

I have my Apache, PHP, and MySQL set up on my MacBook Pro directly using the instructions available at this site: http://coolestguidesontheplanet.com/get-apache-mysql-php-phpmyadmin-working-osx-10-9-mavericks/

I developed this script to create a MySQL database, download WordPress's latest version, extract files to a specific folder, and create a wp-config file with the correct settings. Hopefully others will find this as helpful as I have.

Please feel free to branch out! I know that there's a lot of modifications and enhancements that can be made to this script. Have at it!

Use as follows. If no parameters are included, Directory name will be 'wordpress' and the path will be the current directory.

wpinstall DirectoryName path/to/parent/directory 

wpinstall help

-Jason
Three 17 Design
