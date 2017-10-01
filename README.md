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
![示例1](http://www.weimiaotech.com/wordpress/wp-content/uploads/2017/10/示例1.jpg)
![示例2](http://www.weimiaotech.com/wordpress/wp-content/uploads/2017/10/示例2.jpg)
![示例3](http://www.weimiaotech.com/wordpress/wp-content/uploads/2017/10/示例3.jpg)
![示例4](http://www.weimiaotech.com/wordpress/wp-content/uploads/2017/10/示例4.jpg)
![示例5](http://www.weimiaotech.com/wordpress/wp-content/uploads/2017/10/示例5.jpg)
![示例6](http://www.weimiaotech.com/wordpress/wp-content/uploads/2017/10/示例6.jpg)

# 安装
## 资质材料
微信小程序要求社区、论坛类小程序需要有《增值电信业务经营许可证》或《电信与信息服务业务经营许可证》。

![安装1](http://www.weimiaotech.com/wordpress/wp-content/uploads/2017/10/安装1.png)

## 下载wmdz
下载解压wmdz（[http://www.weimiaotech.com/wordpress/](http://www.weimiaotech.com/wordpress/)），wmdz中包含wmapi和wmapp，其中wmapi是后端接口代码，需要部署到discuz服务器，wmapp是小程序代码，需要发布到小程序。

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

![安装2](http://www.weimiaotech.com/wordpress/wp-content/uploads/2017/10/安装2.png)


### 小程序配置发布
- 前往[https://mp.weixin.qq.com/debug/wxadoc/dev/devtools/download.html?t=1506754083](https://mp.weixin.qq.com/debug/wxadoc/dev/devtools/download.html?t=1506754083)，下载小程序开发者工具
- 打开小程序开发者工具，新建项目，项目路径为wmapp

- 修改app.js，修改svr_url为discuz的路径 

![安装3](http://www.weimiaotech.com/wordpress/wp-content/uploads/2017/10/安装3.png)

- 修改app.json，修改项目名称

![安装4](http://www.weimiaotech.com/wordpress/wp-content/uploads/2017/10/安装4.png)

- 上传小程序代码

![安装5](http://www.weimiaotech.com/wordpress/wp-content/uploads/2017/10/安装5.png)


- 前往【发布管理】，发布上线

![安装6](http://www.weimiaotech.com/wordpress/wp-content/uploads/2017/10/安装6.png)


# 打赏
如果觉得wmdz对您有用，请随意打赏。您的支持将鼓励我继续创作！

![打赏](http://www.weimiaotech.com/wordpress/wp-content/uploads/2017/10/打赏1.png)

# 讨论区
[http://www.weimiaotech.com/discuz/forum.php](http://www.weimiaotech.com/discuz/forum.php)


# 更多合作
- QQ：2733702796
- 微信：mmxingkong123
