# cloudstack-dns-sslipio
A slightly modified sslip.io pipe backend for Powerdns to serve my Cloudstack needs.
It can probably be modified better, show me.

Requires grepcidr package installed and the list of your valid IP v4/6 CIDRs in /etc/pdns/ips.txt

What it does? This:

```
host 1-2-3-4.sslip.io
1-2-3-4.sslip.io has address 1.2.3.4
```
