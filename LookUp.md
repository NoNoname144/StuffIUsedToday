# Welcome to my LookUp File

This file just exists to have a place where all the things I learned or used today will be stored so I don't forget them.

## Linux

### Adding a User

- useradd new_user: <br>
    With ```useradd new_user``` the user will be created without anything. To login through ssh a password needs to be assigned with ```passwd new_user```. Most things need to be done manually or have to be added with a flag.

- adduser new_user: <br>
    With ```adduser new_user``` a new user will be created an a little Perl script will run and will __create a group for the user and add the user in it__, __create a home directory__, copy skeleton files (?), __will require you to set a password__ and ask for some optional information __if no flags were set__.

## FTP (requires vsftpd installed)

- Setup: (Wip)

##
