简要说明：

所有yaml文件默认配置icon图标，可下载后自行更改图标链接

一，clash-smart.yaml： 带故障转移的Smart智能策略组。

该策略组请使用Smart内核,否则无法运行

二，clash-block.yaml： 带故障转移的拒绝策略组。

该策略组无法在IOS系统的Stash应用中使用，因reject规则不被该应用支持，无法运行

Block分组为拒绝分组，目前只维护了Adobe相关域名

三，clash-fallback.yaml： 带故障转移的Url-test策略组。

该策略组Clash内核通用，建议使用该文件

四，节点订阅链接

机场订阅，订阅地址1/2/3/4名称不能重复,但可自定义修改

订阅链接1/2/3/4是用来写订阅链接的，下载后填入即可

五，分组

国外：国外分组默认走代理

国内：国内分组默认走直连

漏网之鱼：就是所有规则之外的，未被规则命中的域名或IP，默认走代理

请根据使用场景，在面板中自行选择

六、仅内核模式运行需要更改:

  #使用仅内核模式请自行修改yaml文件中以下选项为:true

device: utun
auto-route: false
auto-redirect: false
auto-detect-interface: false
strict-route: false
