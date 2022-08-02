# postgresql
PostgreSQL

# Install php8.0-pgsql package.
Please follow the step by step instructions below to install php8.0-pgsql package:

sudo apt update

sudo apt install php8.0-pgsql

# Uninstall / Remove php8.0-pgsql package.
Please follow the instructions below to uninstall php8.0-pgsql package:

sudo apt remove php8.0-pgsql

sudo apt autoclean && sudo apt autoremove

# Connect postgres via TERMINAL
sudo -i -u postgres

# If Not working then edit php.ini
Edit php.ini, uncomment “extension=php_pgsql.dll”. Check both the php.ini in the PHP folder and Apache folder

Edit environment variables, add PostgreSQL /bin and /lib directories to Path. This solves the issue of php_pgsql.dll not loading due to it not being able to resolve dependencies.

Done. PHP should now be able to communicate with PostgreSQL.





