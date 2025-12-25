
***🔎 DorkNexus — A to Z Dorks Collection for Cybersecurity Researchers***

A curated and categorized list of *200+ Google Dorks* useful for OSINT, Reconnaissance, Web Vulnerability Discovery, and Security Learning.

> ⚠️ *Important:* These queries are for educational and ethical research purposes only..  
> Unauthorized access, exploitation, ya private data ko expose karna `illegal` hai.
 ‎
 ‎‎
<div align="center">
    <a href="https://www.instagram.com/karndeepbaror/"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=red&color=black" alt="Instagram Badge"/></a>
    <a href="https://youtube.com/@cryptarea"><img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=red&color=black" alt="YouTube Badge"/></a>
    <a href="https://t.me/CryptonicArea"><img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=red&color=black" alt="Telegram Badge"/></a>
</div>


 ‎
         
****📖 What are Google Dorks?****

`Google Dorks` are advanced Google search queries that use operators to filter and uncover information that’s not normally visible — such as exposed files, `admin panels`, `sensitive data leaks`, `error pages`, and more.



****📂 Categories:***"
 

•  🔐 Credentials & Sensitive Information  
•  📄 Exposed Files & Documents  
•  🛠️ Admin & Login Pages  
•  📡 Indexed Servers & Directories  
•  ⚠️ Error Messages & Debug Info  
•  🧪 Vulnerability‑Specific Searches  
•  🕵️ OSINT: People, Emails, Usernames  
•  📷 Cameras / IoT Devices  
•  📊 Tech & Service Fingerprinting  
•  🌐 Miscellaneous
 ‎ ‎ ‎ ‎

 
 ‎‎‎ ‎
***🔐 1. Credentials & Sensitive Information:***

 
```
intitle:"index of" password
intext:"password" filetype:txt
intext:"login" "password"
"passwd" "shadow" "etc"
filetype:log "user_pass"
intext:"username" "password"
intitle:"Login" intext:"password"
inurl:wp‑config.php
inurl:".env" "DB_PASSWORD"
filetype:env DB_PASSWORD
intext:"AWS_SECRET_ACCESS_KEY"
intext:"aws_access_key_id"
"intext:ACCESS_TOKEN" "Bearer"
filetype:txt pass OR pwd
filetype:xls username password
filetype:csv password
intext:"SMTP_PASS"
filetype:json "token"
filetype:sql "INSERT INTO users"
filetype:bak password
inurl:credentials.txt
intext:"auth_token"
intitle:"credentials" "login"
intext:"private key"
```


 ‎
***📄 2. Exposed Files & Documents:***

 
```
filetype:pdf confidential
filetype:docx financial
filetype:xls site:gov
filetype:pptx confidential
inurl:/backup/ filetype:zip
inurl:/archive/ filetype:tar
intitle:"index of" db
filetype:accdb
filetype:sqlite
filetype:mdb
filetype:rsa
filetype:key
filetype:ini
filetype:bak
filetype:db
filetype:sql
filetype:csv username password
filetype:xml intext:<password>
filetype:txt private
filetype:log error
filetype:pdf username
filetype:doc password
filetype:ods sensitive
filetype:pdf "internal use only"
```


 

***🛠️ 3. Admin & Login Pages:***

 
```
inurl:admin login
inurl:administrator login
inurl:wp-admin
inurl:cpanel
inurl:dashboard login
intitle:"Login Page"
inurl:signin.aspx
inurl:userlogin
inurl:auth
inurl:secure login
inurl:admin port
inurl:admin.cgi
inurl:console login
inurl:login.php
inurl:login.asp
inurl:admin.jsp
inurl:panel login
inurl:administrator.asp
inurl:site admin
inurl:admin_login
inurl:login?redirect=
```


 

