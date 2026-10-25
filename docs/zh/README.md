<p align="center"><picture><source media="(prefers-color-scheme: dark)" srcset="https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@ed4a61058a8e/assets/wordmark-dark.png"><img src="https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@ed4a61058a8e/assets/wordmark-light.png" width="420" alt="AdminsTools"></picture></p>

<p align="center"><a href="../../README.md">Türkçe</a> &nbsp;·&nbsp; <a href="../../docs/en/README.md">English</a> &nbsp;·&nbsp; <a href="../../docs/de/README.md">Deutsch</a> &nbsp;·&nbsp; <a href="../../docs/ru/README.md">Русский</a> &nbsp;·&nbsp; <b>中文</b></p>

<p align="center">网络与系统管理员的单窗口工具箱：发现、路径与速度、DNS、Web、邮件、远程管理 —— 无需安装、驱动或账户。</p>

<p align="center"><img src="https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@ed4a61058a8e/assets/screens/zh/ping.svg" width="760" alt="Ping 扫描"></p>

<p align="center">✓ 单个文件，无需安装 &nbsp;·&nbsp; ✓ 无需管理员权限 &nbsp;·&nbsp; ✓ Windows · macOS · Linux &nbsp;·&nbsp; ✓ 数据保留在本机</p>

<p align="center"><a href="http://adminstools.org/downloads/AdminsTools-2.23.0.exe"><b>Windows</b></a> <sub>.exe · ~16 MB</sub> &nbsp;|&nbsp; <a href="http://adminstools.org/downloads/AdminsTools-2.23.0-macos-arm64.zip"><b>macOS</b></a> <sub>Apple Silicon</sub> &nbsp;|&nbsp; <a href="http://adminstools.org/downloads/AdminsTools-2.23.0-macos-amd64.zip"><b>macOS</b></a> <sub>Intel</sub> &nbsp;|&nbsp; <a href="http://adminstools.org/downloads/adminstools-2.23.0-linux-amd64"><b>Linux</b></a> <sub>amd64</sub></p>

| **27** | **1** | **256** | **5** | **9** |
|:---:|:---:|:---:|:---:|:---:|
| 个工具，一个窗口 | 文件; 无需安装 | 个地址 /24 一轮扫完 | 语言: TR · EN · DE · RU · 中文 | 种配色主题，含深色 |

## 截图

