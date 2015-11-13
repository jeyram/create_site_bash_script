## BASH Script in order to create vhost, mysql  db, and mysql user

I developed this script in order to create apache vhost, mysql  db, and mysql user of a site via one command

##Install
 - Copy `create_site` file to `/usr/local/bin/create_site` and give execution permission by typing `chmod +x /usr/local/bin/create_site`
 - Copy `template` file to `/etc/sites-available/template` and write your MySQL root user password to last line at the file.

##Usage
    create_site [site name] [mysql password]

## Contributing

Thank you for considering contributing to the code! You can get in touch with the author by this link: http://bariscimen.com/

### License

This program is free software; you can redistribute it and/or modify it under the terms of the GNU General Public License(GPL v3.) as published by the Free Software Foundation.