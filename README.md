# OSINT tools to search for personal and geo data

I am going to build this list for my own needs. Feel free to submit PR with new services/tools.

How to read this list. Each section (header) represent input data i.e. data you have already. Each subsection (list item) represents type of data you can get. Each URL represents the page to enter input data.

### Email

- phone-number:
  - https://twitter.com/account/begin_password_reset
  - https://www.facebook.com/login/identify/
  - https://www.paypal.com/authflow/password-recovery/
  - https://vk.com/restore
  - https://iforgot.apple.com/password/verify/appleid
  - https://account.live.com/ResetPassword.aspx
  - https://signin.ebay.com/ws/eBayISAPI.dll?SignIn "Continue", then "Need help signing in?"
- linkedin-account:
  - https://outlook.live.com/ create new contact then go to "linkedin" tab

### Phone Number

- email:
  - https://twitter.com/account/begin_password_reset
  - https://www.facebook.com/login/identify/
  - https://account.live.com/ResetPassword.aspx
  - https://yoomoney.ru/yooid/signin/step/login
- username:
  - https://vk.com/restore
- telegram-account:
  - Telegram -> Contacts -> Add contact by phone 

### Name and Birthday
- email:
  - https://account.samsung.com/accounts/v1/SAMSUNGCA/findId

### Username

- ???:
  - https://www.instagram.com/accounts/password/reset/
  - https://signin.ebay.com/ws/eBayISAPI.dll?SignIn "Continue", then "Need help signing in?"

### Facebook ID

- my.mail.ru-account:
  - https://my.mail.ru/fb/FACEBOOK-URL-ID

### Vkontakte ID

- my.mail.ru-account:
  - https://my.mail.ru/vk/VKONTAKTE-ID
- vk-account-extra-data:
  - https://vk.com/foaf.php?id=VKONTAKTE-ID (date of account created, date of last login, optional bio and social links)
- vk-account-history:
  - https://t.me/vk2017bot
  - https://t.me/VKHistoryRobot
  - https://bigbookname.com/user/zzz-VKONTAKTE-ID

### Gmail email

- my.mail.ru-account:
  - https://my.mail.ru/gmail/GMAIL-USERNAME (without "@gmail.com")

### Skype Username
- phone-number,email:
  - https://account.live.com/ResetPassword.aspx

### Photo

- vk-account,odnoklassniki-account,clubhouse-account,tiktok-account:
  - https://search4faces.com/
- vk-account:
  - https://findclone.ru
- web-document:
  - https://yandex.ru/images/
  - https://images.google.com/

### Telegram ID

- telegram-groups,username,username-history:
  - https://t.me/tgscanrobot
- registration-date:
  - https://t.me/regdatebot

### Location
- streetview:
  - https://www.google.com/maps
  - https://yandex.ru/maps
  - https://www.bing.com/maps
- social-network-photos:
  - https://fotomapia.ru/
- building-details,building-photo,building-historical-photo:
  - https://photobuildings.com 
  - https://pastvu.com 
  - https://www.citywalls.ru 

### Overpass API Query

- results-on-map,results-as-data:
  - https://overpass-turbo.eu/
  - https://maps.mail.ru/osm/tools/overpass/

### Photo of Location

- location:
  - https://labs.tib.eu/geoestimation/
