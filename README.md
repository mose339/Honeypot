# Honeypot
1. Create a Google Cloud account. Use the site console.google.com.

2. I created a VM called "min-admin." I followed the instructions on the CodePath site.

*Note*: I had an issue with the account username and email. I ran commands to set it up again. Then I could log on.
```
$ sudo su - 
# cd /opt/mhn
# source env/bin/activate
# python server/manual_password_reset.py
```
![admin screenshot](https://github.com/mose339/Honeypot/blob/main/images/HoneyPot%20Admin.png)


3. I created a VM called "honeypot-1".
![honeypot attacks](https://github.com/mose339/Honeypot/blob/main/images/HoneyPot%20Attacks.png)
