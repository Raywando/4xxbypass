# 4xxbypass

A tool that automates a number of well-known 403/401 bypassing techniques. 

# Usage

`echo "https://target.com/this/is/a/403/page" | 4xxbypass`

`cat urls.txt | 4xxbypass`

# Install Instructions

1- Install httpx if not already installed from (https://github.com/projectdiscovery/httpx)

2- `curl https://raw.githubusercontent.com/Raywando/4xxbypass/main/4xxbypass > /usr/bin/4xxbypass`

3- `chmod +x /usr/bin/4xxbypass`

# Payloads

![](https://i.imgur.com/RfwGwjS.png)

Along with adding the headers
```
X-Forwarded-For: 127.0.0.1
X-Forwarded-Host: 127.0.0.1
X-Custom-IP-Authorization: 127.0.0.1
```

# PoC

![](https://i.imgur.com/jmdkfl1.gif)

# Reference

https://github.com/KathanP19/HowToHunt/blob/fcd0ce1a0f9e83df08084402dfae02f3a5267ab5/Status_Code_Bypass/403Bypass.md
