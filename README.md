# gethosts
A program to query the configured DNS server for FQDN of a range of hosts within a given network.

## example output
```
$ ./gethosts 1.1.1.1/28
1.1.1.0:
1.1.1.1: one.one.one.one
1.1.1.2:
1.1.1.3:
1.1.1.4:
1.1.1.5:
1.1.1.6:
1.1.1.7:
1.1.1.8:
1.1.1.9:
1.1.1.10:
1.1.1.11:
1.1.1.12:
1.1.1.13:
1.1.1.14:
1.1.1.15:
$
$ ./gethosts 8.8.8.8/30
8.8.8.8: dns.google
8.8.8.9:
8.8.8.10:
8.8.8.11:
```

## Requirement
python version 3
