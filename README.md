# 功能
## 功能列表
- 查看帖子列表
- 查看帖子详情
- 查看版块
- 注册登录
- 热门精华
- 发帖
- 回复
- 我的帖子
- 我的回复

## 功能示例
![示例1](http://a2.qpic.cn/psb?/V13OOk0c1xiW63/.8siLMxSrjE4S1JTWAFq2D1URxukj2b5YpJc609no18!/m/dPkAAAAAAAAAnull&bo=gAJyBAAAAAARB8Q!&rf=photolist&t=5)
![示例2](http://a2.qpic.cn/psb?/V13OOk0c1xiW63/LNE*OcU5CUyuuCtB02vRoAgkOfMCc9MP34Cj1OtMFVY!/m/dAEBAAAAAAAAnull&bo=gAJyBAAAAAARB8Q!&rf=photolist&t=5)
![示例3](http://a3.qpic.cn/psb?/V13OOk0c1xiW63/qEYWnjz3rpk7ztCSRdFCou6*0b9fV0b97StNAzSEhLk!/m/dEIAAAAAAAAAnull&bo=gAJyBAAAAAARB8Q!&rf=photolist&t=5)
![示例4](http://a3.qpic.cn/psb?/V13OOk0c1xiW63/S64GhVJIj.oZX0zYvFDhRMCy.fxumWYTczj1ICTXWtI!/m/dEIAAAAAAAAAnull&bo=gAJyBAAAAAARB8Q!&rf=photolist&t=5)
![示例5](http://a2.qpic.cn/psb?/V13OOk0c1xiW63/EKTGAkV4zYXr65Vjj30nEE*eVJBJikASu7un6ViPpS8!/m/dMkAAAAAAAAAnull&bo=gAJyBAAAAAARB8Q!&rf=photolist&t=5)
![示例6](http://a3.qpic.cn/psb?/V13OOk0c1xiW63/Xr4dq1slIeyORcSmgwQ0Va*a4o6Gvcc3dgzvgFU9r1o!/m/dEIAAAAAAAAAnull&bo=gAJyBAAAAAARB8Q!&rf=photolist&t=5)
 
# 安装
## 资质材料
微信小程序要求社区、论坛类小程序需要有《增值电信业务经营许可证》或《电信与信息服务业务经营许可证》。

![安装1](http://a3.qpic.cn/psb?/V13OOk0c1xiW63/7yoDs0k3.cIdkU.jXmfqBKa3FVSXvxXkWh9OjOsIVI4!/m/dJYAAAAAAAAAnull&bo=RQWAAgAAAAADB.A!&rf=photolist&t=5)
 
## 下载wmdz
下载解压wmdz（[http://www.weimiaotech.com/discuz/data/download/wmdz_v1.zip](http://www.weimiaotech.com/discuz/data/download/wmdz_v1.zip)），wmdz中包含wmapi和wmapp，其中wmapi是后端接口代码，需要部署到discuz服务器，wmapp是小程序代码，需要发布到小程序。

## 配置安装
### 小程序申请与设置
- 前往[https://mp.weixin.qq.com/wxopen/waregister?action=step1](https://mp.weixin.qq.com/wxopen/waregister?action=step1)，注册小程序。
- 登录小程序，前往【设置】—>【基本设置】，配置小程序名称、小程序头像、介绍等信息。
- 前往【设置】—>【开发设置】，获取小程序appid、appsecret，配置小程序服务器域名。

### discuz服务器安装配置
- 将wmapi复制到服务器上discuz的目录下
- 修改data目录和wmapi_config.php的权限
cd wmapi
chmod 777 data
chmod 777 wmapi_config.php
- 打开安装脚本http://path_to_discuz/wmapi/wmapi_install.php，添加appid、appsecret，开始安装。

![安装2](http://a4.qpic.cn/psb?/V13OOk0c1xiW63/6zMD8lJwtuHZE*MQIpa5z463I9flQ9w0I5QDeaQXeOA!/m/dPcAAAAAAAAAnull&bo=QAMiAQAAAAADB0I!&rf=photolist&t=5)
 

### 小程序配置发布
- 前往[https://mp.weixin.qq.com/debug/wxadoc/dev/devtools/download.html?t=1506754083](https://mp.weixin.qq.com/debug/wxadoc/dev/devtools/download.html?t=1506754083)，下载小程序开发者工具
- 打开小程序开发者工具，新建项目，项目路径为wmapp

- 修改app.js，修改svr_url为discuz的路径 

![安装3](http://a3.qpic.cn/psb?/V13OOk0c1xiW63/DQP1.osfxfdIFkIEQgG4akxYQT4BmbV94HBmQkrwIvU!/m/dEIAAAAAAAAAnull&bo=bAPrAAAAAAADB6Y!&rf=photolist&t=5)

- 修改app.json，修改项目名称

![安装4](http://a2.qpic.cn/psb?/V13OOk0c1xiW63/iKm34*aG7SWLil8u*VYC5I9IfucWRRh6Yc*HWjZrVVg!/m/dAEBAAAAAAAAnull&bo=*gLtAAAAAAADBzM!&rf=photolist&t=5)

- 上传小程序代码

![安装5](http://a2.qpic.cn/psb?/V13OOk0c1xiW63/R0haUjd.HfE6gpZV9tdfHWAjwTGEEoJRBJABG8XRblQ!/m/dAEBAAAAAAAAnull&bo=YwNbAQAAAAADBxg!&rf=photolist&t=5)


- 前往【发布管理】，发布上线

![安装6](http://a3.qpic.cn/psb?/V13OOk0c1xiW63/iVSzXeaYsR5EPUXBuXqtIDcjJ.3444YaiartRHBzD7Y!/m/dEIAAAAAAAAAnull&bo=UgUWAQAAAAADB2I!&rf=photolist&t=5)
 

# 打赏
如果觉得wmdz对您有用，请随意打赏。您的支持将鼓励我继续创作！

![打赏](http://a4.qpic.cn/psb?/V13OOk0c1xiW63/XqTp4KhSv*7KnpseaO4iO3g4XEa0Xv9ZhpTCyHiL.BU!/m/dPcAAAAAAAAAnull&bo=sAC0AAAAAAADByY!&rf=photolist&t=5)

# 讨论区
[http://www.weimiaotech.com/discuz/forum.php](http://www.weimiaotech.com/discuz/forum.php)


# 更多合作
- QQ：2733702796
- 微信：mmxingkong123