| 发现 | 路径与速度 | DNS 和地址 | Web | 管理 | 计算与信息 |
|---|---|---|---|---|---|
| [Ping 扫描](#t-ping) | [Traceroute / MTR](#t-trace) | [DNS 查询](#t-dns) | [HTTP/HTTPS 摘要](#t-http) | [批量操作](#t-exec) | [子网计算](#t-subnet) |
| [端口扫描](#t-port) | [网速测试](#t-speed) | [Whois](#t-whois) | [HTTP 请求 (curl)](#t-curl) | [Mail](#t-mail) | [本机](#t-local) |
| [IP 标识](#t-ident) | [Wi-Fi](#t-wifi) | [我的公网 IP](#t-myip) | [API 客户端](#t-api) | [SNMP](#t-snmp) |  |
| [MAC 厂商](#t-mac) | [文件下载器](#t-download) |  | [证书](#t-cert) | [Syslog](#t-syslog) |  |
| [邻居 (LLDP/CDP)](#t-nbr) | [MTU 探测](#t-mtu) |  | [SSL 检查](#t-ssl) | [端口消息 / 监听](#t-send) |  |
|  |  |  |  | [抓包](#t-capture) |  |
|  |  |  |  | [Wake-on-LAN](#t-wol) |  |

### 发现

<a id="t-ping"></a>

#### Ping 扫描

一轮扫完一个 /24：延迟、ARP、丢包、名称和 MAC 厂商；对单个地址 ping 5 次或持续 ping。

![Ping 扫描](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@ed4a61058a8e/assets/screens/zh/ping.svg)

<a id="t-port"></a>

#### 端口扫描

预设配置、服务横幅、UDP 探测；高风险端口会被标记。

![端口扫描](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@ed4a61058a8e/assets/screens/zh/port.svg)

<a id="t-ident"></a>

#### IP 标识

“这个 IP 是什么？”综合 Ping、端口、SNMP、Web 和 MAC，给出有依据的评分推测。

![IP 标识](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@ed4a61058a8e/assets/screens/zh/ident.svg)

<a id="t-mac"></a>

#### MAC 厂商

任意格式的 MAC → 厂商；输入 IP 即可查出 MAC。虚拟和本地管理地址会被标记。

![MAC 厂商](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@ed4a61058a8e/assets/screens/zh/mac.svg)

<a id="t-nbr"></a>

#### 邻居 (LLDP/CDP)

逐台交换机发现；端口名称、LAG、七种布局、SVG / PNG / PDF。

![邻居 (LLDP/CDP)](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@ed4a61058a8e/assets/screens/zh/nbr.svg)

### 路径与速度

<a id="t-trace"></a>

#### Traceroute / MTR

网络通道、每一跳的丢包与延迟、世界地图。

![Traceroute / MTR](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@ed4a61058a8e/assets/screens/zh/trace.svg)

<a id="t-speed"></a>

#### 网速测试

测量到互联网或自有服务器的下载 / 上传速度。

![网速测试](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@ed4a61058a8e/assets/screens/zh/speed.svg)

<a id="t-wifi"></a>

#### Wi-Fi

信号测量, 信道视图和覆盖图。

![Wi-Fi](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@ed4a61058a8e/assets/screens/zh/wifi.svg)

<a id="t-download"></a>

#### 文件下载器

多连接并行快速下载，直接保存到下载文件夹；SHA-256 校验。

![文件下载器](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@ed4a61058a8e/assets/screens/zh/download.svg)

<a id="t-mtu"></a>

#### MTU 探测

不分片可通过的最大数据包；黑洞检测。

![MTU 探测](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@ed4a61058a8e/assets/screens/zh/mtu.svg)

### DNS 和地址

<a id="t-dns"></a>

#### DNS 查询

记录类型、多台服务器并排对比、DNSSEC、AXFR。

![DNS 查询](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@ed4a61058a8e/assets/screens/zh/dns.svg)

<a id="t-whois"></a>

#### Whois

RDAP 和传统 whois：注册商、联系人、AS、位置、原始记录。

![Whois](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@ed4a61058a8e/assets/screens/zh/whois.svg)

<a id="t-myip"></a>

#### 我的公网 IP

检测公网地址、运营商和 DNS 重定向。

![我的公网 IP](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@ed4a61058a8e/assets/screens/zh/myip.svg)

### Web

<a id="t-http"></a>

#### HTTP/HTTPS 摘要

状态码、重定向、安全标头和产品推测。

![HTTP/HTTPS 摘要](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@ed4a61058a8e/assets/screens/zh/http.svg)

<a id="t-curl"></a>

#### HTTP 请求 (curl)

分别测量 DNS、TCP、TLS 和首字节；也支持依赖 JavaScript 的页面。

![HTTP 请求 (curl)](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@ed4a61058a8e/assets/screens/zh/curl.svg)

<a id="t-api"></a>

#### API 客户端

类似 Postman，但更简洁：集合、变量、身份。

![API 客户端](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@ed4a61058a8e/assets/screens/zh/api.svg)

<a id="t-cert"></a>

#### 证书

证书链, 到期日期, 信任状态和 TLS 版本。

![证书](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@ed4a61058a8e/assets/screens/zh/cert.svg)

<a id="t-ssl"></a>

#### SSL 检查

接近 SSL Labs 标准的 A+ … F 评级及原因。

![SSL 检查](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@ed4a61058a8e/assets/screens/zh/ssl.svg)

### 管理

<a id="t-exec"></a>

#### 批量操作

通过 SSH / WinRM 在数百台机器上执行命令；支持模板和多个身份。

![批量操作](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@ed4a61058a8e/assets/screens/zh/exec.svg)

<a id="t-mail"></a>

#### Mail

SMTP、MX + SPF / DMARC、IMAP / POP3、测试邮件和中继测试。

![Mail](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@ed4a61058a8e/assets/screens/zh/mail.svg)

<a id="t-snmp"></a>

#### SNMP

Walk / get，v1–v3；在广播模式下，本机会像 SNMP 设备一样响应。

![SNMP](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@ed4a61058a8e/assets/screens/zh/snmp.svg)

<a id="t-syslog"></a>

#### Syslog

发送消息，或作为服务器监听传入消息。

![Syslog](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@ed4a61058a8e/assets/screens/zh/syslog.svg)

<a id="t-send"></a>

#### 端口消息 / 监听

向 TCP / UDP 端口发送消息并查看响应，或监听传入数据。

![端口消息 / 监听](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@ed4a61058a8e/assets/screens/zh/send.svg)

<a id="t-capture"></a>

#### 抓包

无需 Npcap 的轻量抓包、协议摘要和 pcap 保存。

![抓包](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@ed4a61058a8e/assets/screens/zh/capture.svg)

<a id="t-wol"></a>

#### Wake-on-LAN

用魔术包唤醒, 并通过 ping 监视开机。

![Wake-on-LAN](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@ed4a61058a8e/assets/screens/zh/wol.svg)

### 计算与信息

<a id="t-subnet"></a>

#### 子网计算

网络, 广播, 可用范围, 掩码和拆分。

![子网计算](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@ed4a61058a8e/assets/screens/zh/subnet.svg)

<a id="t-local"></a>

#### 本机

接口, adresler, 网关, DNS 和 VPN。

![本机](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@ed4a61058a8e/assets/screens/zh/local.svg)

## Neden AdminsTools

- **快速, 但不拖慢电脑** — Ping 以平稳的节奏发出：交换设备不会过载，响应不会丢失。程序以低优先级在少数几个核心上运行。
- **强大的筛选器** — 预设按钮、带计数的值列表、范围以及简洁的查询语言： `vendor:hp rtt>20 -down`。行不会跳动。
- **结果历史与导出** — 每次运行都会保留并按名称保存。Excel、CSV、pcap、SVG / PNG / PDF；文件直接保存到下载文件夹。
- **密码库** — SSH、WinRM、SNMP v3 和邮件密码保存在以 Argon2id + AES-GCM 加密的密码库中；不会写入设置或结果文件。
- **数据留在您的电脑上** — 无账户、无云端、无遥测。界面仅在 127.0.0.1 上通过会话密钥打开。
- **5 种语言, 9 种主题** — 土耳其语、英语、德语、俄语、中文。浅色和深色主题；列宽和视图会被记住。

## 下载

版本 2.23.0 · 单个文件：下载即可运行。设置保存在一个文件中；将 `PowerAdminTool.json` 放在 exe 旁边，即可从 U 盘便携运行。

**Windows** — `AdminsTools-2.23.0.exe · ~16 MB`

- Windows 10 / 11, 64 bit
- 无需安装和管理员权限
- Ping 和 traceroute 无需驱动

[⤓ 下载 Windows 版](http://adminstools.org/downloads/AdminsTools-2.23.0.exe)

**macOS** — `AdminsTools-2.23.0-macos-arm64.zip · -macos-amd64.zip`

- Apple Silicon (M1 及更新) 或 Intel
- 未签名: 首次打开时右键 › 打开
- macOS 上不支持抓包

[⤓ Apple Silicon](http://adminstools.org/downloads/AdminsTools-2.23.0-macos-arm64.zip) &nbsp;·&nbsp; [⤓ Intel](http://adminstools.org/downloads/AdminsTools-2.23.0-macos-amd64.zip)

**Linux** — `adminstools-2.23.0-linux-amd64 · ~15 MB`

- x86-64，单个二进制文件
- `-listen 0.0.0.0:8090` 可在跳板机上通过浏览器使用
- Ping 需要： `ping_group_range` 或 `cap_net_raw`

[⤓ 下载 Linux 版](http://adminstools.org/downloads/adminstools-2.23.0-linux-amd64)

---

© 2026 Mehmet Göğebakan
