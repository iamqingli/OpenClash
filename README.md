# OpenClash 完美配置

一、immortolwrt设置项：

网络-DHCP/DNS-常规设置项中，取消勾选DNS重定向，保存并应用。

![image](https://github.com/user-attachments/assets/f25cbf31-6112-43f2-a69f-079e3a702344)

二、OpenClash设置：

只修改给出的设置项，其他保持默认！！！

每设置完一个页面需要点一下保存，全部设置完后点保存并应用。

在保证网络通常情况下无法更新订阅时请打开Passwall等插件，在代理环境下重新更新订阅！！！

㈠ 插件设置：

1.先恢复为默认设置：

![image](https://github.com/user-attachments/assets/f369c293-7f3d-4aa2-97b8-592ce75e38af)

2.模式设置：选FakeIP增强模式：

![image](https://github.com/user-attachments/assets/8d97168d-8a05-4945-a0c4-d2b96b5d4ab5)

3.流量控制：选绕过中国大陆模式：

![image](https://github.com/user-attachments/assets/70498b2d-47b7-4af8-beff-d58b6916631f)

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

![image](https://github.com/user-attachments/assets/3ddb7443-3518-4ccd-8e10-736634f7b7c8)

复写设置DNS项设置

![image](https://github.com/user-attachments/assets/6487073e-25a7-4fd0-afaa-c66513854bbc)

复写设置Meta设置

![image](https://github.com/user-attachments/assets/b4f7729d-415b-4fa3-be51-cd998b9496dd)

复写设置规则设置：

![image](https://github.com/user-attachments/assets/67eeba49-b1b6-4ef0-b219-ca7112da2103)

自定义上游DNS服务器  重点！！！

1.NameServer只设置运营商提供的DNS，其他一个都不要选

![image](https://github.com/user-attachments/assets/1130bad0-42c8-4749-987e-006de2b432a1)

2.FallBack一个都不要选，默认走节点VPS设置的DNS

![image](https://github.com/user-attachments/assets/9f27784d-6218-4eff-b573-ac629c69d392)

3.Default-Nameserver一个都不要选

![image](https://github.com/user-attachments/assets/2ad8aa36-24ba-447a-9c82-6f2f1633b211)

㈢ 配置订阅设置：

1.默认选择clash.meta;2.勾选在线订阅转换服务；3.订阅转换服务器地址可选默认或自建转换地址；4.订阅转换模板选自定义

订阅转换模板自定义填写我的：

https://raw.githubusercontent.com/iamqingli/OpenClash/refs/heads/main/Clash-Full.ini

或是其他人的

也可在列表中选用Online Full模板

![image](https://github.com/user-attachments/assets/75ae2835-5188-44cc-9a5b-788d5223a0e2)

㈣ 更新并应用后返回运行状态页面，选择Yacd面板或其他面板根据自己需要进行节点选择：默认全部是直连。

![image](https://github.com/user-attachments/assets/85d658c4-225d-4f25-90b7-95190ad5f66d)
