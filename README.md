# Surge规则文件汇总
# 生成时间: 2025-07-10 13:35:52

## 总体统计
- 总规则数: 40669
- 分类数: 7
- 生成文件数: 7

## 分类详情
### China IP-ASN
- 描述: 中国大陆IP地址段和ASN
- 规则数: 5485
- 文件: cn_asn.list
  - IP-ASN: 5485

### China Domains
- 描述: 中国大陆常见域名
- 规则数: 3754
- 文件: cn_sites.list
  - DOMAIN: 17
  - DOMAIN-KEYWORD: 9
  - DOMAIN-SUFFIX: 3676
  - IP-CIDR: 17
  - IP-CIDR6: 4
  - USER-AGENT: 31

### proxy sites
- 描述: 国外常见网站
- 规则数: 30783
- 文件: proxy.list
  - DOMAIN: 84
  - DOMAIN-KEYWORD: 26
  - DOMAIN-SUFFIX: 30568
  - IP-CIDR: 93
  - IP-CIDR6: 4
  - USER-AGENT: 8

### Telegram
- 描述: Telegram相关域名和IP
- 规则数: 24
- 文件: telegram.list
  - DOMAIN-SUFFIX: 5
  - IP-ASN: 2
  - IP-CIDR: 11
  - IP-CIDR6: 4
  - PROCESS-NAME: 2

### AIGC
- 描述: 不对中国大陆地区提供服务的AI服务商域名和IP
- 规则数: 228
- 文件: aigc.list
  - DOMAIN: 30
  - DOMAIN-KEYWORD: 17
  - DOMAIN-SUFFIX: 159
  - IP-ASN: 2
  - IP-CIDR: 15
  - IP-CIDR6: 5

### Direct
- 描述: 无需代理的域名
- 规则数: 254
- 文件: direct.list
  - DOMAIN: 56
  - DOMAIN-KEYWORD: 35
  - DOMAIN-SUFFIX: 126
  - PROCESS-NAME: 36
  - USER-AGENT: 1

### LAN
- 描述: 局域网域名
- 规则数: 141
- 文件: lan.list
  - DOMAIN: 6
  - DOMAIN-SUFFIX: 117
  - IP-CIDR: 14
  - IP-CIDR6: 4
