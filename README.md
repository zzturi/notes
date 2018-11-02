# Content

_________________________________/

- [MyProject](#myproject)我的项目
- [MyNotes](#mynotes)我的笔记
- [Security](#security)安全
    + [知识_SDL](#知识_sdl)
    + [知识_RedTeam](#知识_redteam)
    + [全能框架](#全能框架)
    + [工具_后渗透windows](#工具_后渗透windows)
    + [工具_后渗透](#工具_后渗透)
    + [工具_CTF](#工具_ctf)
    + [工具_反编译_Decompiler](#工具_反编译_Decompiler)
    + [工具_二进制_debug_pwn](#工具_二进制_debug_pwn)
    + [工具_二进制_fuzz](#工具_二进制_fuzz)
    + [工具_Proxy代理](#工具_proxy代理)
    + [ProxyPool](#proxypool)
    + [工具_防御与分析](#工具_防御与分析)
    + [工具_扫描自动化](#工具_扫描自动化)
    + [爬虫](#爬虫)
    + [工具_github泄露扫描](#工具_github泄露扫描)
    + [工具_免杀AntiVirusEvasion](#工具_免杀antivirusevasion)
    + [CMS](#cms)
    + [工具_Phishing钓鱼](#工具_phishing钓鱼)
    + [PortExp](#portexp)
    + [website_mail匿名邮箱](#website_mail匿名邮箱)
    + [website_知识_安全技术](#website_知识_安全技术)
    + [website_exp引擎](#website_exp引擎)
    + [website_网络空间引擎](#website_网络空间引擎)
    + [website_威胁分析引擎_防御](#website_威胁分析引擎_防御)
    + [website_安全工具_防御](#website_安全工具_防御)
    + [website_安全工具](#website_安全工具)
    + [website_encoder](#website_encoder)
    + [website_ip](#website_ip)
- [Development](#development)开发
    + [必备网站](#必备网站)
    + [其他网站](#其他网站)
    + [web应用开发-基础框架](#web应用开发-基础框架)
    + [web前端](#web前端)
    + [web系统](#web系统)
    + [学习项目](#学习项目)
    + [知识](#知识)
    + [其他工具](#其他工具)
    
_________________________________/

## MyProject
|项目名称|属性|描述|
|:-------------:|--|-----|
|[EquationExploit](https://github.com/1135/EquationExploit)|Java C++|在Windows下针对网段批量利用永恒之蓝漏洞(MS-17010 EternalBlue) |
|[Applescript_demos](https://github.com/1135/Applescript_demos)|applescript|苹果脚本示例，在Mac下使用苹果脚本实现发送iMessage短信|
|[VulSpider](https://github.com/1135/VulSpider)|python2|后台持续运行，获取最新漏洞及每日简报，发送邮件给安全人员|

## MyNotes

|笔记标题|属性|描述|
|:-------------:|--|-----|
|[静态爬虫利器 - GraphQuery](z_web_crawl.md)|web|z_web_crawl.md|
|[wireshark使用总结](z_net_wireshark.md)|net|z_net_wireshark.md|
|[MacOS下的好用软件、快捷键、命令、技巧](z_command_Mac_软件_快捷键_命令_技巧.md)|Mac|z_command_Mac_软件_快捷键_命令_技巧.md|
|[Ubuntu/CentOS一键安装Socks5代理服务器](linux_proxy_Ubuntu_CentOS_socks5_Server.md)|Proxy|linux_proxy_Ubuntu_CentOS_socks5_Server.md|
|[web中间件修复方案 SSL slowhttpdos Tomcat](web___fix_中间件漏洞修复方案_SSL_slowhttpdos.md)|web|web___fix_中间件漏洞修复方案_SSL_slowhttpdos.md|
|[虚拟币挖矿的多种方式](z_blockchain_mining.md)|blockchain|z_blockchain_mining.md|
|[远控软件历史](z_history_RAT.md)|RAT|z_history_RAT.md|

---

## Security

#### 知识_SDL

|名称|描述|
|:-------------:|--|
|[sdlchina-web](https://github.com/sdlchina/sdlchina-web/tree/master/_posts)|SDL流程简介 SDL规范文档 SDL落地方案|


#### 知识_RedTeam

|名称|描述|
|:-------------:|--|
|[Red-Team-Infrastructure-Wiki](https://github.com/bluscreenofjeff/Red-Team-Infrastructure-Wiki)|红队基础设施Wiki|


#### 全能框架

|名称|属性|运行环境|描述|
|:-------------:|--|--|-----|
|[metasploit-framework](http://github.com/rapid7/metasploit-framework)|Ruby #RAT|Linux/Mac OS/windows|必备的功能强大的渗透测试框架|

#### 工具_后渗透windows

|名称|属性|运行环境|描述|
|:-------------:|--|--|-----|
|[Empire](https://github.com/EmpireProject/Empire)|python|Kali/Debian/Ubuntu|#域渗透 #RAT 域渗透利器Empire is a post-exploitation framework|
|[CrackMapExec](https://github.com/byt3bl33d3r/CrackMapExec)|python+powershell|[Installation](https://github.com/byt3bl33d3r/CrackMapExec/wiki/Installation)| 2k★ #域渗透 域渗透利器|
|[QuasarRAT](https://github.com/quasar/QuasarRAT)|C#|windows|#RAT 传统远控 Remote Administration Tool for Windows|
|[sRDI](https://github.com/monoxgas/sRDI)|powershell|windows|Shellcode implementation of Reflective DLL Injection. Convert DLLs to position independent shellcode|

#### 工具_后渗透

Remote Administration Tool

|名称|属性|运行环境|描述|
|:-------------:|--|--|-----|
|[EggShell](https://github.com/neoneggplant/EggShell)|python|macOS/Linux|#RAT iOS(Jailbroken)/macOS/Linux(OnlyFileManage)|
|[LaZagne](https://github.com/AlessandroZ/LaZagne)|python|windows/Linux/macOS|#密码恢复 Credentials recovery project. 系统口令/浏览器软件/邮箱软件/wifi|
|[backdoors](https://github.com/iamckn/backdoors)|sh|linux|#backdoor [利用SSH日志触发的后门分析](http://www.freebuf.com/articles/system/185942.html)|
|[dnscat2](https://github.com/iagox86/dnscat2)|C++ C Ruby|linux Win32|#backdoor DNS后门|
|[m0nad/Diamorphine](https://github.com/m0nad/Diamorphine)|C|linux|#backdoor 需要ROOT权限 隐藏指定进程与通信 LKM rootkit for Linux Kernels 2.6.x/3.x/4.x (x86 x86_64)|


#### 工具_CTF

|名称|描述|
|:-------------:|--|
|https://github.com/zardus/ctf-tools|3k★ CTF工具集 包含类型:binary forensics crypto web stego misc|


知识_CTF

|名称|描述|
|:-------------:|--|
|https://ctf-wiki.github.io/ctf-wiki/|#CTF知识 wiki知识库|
|http://www.garykessler.net/library/file_sigs.html|#CTF知识 各种文件头部hex值 真实文件格式|


#### 工具_反编译_Decompiler

|名称|属性|描述|
|:-------------:|--|-----|
|[Luyten](https://github.com/deathmarine/Luyten)|Java|2k★ Java Decompiler [Gui] |


#### 工具_二进制_debug_pwn

|名称|属性|描述|
|:-------------:|--|-----|
|[gdbgui](https://github.com/cs01/gdbgui)|/|6k★ 基于浏览器可视化gdb调试 [下载安装ubuntu14.04+](https://gdbgui.com/downloads.html)|
|[peda](https://github.com/longld/peda)|python|6k★ Python Exploit Development Assistance for GDB|
|[pwntools](https://github.com/Gallopsled/pwntools)|python2.7(best Ubuntu)|4k★ CTF framework and exploit development library|
|[heap-viewer](https://github.com/danigargu/heap-viewer)|python| [IDA Pro plugin] examine the glibc heap, focused on exploit development|

|名称|属性|描述|
|http://syscalls.kernelgrok.com/|/|系统调用参考 主要用sys_execve|
http://shell-storm.org/shellcode/|shellcode|各种平台下的shellcode包括:BSD/Cisco/FreeBSD/Linux/OSX/Windows|


#### 工具_二进制_fuzz

|名称|属性|描述|
|:-------------:|--|-----|
|[halfempty](https://github.com/googleprojectzero/halfempty)|C|[projectZero] testcase minimization tool.|


#### 工具_Proxy代理

|名称|属性|描述|
|:-------------:|--|-----|
|[frp](https://github.com/fatedier/frp)|golang|14k★ 高性能的反向代理(reverse proxy). 可用于内网穿透,支持协议:tcp, udp, http, https.[中文文档](https://github.com/fatedier/frp/blob/master/README_zh.md)|
|[brook](https://github.com/txthinking/brook)|golang|6k★ 【Server端】(Linux/MacOS/Windows/Android/iOS)开启VPN/Socks5/Shadowsocks 【Client端】可连接，以及Socks5 to HTTP|

#### ProxyPool
|名称|描述|
|:-------------:|-----|
|http://proxylist.fatezero.org/proxy.list | 在线代理池 每15分钟更新. 实测很多高匿代理会暴露真实ip(具体在http header的X-Forwarded-For中最后一个ip)   即https://github.com/fate0/proxylist/blob/master/proxy.list|


#### 工具_防御与分析

|名称|属性|描述|
|:-------------:|-----|-----|
|[suricata](https://github.com/OISF/suricata) |流量解析| #强大的网络威胁检测引擎 real time IDS, IPS, network security monitoring (NSM) and offline pcap processing.|
|[cuckoo](https://github.com/cuckoosandbox/cuckoo)|文件分析引擎|3k★ #分析行为 an automated dynamic malware analysis system|


#### 工具_扫描自动化

|名称|属性|运行环境|描述|
|:-------------:|--|--|-----|
|[Yuki-Chan-The-Auto-Pentest](https://github.com/Yukinoshita47/Yuki-Chan-The-Auto-Pentest)|python+shell|kali_linux|Automate Pentest Tool|
|[Sn1per](https://github.com/1N3/Sn1per)|python+shell|kali_linux docker|Automated Pentest Recon Scanner.  kali`./install.sh`|

#### Payload_弱口令字典
|名称|描述|
|:-------------:|-----|
|https://github.com/danielmiessler/SecLists/tree/master/Passwords|弱口令字典|
|https://weakpass.com/|弱口令字典|


#### 爬虫

|名称|属性|描述|
|:-------------:|--|-----|
|https://github.com/NikolaiT/GoogleScraper|python3.7| 2k★ 异步搜索引擎爬虫 A Python module to scrape several search engines.|
|[chromeless](https://github.com/prisma/chromeless)|js|动态爬虫 Chrome自动化|
|[Anti-Anti-Spider](https://github.com/luyishisi/Anti-Anti-Spider)|python|反反爬虫|

#### 基本库

|名称|属性|描述|
|:-------------:|--|-----|
|[httplib2](https://github.com/httplib2/httplib2)|python|社区维护的HTTP client library 特性包括:所有Methods 授权Authentication 持久连接Keep-Alive 缓存Caching  压缩Compression(gzip/deflate)|
|[puppeteer](https://github.com/GoogleChrome/puppeteer)|js| 38k★ [google] Headless Chrome Node API |


#### 工具_github泄露扫描
|名称|属性|运行环境|描述|
|:-------------:|--|--|-----|
|[x-patrol](https://github.com/MiSecurity/x-patrol/)|golang|all|MiSecurity|

#### 工具_免杀AntiVirusEvasion

FUD:Fully undetectable

|名称|属性|描述|
|:-------------:|--|-----|
|[avet](https://github.com/govolution/avet)|C+shell+python|[仅针对Windows exe] AntiVirus Evasion Tool 运行于kali2|
|[Veil-Evasion](https://github.com/Veil-Framework/Veil-Evasion)|shell+C+python2.7|[可针对Windows exe] generate metasploit payloads that bypass common anti-virus solutions|
|[ASWCrypter](https://github.com/AbedAlqaderSwedan1/ASWCrypter)|shell+python|An Bash&Python Script For Generating Payloads that Bypasses All Antivirus so far FUD.实测无法过360ZhuDongFangyu|

#### CMS
|名称|属性|描述|
|:-------------:|--|-----|
|[WordPress](https://github.com/WordPress/WordPress)|php|11k★ 31% of the web uses [WordPress](https://wordpress.org/), from hobby blogs to the biggest news sites online.|
|[joomla](https://github.com/joomla/joomla-cms)|php|3k★ Joomla! Content Management System.|


#### 工具_Phishing钓鱼

|名称|属性|运行环境|描述|
|:-------------:|--|--|-----|
|[gophish](https://github.com/gophish/gophish)|golang|all|2k★ Open-Source Phishing Toolkit. 用于对企业进行定期的钓鱼测试. 启动后先在`Sending Profiles`中配置真实可用的`mail server`,发起一个Campaign:钓鱼邮件(内含钓鱼网站) [使用视频](https://www.youtube.com/watch?v=knc6Iq-hNcw)|
|[blackeye](https://github.com/flagellantX/blackeye)|.sh .php|/| 钓鱼页面Phishing Pages 含各大网站`Facebook,Google,Twitter,Microsoft`等|


#### PortExp

|针对端口|工具名称|编程语言|工具描述|
|:-------------:|--|--|-----|
|1099(RMI)|[BaRMIe](https://github.com/NickstaDB/BaRMIe)|Java| enumerating and attacking Java RMI (Remote Method Invocation) services.|

```
#BaRMIe
java -jar BaRMIe_v1.01.jar -attack ip port
#可以只输入ip自动进行端口枚举
#支持13种payload
Deserialization payloads for: 10.0.0.1:1099
 1) Apache Commons Collections 3.1, 3.2, 3.2.1
 2) Apache Commons Collections 4.0-alpha1, 4.0
 3) Apache Groovy 1.7-beta-1 to 2.4.0-beta-4
 4) Apache Groovy 2.4.0-rc1 to 2.4.3
 5) JBoss Interceptors API
 6) ROME 0.5 to 1.0
 7) ROME 1.5 to 1.7.3
 8) Mozilla Rhino 1.7r2
 9) Mozilla Rhino 1.7r2 for Java 1.4
 10) Mozilla Rhino 1.7r3
 11) Mozilla Rhino 1.7r3 for Java 1.4
 12) Mozilla Rhino 1.7r4 and 1.7r5
 13) Mozilla Rhino 1.7r6, 1.7r7, and 1.7.7.1
 ```
 

#### website_mail匿名邮箱

|名称|描述|
|:-------------:|--|
|https://emkei.cz/|在线发送钓鱼邮件 可伪造邮件发送者 (如伪造xx@163.com发送到qq邮箱)|
|http://www.yopmail.com/zh/|临时邮箱 可随意进入xxx@yopmail.com收发邮件|
|http://www.mailinator.com/|临时邮箱 可随意进入asd@mailinator.com收邮件|
|https://10minutemail.net/|临时邮箱 十分钟邮箱 短期 每次邮箱地址不同 适用于注册小号|
|https://protonmail.com/|匿名邮箱 瑞士的加密邮箱 长期 google验证码认证后可注册.[福布斯评价：唯一NSA 无法接近的邮件服务](http://www.forbes.com/sites/hollieslade/2014/05/19/the-only-email-system-the-nsa-cant-access/#5060612155ed) |


#### website_知识_安全技术

|名称|属性|描述|
|:-------------:|--|-----|
|[OWASP](https://www.owasp.org/index.php/Main_Page)|知识库|自由开放的软件安全社区|
|-|知识库|OWASP web测试指南V4 双语 [owasp-testing-guide-v4](/https://kennel209.gitbooks.io/owasp-testing-guide-v4/content/)|
|-|知识库|#反序列化安全# [Deserialization Cheat Sheet](https://www.owasp.org/index.php/Deserialization_Cheat_Sheet)|
|https://attack.mitre.org/|知识库|真实世界用到的、系统化的网络攻击技术|
|[www.seebug.org](https://www.seebug.org/)|/|知道创宇|
|[paper.seebug.org](https://paper.seebug.org/)|Papers|知道创宇 Papers|


#### website_exp引擎

|名称|属性|描述|
|:-------------:|--|-----|
|[exploit-db](https://www.exploit-db.com/)|exp引擎|Offensive Security’s Exploit Database Archive.|
|-|exp引擎|[Remote Exploits](https://www.exploit-db.com/remote/)|
|-|exp引擎|[Web Application Exploits](https://www.exploit-db.com/webapps/)|
|-|exp引擎|[Local & Privilege Escalation Exploits](https://www.exploit-db.com/local/)|
|-|exp引擎|[Denial of Service & Proof of Concept Exploits](https://www.exploit-db.com/dos/)|
|-|/|[Exploit Shellcode Archive](https://www.exploit-db.com/shellcode/)|
|-|Papers|[Archived Security Papers](https://www.exploit-db.com/papers/)|
|[sploitus.com](https://sploitus.com/)|exp引擎|Exploits.|


#### website_网络空间引擎

|名称|属性|描述|
|:-------------:|--|-----|
|[Shodan.io](https://www.shodan.io/)|网络空间引擎|Shodan is the world's first search engine for Internet-connected devices.|
|[Fofa.so](https://fofa.so/)|网络空间引擎|白帽汇 [规则列表](https://fofa.so/library)|
|[Zoomeye](https://www.zoomeye.org/)|网络空间引擎|知道创宇|
|[censys.io](https://censys.io/ipv4)|网络空间引擎|censys.io|

#### website_威胁分析引擎_防御

|名称|属性|描述|
|:-------------:|--|-----|
|[360威胁分析平台](https://ti.360.net/)|威胁分析引擎|威胁情报 ip domain file url email|
|[微步在线威胁情报](https://x.threatbook.cn/nodev4/vb4/list)|威胁分析引擎|威胁情报 ip domain file url email|
|[在线沙箱app.any.run](https://app.any.run/tasks/defe1b39-b4b6-4573-ba46-de2c425f670f)|威胁分析引擎|在线沙箱:提取ioc 下载样本 下载pcap文件 运行线程 DNS解析 http通信|


#### website_安全工具_防御
|名称|描述|
|:-------------:|-----|
|http://spf.myisp.ch/|#防御 邮件服务器SPF配置检查|

#### website_安全工具

|名称|描述|
|:-------------:|-----|
|[findsubdomains.com](https://findsubdomains.com/) |domain信息收集 子域名查找 Find subdomains online.|
|[dnsdumpster.com](https://dnsdumpster.com/) |domain信息收集 DNS枚举子域名 FREE domain research tool that can discover hosts related to a domain.|
|[wappalyzer.com](https://www.wappalyzer.com/) |信息收集 web技术栈 web frameworks, server software, analytics tools and many more. |
|[onlinehashcrack.com](https://www.onlinehashcrack.com/) |crack在线破解 Hashes(NTLM/wordpress/MySQL). Wifi WPA(2). MS Office.|
|https://www.irongeek.com/homoglyph-attack-generator.php|外观类似的替换字符 常用于钓鱼|


#### website_encoder

|名称|描述|
|:-------------:|-----|
|https://codebeautify.org/|进制转换 json xml Escape/Unescape sql...|


#### website_ip

|名称|描述|
|:-------------:|-----|
|https://whoer.net/ | ip匿名性自测 可获取内网ip(通过webRTC等技术) |
|https://www.ipip.net/ip.html | 查国内ip 相对精确的物理位置|
|http://www.ifconfig.io/ | my ip address |

---

## Development

#### 必备网站

|名称|属性|描述|
|:-------------:|--|-----|
|[regex101.com](https://regex101.com/)|regex|在线调试正则 支持php/javascript/python/golang. 代码生成器:直接生成多种语言代码java/golang等|
|[graphemica.com/](http://graphemica.com/)|characters|同一字符的各种编码情况下的表示 各种格式|

#### 其他网站
|名称|属性|描述|
|:-------------:|--|-----|
|https://httpbin.org/|http debug|A simple HTTP Request & Response Service.|

#### web应用开发-基础框架

|名称|属性|描述|
|:-------------:|--|-----|
|[Spring Framework](https://github.com/spring-projects/spring-framework)|Java|23k★ create enterprise applications in a wide range of scenarios and architectures. |
|[Spring Boot](https://github.com/spring-projects/spring-boot)|Java|28k★ Spring Boot makes it easy to create Spring-powered, production-grade applications and services with absolute minimum fuss. |
|[ThinkPHP5 Framework](https://github.com/top-think/framework)|php|1k★ 中文web应用开发框架  |
|[Vue.js](https://github.com/vuejs/vue)|js前端框架|112k★ A progressive, incrementally-adoptable JavaScript framework for building UI on the web.|


#### web前端

|名称|属性|描述|
|:-------------:|--|-----|
|[Quill Rich Text Editor](https://github.com/quilljs/quill)|富文本编辑器|19k★ 现代编辑器 专为兼容性和可扩展性而构建 安全好用  |
|[PDF.js](https://mozilla.github.io/pdf.js/)|pdf浏览|23k★ https://mozilla.github.io/pdf.js/|
|[clipboard.js](https://clipboardjs.com)|clipboard操作|23k★ Modern copy to clipboard. |

#### web系统

|名称|属性|描述|
|:-------------:|--|-----|
|[filebrowser](https://github.com/filebrowser/filebrowser)|云盘系统 Golang|3k★ A stylish web-based file manager|
|[nextcloud](https://github.com/nextcloud/server)|云盘系统 PHP|5k★ a safe home for all your data. 多客户端：web、ios、android |
|[gitea](https://github.com/go-gitea/gitea)|git系统 golang|9k★ 独立二进制包,无障碍开启self-hosted git service(自托管git服务). all platforms which Go supports!|

#### 学习项目
|名称|属性|描述|
|:-------------:|--|-----|
|[Project-Based-Tutorials-in-C](https://github.com/rby90/Project-Based-Tutorials-in-C)|C|2k★ C语言 基于项目的教程|

#### 知识

|名称|属性|描述|
|:-------------:|--|-----|
|[Java-Guide](https://github.com/Snailclimb/Java-Guide)|非代码|Java学习指南 一份涵盖大部分Java程序员所需要掌握的核心知识|
|[tensorflow_cookbook](https://github.com/nfmcclure/tensorflow_cookbook)|python #ML|3k★ Code for Tensorflow Machine Learning Cookbook |
|[Linux kernel map](http://www.makelinux.net/kernel_map/)|linux|linux内核学习 交互式操作 美国网站|
|[Annotated Nginx Source（中文）](https://github.com/chronolaw/annotated_nginx)|C web中间件|源代码学习 《Nginx完全开发指南》的作者 |


#### 其他工具

|名称|属性|运行环境|描述|
|:-------------:|--|--|-----|
|[transfer.sh](https://github.com/dutchcoders/transfer.sh)|golang|all|7k★ 命令行中上传文件`curl --upload-file ./1.txt https://yoursite.com/1.txt`|
|[MailHog](https://github.com/mailhog/MailHog)|golang|all|3k★ 仅供SMTP测试使用（基于Web和API） Mac下安装:`brew install mailhog`|

