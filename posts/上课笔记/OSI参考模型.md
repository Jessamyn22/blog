---
published: 2026-11-09
tags:
  - 底层知识
title: OSI参考模型
category: 知识
---
## OSI 七层 / 'TCP/IP' 四层

| OSI 七层   | TCP/IP 四层 | 主要协议                 | 数据单元    |
| -------- | --------- | -------------------- | ------- |
| 7. 应用层   | 4. 应用层    | HTTP, DNS, FTP, SMTP | 报文      |
| 6. 表示层   | 4. 应用层    | TLS/SSL, MIME        | 报文      |
| 5. 会话层   | 4. 应用层    | NetBIOS, RPC         | 报文      |
| 4. 传输层   | 3. 传输层    | TCP, UDP             | 段 / 数据报 |
| 3. 网络层   | 2. 网络层    | IP, ICMP, ARP        | 包       |
| 2. 数据链路层 | 1. 网络接口层  | Ethernet, PPP, Wi-Fi | 帧       |
| 1. 物理层   | 1. 网络接口层  | 双绞线、光纤               | 比特      |
