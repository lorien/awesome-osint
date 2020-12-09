# Awesome OSINT

I am going to build this list for my own needs. Feel free to submit PR with new services/tools.

## Table of Contents

- [Web Tools](#web-tools)
- [Software Tools](#software-tools)

## Web Tools

### Reverse IP

- https://viewdns.info/reverseip/
- bing: "ip:8.8.8.8"
- http://atsameip.intercode.ca/
- https://dnslytics.com/reverse-ip

### Domain IP History

- https://viewdns.info/iphistory/
- https://threatcrowd.org/ - see "dns resolutions" in results
- https://cyber-hub.pw/domain_history.php

### Reverse NS

- https://viewdns.info/reversens/
- https://hackertarget.com/find-shared-dns-servers/
- https://dnslytics.com/reverse-ns

### Cloudflare Deanon

See also "Domain IP History" tools

- http://www.crimeflare.org:82/cfs.html

### WHOIS History

- http://whoishistory.ru/ - history for .RU, .SU, .РФ domains

### Subdomains

- google: "site:*.domain.com"
- https://dnsdumpster.com/
- https://crt.sh/ - historical data of SSL cert, see Common Name data
- https://cyber-hub.pw/domain_resolver.php

### Reverse Adsense

- https://dnslytics.com/reverse-adsense

### Reverse Analytics

- https://dnslytics.com/reverse-analytics
- https://analyzeid.com/id/codeby.net

### Zone Transfer

- https://hackertarget.com/zone-transfer/

### Google Dorks

- https://www.exploit-db.com/google-hacking-database

### Hash Cracking

- https://crackstation.net/

## Software Tools

### Subdomains

- https://github.com/guelfoweb/knock - brute-forcing, wildcard detection
- https://github.com/aboul3la/Sublist3r - search engines, dnsdumpster, brute-forcing
- https://github.com/OWASP/Amass - `amass enum` command

### Website Directories

- https://github.com/Nekmo/dirhunt
- https://github.com/maurosoria/dirsearch

### Image Processsing

- https://github.com/beurtschipper/Depix - recovers text blured with linear box filter

### Cloudflare Deanon

- https://github.com/m0rtem/CloudFail - dnsdumpster, crimeflare, brute-force
