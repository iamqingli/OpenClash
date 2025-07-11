# OpenClash 旁路由配置

一、immortolwrt设置项：

网络-DHCP/DNS-常规设置项中，取消勾选DNS重定向，保存并应用。

<img width="1026" height="473" alt="image" src="https://github.com/user-attachments/assets/8f4a4647-3e98-4c69-b4be-455243248280" />

二、OpenClash设置：

只修改给出的设置项，其他保持默认！！！

每设置完一个页面需要点一下保存，全部设置完后点保存并应用。

在保证网络通畅情况下，如无法更新订阅请打开科学上网插件，在科学环境下重新更新订阅配置！！！

㈠ 插件设置：

1.还原默认配置：

![image](https://github.com/user-attachments/assets/f369c293-7f3d-4aa2-97b8-592ce75e38af)

2.模式设置：选FakeIP增强模式：

<img width="1126" height="603" alt="image" src="https://github.com/user-attachments/assets/8f1fc668-aaf4-4dd3-84b5-becc16ab5e07" />

3.流量控制：选绕过中国大陆模式：

<img width="1122" height="519" alt="image" src="https://github.com/user-attachments/assets/53f5cc79-b188-4291-866a-ac51f6118643" />

4.DNS设置：选DNSmasq转发或防火墙转发：

![image](https://github.com/user-attachments/assets/2db2a626-ef5f-47ac-908c-e189190db6a1)

5.IPV6设置：使用IPV6只勾选允许IPv6类型DNS解析，不使用IPV6不勾选。代理模式不建议使用。

![image](https://github.com/user-attachments/assets/39f920cc-20e2-4a04-a7f0-55e6b4de4a6c)

6.规则订阅强烈建议开启并设置自动更新：

![image](https://github.com/user-attachments/assets/c839ed74-8edd-4699-9ace-ef8fb923c978)

![image](https://github.com/user-attachments/assets/793fa2bc-d820-4999-a31b-7364c1d1b63d)

![image](https://github.com/user-attachments/assets/21ba1b49-7658-4fd8-a839-4a91a8526468)

![image](https://github.com/user-attachments/assets/cbfbb2e3-e502-41de-9b71-a732a0a72a5a)

㈡ 复写设置：

复写设置常规项设置：

<img width="830" height="571" alt="image" src="https://github.com/user-attachments/assets/21ceaf9e-970a-4220-bbf2-d1dd80a5b29e" />

复写设置DNS项设置

<img width="838" height="604" alt="image" src="https://github.com/user-attachments/assets/eebb001a-9a91-46fb-811e-2a0d19af344d" />

复写设置Meta设置

<img width="929" height="564" alt="image" src="https://github.com/user-attachments/assets/e65aaad1-9d3a-4fda-836d-031f3a5cf916" />

复写设置规则设置：

<img width="819" height="270" alt="image" src="https://github.com/user-attachments/assets/19c81865-76fa-4631-9c7b-b7af1f2cbb6c" />

自定义上游DNS服务器  重点！！！

1.NameServer只设置运营商提供的DNS，其他一个都不要选。我的上游DNS服务是Adguard Home，只用来缓存国内域名解析，未配置去广告规则，也不建议添加去广告规则。

![image](https://github.com/user-attachments/assets/1130bad0-42c8-4749-987e-006de2b432a1)

2.FallBack一个都不要选，默认走节点VPS设置的DNS。

![image](https://github.com/user-attachments/assets/9f27784d-6218-4eff-b573-ac629c69d392)

3.Default-Nameserver一个都不要选。

![image](https://github.com/user-attachments/assets/2ad8aa36-24ba-447a-9c82-6f2f1633b211)

㈢ 配置订阅设置：

1.默认选择clash.meta;2.勾选在线订阅转换服务；3.订阅转换服务器地址可选默认或自建转换地址；4.订阅转换模板选自定义

订阅转换模板自定义填写：

https://raw.githubusercontent.com/iamqingli/OpenClash/refs/heads/main/Clash-Full.ini

也可在列表中选用Online Full模板

![image](https://github.com/user-attachments/assets/75ae2835-5188-44cc-9a5b-788d5223a0e2)

㈣ 更新并应用后返回运行状态页面，选择Zashboard面板或其他面板根据自己需要进行节点选择。

<img width="1116" height="597" alt="image" src="https://github.com/user-attachments/assets/f02af922-180e-47e8-bf8d-2d4384fd382d" />

㈤强烈建议使用yaml文件！！！
