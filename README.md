>forked from Yenthe666/InstallScript

## Installation Script for Odoo
 - Install Odoo 9.0 on Ubuntu 14.04
 - Install Odoo 9.0 on Debian (see note below)

### NOTE for Debian
In order to use this script on Debian wheezy or jessie, it's necessary to change [wkhtml2pdf download links in the installation script](https://github.com/tvibliani/InstallScript/blob/8322829463db26f91cf7443a9144f08849821fbc/odoo_install.sh#L27-L34) accordingly, using one of following:
 - For Debian Wheezy:
```Bash
WKHTMLTOX_X64=http://download.gna.org/wkhtmltopdf/0.12/0.12.1/wkhtmltox-0.12.1_linux-wheezy-amd64.deb
WKHTMLTOX_X32=http://download.gna.org/wkhtmltopdf/0.12/0.12.1/wkhtmltox-0.12.1_linux-wheezy-i386.deb
``` 
 - For Debian Jessie choose from [versions by Odoo](http://nightly.odoo.com/extra/) OR use one from [official repo](http://wkhtmltopdf.org/downloads.html):
```Bash
WKHTMLTOX_X64=http://download.gna.org/wkhtmltopdf/0.12/0.12.2.1/wkhtmltox-0.12.2.1_linux-jessie-amd64.deb
WKHTMLTOX_X32=http://download.gna.org/wkhtmltopdf/0.12/0.12.2.1/wkhtmltox-0.12.2.1_linux-jessie-i386.deb 
```

With wkhtml2pdf links adapted properly, installation script is supposed to work on Debian distributions.      

