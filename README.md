# v2ray

#### open from web
`http://\<IP\>:65432`
  
**default web port:**  `65432`

**default ID:** `admin`  **password:** `admin`
  
  
#### setup
- remark: whatever
- enable: on
- protocol: vmess
- listening IP: sever IP
- prot: <setting port>
- id: default
- alter id: 64
- disable insecure encryption: on
- transport: TCP
- http comouflage: off
- tls: off

#### pac mode
revise the first line of pac.js to
`var varRay =“SOCKS5 127.0.0.1:1080; SOCKS 127.0.0.1:1080; DIRECT;”;`
