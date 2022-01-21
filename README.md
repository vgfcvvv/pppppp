#!MANAGED-CONFIG http://127.0.0.1:25500/sub?target=surfboard&url=vmess%3A%2F%2FeyJhZGQiOiIwMTA1dHcuZmFuczgueHl6IiwiYWlkIjoiMiIsImhvc3QiOiIiLCJpZCI6ImU5NTYxZDgyLTM2NmUtMzgwYy1iZWZlLWEwMTkzNzVlZGU1ZCIsIm5ldCI6IndzIiwicGF0aCI6Ii92MnJheSIsInBvcnQiOiI4MCIsInBzIjoi5Y%2Bw5rm%2BMfCfh7nwn4e8LeS4iee9keS8mOWMliIsInNjeSI6Im5vbmUiLCJzbmkiOiIiLCJ0bHMiOiIiLCJ0eXBlIjoiIiwidiI6IjIifQ%3D%3D&insert=false&config=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2FSleepyHeeead%2Fsubconverter-config%40master%2Fremote-config%2Fspecial%2Fbasic.ini interval=86400 strict=false

[General]
loglevel = notify
interface = 127.0.0.1
skip-proxy = 127.0.0.1, 192.168.0.0/16, 10.0.0.0/8, 172.16.0.0/12, 100.64.0.0/10, localhost, *.local
ipv6 = false
dns-server = system, 8.8.8.8
exclude-simple-hostnames = true
enhanced-mode-by-rule = true

[Proxy]
DIRECT = direct
🇨🇳 台湾1🇹🇼-三网优化 = vmess, 0105tw.fans8.xyz, 80, username=e9561d82-366e-380c-befe-a019375ede5d, tls=false, ws=true, ws-path=/v2ray, sni=0105tw.fans8.xyz, ws-headers=Host:0105tw.fans8.xyz

[Proxy Group]
Proxies = select,🇨🇳 台湾1🇹🇼-三网优化

[Rule]
DOMAIN-SUFFIX,1password.com,DIRECT
DOMAIN-SUFFIX,vultr.com,DIRECT
DOMAIN-SUFFIX,mb3admin.com,DIRECT
DOMAIN-SUFFIX,rixcloud.io,DIRECT
DOMAIN-SUFFIX,tempestapp.io,DIRECT
DOMAIN-SUFFIX,baidu.com,DIRECT
DOMAIN-SUFFIX,baidu-int.com,DIRECT
DOMAIN-SUFFIX,erebor.douban.com,DIRECT
DOMAIN,mtalk.google.com,DIRECT
DOMAIN,alt1-mtalk.google.com,DIRECT
DOMAIN,alt2-mtalk.google.com,DIRECT
DOMAIN,alt3-mtalk.google.com,DIRECT
DOMAIN,alt4-mtalk.google.com,DIRECT
DOMAIN,alt5-mtalk.google.com,DIRECT
DOMAIN,alt6-mtalk.google.com,DIRECT
DOMAIN,alt7-mtalk.google.com,DIRECT
DOMAIN,alt8-mtalk.google.com,DIRECT
DOMAIN,alt9-mtalk.google.com,DIRECT
DOMAIN,captive.apple.com,DIRECT
DOMAIN,time-ios.apple.com,DIRECT
DOMAIN-SUFFIX,gateway.push-apple.com.akadns.net,DIRECT
DOMAIN-SUFFIX,push.apple.com,DIRECT
DOMAIN-KEYWORD,github,Proxies
DOMAIN-SUFFIX,github.com,Proxies
DOMAIN-SUFFIX,github.io,Proxies
DOMAIN-SUFFIX,githubapp.com,Proxies
DOMAIN-SUFFIX,githubassets.com,Proxies
DOMAIN-SUFFIX,githubusercontent.com,Proxies
DOMAIN-SUFFIX,home-intl.console.aliyun.com,Proxies
DOMAIN,ip.skk.moe,Proxies
DOMAIN,ip.sb,Proxies
DOMAIN-SUFFIX,googleapis.cn,Proxies
DOMAIN-SUFFIX,maying.co,Proxies
DOMAIN-SUFFIX,flowercloud.net,Proxies
DOMAIN-SUFFIX,socloud.me,Proxies
DOMAIN-SUFFIX,ytoo.asia,Proxies
DOMAIN-SUFFIX,ytoo.co.uk,Proxies
GEOIP,CN,DIRECT
FINAL,Proxies
