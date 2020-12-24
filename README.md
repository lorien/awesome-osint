# Awesome OSINT

I am going to build this list for my own needs. Feel free to submit PR with new services/tools.

## Table of Contents

- [Web Tools](#web-tools)
- [Software Tools](#software-tools)
- [Datasets](#datasets)

## Web Tools

### Email to Phone Number

- https://twitter.com/account/begin_password_reset (silent, alert sometime)
- https://www.facebook.com/login/identify/ (silent)
- https://www.paypal.com/authflow/password-recovery/ (silent)
- https://vk.com/restore (silent)
- https://iforgot.apple.com/password/verify/appleid (silent, alert sometime)
- https://account.live.com/ResetPassword.aspx (silent)
- https://signin.ebay.com/ws/eBayISAPI.dll?SignIn "Continue", then "Need help signing in?" (alert sometime)

### Phone Number To Email

- https://twitter.com/account/begin_password_reset (silent)
- https://www.facebook.com/login/identify/ (silent, alert sometim)
- https://account.live.com/ResetPassword.aspx (silent)

### Email by Personal Data

- https://account.samsung.com/accounts/v1/SAMSUNGCA/findId (silent, By First Name, Last Name and Birtday)
- https://www.instagram.com/accounts/password/reset/ (alert, by username)
- https://account.live.com/ResetPassword.aspx (silent, by username)

### Phone Number by Personal Data

- https://account.live.com/ResetPassword.aspx (silent, by username)
- https://signin.ebay.com/ws/eBayISAPI.dll?SignIn "Continue", then "Need help signing in?" (alert sometime, by username)

### Phone Number to Username

- https://vk.com/restore (silent)
- Telegram -> Contacts -> Add contact by phone (silent)

### Email to Linkedin

- https://outlook.live.com/ create new contact then go to "linkedin" tab (silent)

### Phone Number to Telegram

- In telegram client, Contacts -> Add contact

### Facebook URL Id to my.mail.ru

- https://my.mail.ru/fb/FACEBOOK-URL-ID


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
- https://domainwat.ch

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

### Person Photo Search

- https://pimeyes.com/
- https://findclone.ru/
- https://search4faces.com/
- https://yandex.ru/images/
- https://www.google.com/imghp?tbm=isch

### Image Search

- https://tineye.com/

### Removing Background from Photo

- https://remove.bg

## Software Tools

### Subdomains

- https://github.com/guelfoweb/knock - brute-forcing, wildcard detection
- https://github.com/aboul3la/Sublist3r - search engines, dnsdumpster, brute-forcing
- https://github.com/OWASP/Amass - `amass enum` command

### Image Processsing

- https://github.com/beurtschipper/Depix - recovers text blured with linear box filter

### Cloudflare Deanon

- https://github.com/m0rtem/CloudFail - dnsdumpster, crimeflare, brute-force

### Web Fuzzing

- https://github.com/ffuf/ffuf

## Datasets

### Lists for fuzzing/bruteforce

- https://github.com/fuzzdb-project/fuzzdb
- https://github.com/danielmiessler/SecLists
- https://github.com/FlameOfIgnis/Pwdb-Public
