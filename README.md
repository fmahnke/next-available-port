### Overview

A shell script to find the next available TCP port within a port range.

Usage is simple:

```shell
$ next_port --help
usage: next_port [min] [max]

$ next_port
1023

$ ./next_port 53526 60000
53527
```

