简要说明：

所有yaml文件默认配置icon图标，可下载后自行更改图标链接

DNS地址可根据自身需要进行更改

一，Clash-Reject.yaml： 

#带故障转移的拒绝策略组，默认优先使用此yaml文件，若某些客户端报错，请选择使用Clash-Stash.yaml文件。

#该策略组无法在IOS系统的Stash应用中使用，因reject规则不被该应用支持，无法运行

#Block分组带拒绝访问分组，包含部分域名，如：Adobe

二，Clash-Smart.yaml： 

#带故障转移的Smart智能策略组。

#该策略组请使用Smart内核,否则无法运行

三，Clash-Stash.yaml： 

#带故障转移的Url-test策略组，IOS客户端Stash软件专用。

四，AppleTV-Stash.yaml： 

#带故障转移的Url-test策略组，AppleTV客户端Stash软件专用（客户端版本低于IOS端）。

该策略组Clash内核通用

五，节点订阅链接

机场订阅，订阅地址1/2/3名称不能重复,但可自定义修改

订阅链接1/2/3是用来写订阅链接的，下载后填入即可

六，分组

国外：国外分组默认走代理

国内：国内分组默认走直连

漏网之鱼：所有规则之外的，未被规则命中的域名或IP，默认走代理

请根据使用场景，在面板中自行选择

七、仅内核模式运行需要更改:
  
  1.使用nikki，混入全部不修改的情况，请修改开启接口device指定为nikki
  
  2.使用仅内核自行修改下面三项为true，路由控制、使用GUI客户端请保持 false，纯内核命令行运行改为 true
  
  auto-route: false
  
  auto-redirect: false
  
  auto-detect-interface: false
  
  3.控制面板:
  
  密码默认设置为空，请自行修改
  
  面板地址可更换：https://github.com/MetaCubeX/metacubexd/archive/refs/heads/gh-pages.zip
  
  避免桌面gui客户端冲突，默认保持注释，Nikki可取消注释使用
  
