---
layout: post
title: ARP / Mac / IPtable 三大表
tags: 
categories: 🌐-NET
---

ARP 表: IP+MAC+ 接口信息备注

`SH-OFFICE-GATEWAY(show)# arp`

	Total ARP entries: 177
	----------------|--------------------------|------------------------|-----------
	     IP Address |     MAC Address          |     Interface[~Port]   |     Flags
	----------------|--------------------------|------------------------|-----------
	172.19.10.1     | 00:02:85:0A:75:40        | lo0                    | Static
	172.19.10.10    | 00:0C:29:07:02:01        | TO-RDOMAIN~et.2.15     |
	172.19.10.15    | 00:14:38:50:3A:B2        | TO-RDOMAIN~et.2.5      |
	172.19.12.9     | 00:02:85:0A:75:40        | lo0                    | Static
	172.19.12.10    | 00:1F:9E:CC:D6:9A        | TO-ASA~et.2.2          |
	172.19.12.25    | 00:02:85:0A:75:40        | lo0                    | Static
	172.19.12.26    | 00:D0:FF:12:34:70        | TO-7206~et.2.4         |
	172.19.16.1     | 00:02:85:0A:75:40        | lo0                    | Static
	172.19.16.9     | Invalidated              | TO-LAN                 |
	172.19.16.12    | 00:0C:29:8D:D8:CA        | TO-LAN~et.1.6          |
	172.19.16.13    | A4:1F:72:67:3A:24        | TO-LAN~et.1.6          |
	172.19.16.15    | 00:0C:29:B5:D1:EE        | TO-LAN~et.1.6          |
	172.19.16.16    | F4:CE:46:B1:19:06        | TO-LAN~et.1.1          |


