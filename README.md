# ace
### Asterisk Configuration Embellish

A simple PHP script to colour asterisk configuration files.

## Install
    # wget -O ace https://github.com/valenciaj/ace/raw/master/ace
    # chmod o+x ace
    # mv ace /usr/local/sbin

## How to use
Use on single file

    # ace /etc/asterisk/sip.conf

Or use on multiple files

    # ace /etc/asterisk/*

## TODO

* Colour include directives
* Handle include directives
* Colour multiline comments
