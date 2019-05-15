PHP version Manage Script
===========

Bash Script to allow you to change PHP version
*Only tested in Ubuntu and using Apache. Nginx, MacOS and Windows is not supported by this script*

## Installation ##

1. Download the script
2. Apply permission to execute:

```
$ chmod +x /path/to/changephpversion
```

### For Global Shortcut ###

```bash
$ cd /usr/local/bin
$ wget -O changephpversion https://raw.githubusercontent.com/samuel27m/changephpversion/master/changephpversion
$ chmod +x changephpversion
```

## Usage ##

Basic command line syntax:

```bash
$ sudo sh /path/to/changephpversion [php_version]
```

With script installed on /usr/local/bin

```bash
$ sudo changephpversion [php_version]
```

### Examples ###

to change PHP version:

```bash
$ sudo changephpversion 5.6
```
