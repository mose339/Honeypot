# Honeypot
1. Create a Google Cloud account. Use the site console.google.com.

2. I created a VM called "mhn-admin." I followed the instructions on the CodePath site.

*Note*: I had an issue with the account username and email. I ran commands to set it up again. Then I could log on.
```
$ sudo su - 
# cd /opt/mhn
# source env/bin/activate
# python server/manual_password_reset.py
```
![admin screenshot](https://github.com/mose339/Honeypot/blob/main/images/Honeypot%20Admin.png)


3. I created a VM called "honeypot-1" which in deployeed dionea.

![honeypot attacks](https://github.com/mose339/Honeypot/blob/main/images/Honeypot%20Attacks.png)

As a result the date takes place at 2020-11-21 at the time of 10:32, with an attack from Russia with the Source IP of 87.251.74.13, the destination port of 5941
