# [myip](https://godoc.org/github.com/clarketm/myip)

Command line utility for displaying public and private IP addresses.

```shell
NAME:
    myip – list IP addresses.

SYNOPSIS:
    myip [ opts... ]

OPTIONS:
    -h, --help          # Show usage.
    -a, --all           # Same as -e, -p (default).
    -e, --ethernet      # Print (IPv4/IPv6) ethernet IP address.
    -p, --public        # Print (IPv4/IPv6) public IP address.
    -v, --version       # Show version number.

EXAMPLES:
    myip -a             # list all IP addresses.
```
