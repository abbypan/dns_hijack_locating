# dns_hijack_locating
how to locate the dns hijack, DNS劫持定位方法

参考：[DNS Security : DDoS, Hijack, Configure Error, Management 安全事件](https://abbypan.github.io/2013/10/18/dns-security)

the logic of hijack location

resolution path : user PC -> ISP recursive / Public recursive -> authoritative ( root, TLD, SLD )

client : PC host file

recursive : the geolocation distribution of influnence clients

recursive : the type distribution of influnence recursive servers, public/isp/company

SLD : the influnence domain type distribution 

TLD : the truncate difference of TLD, com/net/cn/...

important business domain authoritative server : same NS, different domain's resolution

recursive log of important business domain : in NS TTL expiration, same hot business domain resolution
