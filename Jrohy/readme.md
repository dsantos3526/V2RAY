#Multi V2ray


Install
```
source <(curl -sL https://multi.netlify.app/v2ray.sh)
```
Keep profile to update
```
source <(curl -sL https://multi.netlify.app/v2ray.sh) -k
```
Uninstall
```
source <(curl -sL https://multi.netlify.app/v2ray.sh) --remove
```

Notes
```
v2ray/xray [-h|help] [options]
    -h, help             get help
    -v, version          get version
    start                start V2Ray
    stop                 stop V2Ray
    restart              restart V2Ray
    status               check V2Ray status
    new                  create new json profile
    update               update v2ray to latest
    update [version]     update v2ray to special version
    update.sh            update multi-v2ray to latest
    add                  add new group
    add [protocol]       create special protocol, random new port
    del                  delete port group
    info                 check v2ray profile
    port                 modify port
    tls                  modify tls
    tfo                  modify tcpFastOpen
    stream               modify protocol
    cdn                  cdn mode
    stats                v2ray traffic statistics
    iptables             iptables traffic statistics
    clean                clean v2ray log
    log                  check v2ray log
    rm                   uninstall core
```




# Reference
* https://github.com/Jrohy/multi-v2ray/blob/master/README_EN.md
* https://github.com/Jrohy/multi-v2ray
