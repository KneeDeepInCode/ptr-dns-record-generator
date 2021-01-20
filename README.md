# ptr-dns-record-generator
A simple, 3-line Python script to help generate PTR reverse DNS records.

## KISS (keep it simple, stupid!)

```python
import ipaddress
ipaddress.ip_address("[IPv4 or IPv6 IP address]").reverse_pointer
```
