# FreePBX-Reverse-Shell-Module
FreePBX Reverse Shell Module
A module designed to get a reverse shell on freePBX when uploaded and installed
The reverse-shell code was taken from https://github.com/pentestmonkey/php-reverse-shell
To get a reverse shell first edit the install.php with listening ip address and port. Then compress the folder via tar and gz:
tar -cvzf shell.tar.gz shell
Then upload the modulue via module admin and install it
