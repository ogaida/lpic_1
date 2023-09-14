---
title: LPIC 1 - Lesson 5
---

# {{ page.title }}

## it is about 103.2 Process text streams using filters

Send text files and output streams through text utility filters to modify the output using standard UNIX commands found in the GNU textutils package.

The following is a partial list of the used files, terms and utilities:

-    wc
-    cat
-    cut
-    head
-    less
-    nl - extend your textfile with linenumbers [examples on geeksforgeeks](https://www.geeksforgeeks.org/nl-command-in-linux-with-examples/)
    - `seq 3|paste -s -d ';'`
-    od - octal dump of any file https://www.geeksforgeeks.org/od-command-linux-example/
-    paste is used to join textfiles horizontally [examples on geeksforgeeks](https://www.geeksforgeeks.org/paste-command-in-linux-with-examples/)
    - `cat hostnames |paste -s -d '|'`
-    tr
    - `echo '3-2-1'|tr - /`
-    sed, see https://www.gnu.org/software/sed/manual/sed.html
-    sort
-    split
-    tail
-    uniq
-    xzcat
-    zcat
-    bzcat
-    sha256sum
-    sha512sum
-    md5sum

## exercises

- use `paste` command to join multiple lines from stdin to one outputline with the delimiter `+`
- grep your username from the file `/var/log/auth.log` but with the correct linenumber at the beginning of each line
- calculate the sha1-checksum of the file `/etc/profile`
- search case insensitive in all `/var/log/syslog.*.gz` files for the string error
- sed: replace the ip 1.2.3.4 with 5.6.7.8 in all files with the extension `.cfg` in the subfolder sub1
- uniq: use the command last to see who made a login. filter the username with `|cut -d ' ' -f1`. Use sort and uniq to create a summary with logins per account
- grep all logfiles with the extension xz within /var/log for the string shutdown
- grep all logfiles with the extension gz within /var/log for the string shutdown
- grep all logfiles with the extension bz2 within /var/log for the string shutdown

[HOME](https://ogaida.github.io/lpic_1/README.html)