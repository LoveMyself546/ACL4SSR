# 原ACL规则https://github.com/ACL4SSR/ACL4SSR 基于此规则按个人习惯二次修改
## 已修改内容如下：
### steam.list
* 去掉下载相关域名的代理（下载直连不走代理）
### 新增Uplay.list
### 新增CustomDirect.list
* 增加uplay和steam的登陆直连规则（避免因IP的切换导致每次登陆都需要验证）

#
# 目前Clash支持的规则类型如下：
* DOMAIN-SUFFIX：域名后缀匹配
* DOMAIN：域名匹配
* DOMAIN-KEYWORD：域名关键字匹配
* IP-CIDR：IP段匹配
* SRC-IP-CIDR：源IP段匹配
* GEOIP：GEOIP数据库（国家代码）匹配
* DST-PORT：目标端口匹配
* SRC-PORT：源端口匹配
* MATCH：全匹配（一般放在最后）