***📡 4. Indexed Servers & Directories:***

 
```
intitle:"index of" /admin
intitle:"index of" /backup
intitle:"index of" /private
intitle:"index of" /secure
intitle:"index of" /uploads
intitle:"index of" /config
intitle:"index of" /db
intitle:"index of" /data
intitle:"index of" /logs
intitle:"index of" /secure‑files
intitle:"index of" /ftp
intitle:"index of" /git
intitle:"index of" /svn
intitle:"index of" /backup.zip
intitle:"index of" .env
```



 
***⚠️ 5. Error Messages & Debug Info:***

 
```
intext:"Warning:" "on line"
intext:"Fatal error" intext:"on line"
intext:"Notice:" "Undefined"
intext:"Exception"
intext:"Stack trace"
intext:"at line"
intext:"Debug mode"
intext:"SQL syntax"
intext:"ORA‑"
intext:"PDOException"
intext:"on line" "Warning"
intext:"compiled with unknown"
intext:"Microsoft VBScript compilation"
```



 
***🧪 6. Vulnerability‑Specific Searches:***

 
```
inurl:/phpinfo.php
inurl:phpinfo()
intext:"Joomla! 1.5"
intext:"nginx/1.6"
intext:"Apache/2.2"
intext:"IIS 6.0"
intext:"IIS 7.0"
inurl:/server‑status
intitle:"Apache Tomcat"
inurl:manager/html
intitle:"IIS Windows Server"
inurl:/test/
inurl:cgi‑bin
inurl:printf
inurl:perl.exe
intitle:"AWStats"
```


 

***🕵️ 7. OSINT — People, Emails, Usernames:***

 
```
"@gmail.com" "password"
"@yahoo.com" "password"
"intext:@company.com email"
intext:"@edu" "contact"
site:linkedin.com/in "software"
site:linkedin.com/in "cybersecurity"
site:github.com "email"
site:twitter.com "@"
"intext:phone 91"
"intext:mail: @org"
"intext:\"contact me\" email"
site:facebook.com intext: “@hotmail.com”
```


 

***📷 8. Cameras / IoT Devices:***

 
```
intitle:"Live View / - AXIS"
inurl:view/view.shtml
inurl:axis-cgi/mjpg
inurl:viewer/frame
inurl:“webcam”
inurl:"/js/wcam.html"
intitle:"IP Camera"
inurl:netcam
inurl:iCamera
intitle:"LiveView"
inurl:/video.cgi
inurl:‘.mjpg’
```



 
***📊 9. Tech & Service Fingerprinting:***

 
```
intext:"Powered by WordPress"
intext:"Drupal powered"
intext:"Joomla!"
intext:"Shopify"
intext:"Magento"
intext:"OpenCart"
intext:"phpBB"
intext:"vBulletin"
intext:"wp-content"
inurl:wp‑content
inurl:administrator/components
inurl:/mod/
inurl:/theme/
inurl:plugins
```



 
***🌐 10. Miscellaneous Useful Dorks:***
 

```
site:pastebin.com "password"
site:dropbox.com private
site:drive.google.com "confidential"
site:docs.google.com "sensitive"
site:scribd.com private
site:slideshare.net confidential
site:reddit.com "password"
site:archive.org "login"
inurl:"reset_password"
intext:"security question"
intext:"secret key"
intext:"token="
intext:"api_key"
```

 ‎

***⚠️ ⚖️ Disclaimer:***

This repository is meant for `ethical learning and authorized research only`. 
Never use `Google Dorks` to access sensitive data without explicit permission. Misuse of this knowledge can be `illegal under cyber law`.



***📌 How to Use:***

1. Visit `wwe.google.com`
2. Paste any query from the list
3. Review results responsibly
4. Report findings only if you have authorization
 ‎


***🤝 Contribution:***

Want to add more powerful and safe dorks? Give a Star.

 ‎
***📄 License:***

This project is licensed under the `MIT License`.  

 ‎
***🌟 Star the Repo:***

If you found `DorkNexus` helpful, do consider giving it a ⭐ on GitHub and sharing it with your cybersecurity circle
