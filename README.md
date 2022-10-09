<p align="center">
  <a href="https://github.com/MuXia-0326/YunzaiBotJsPluginMuXia">
    <img width="200" src="readme/project_logo.png">
  </a>
</p>

<h1 align="center">MuXia-js-plugin</h1>

<div align="center">

上图来自画师[ｍｅｍｅｎｏ](https://www.pixiv.net/users/62635184)，强烈安利

此项目依赖于[YunzaiBot](https://github.com/Le-niao/Yunzai-Bot)

[![访问量](https://profile-counter.glitch.me/MuXia-js-plugin/count.svg)](https://github.com/MuXia-0326/YunzaiBotJsPluginMuXia)

</div>

<div align="center">

### 如果觉得本项目好用，点一个 star 吧

</div>

# 插件列表

| 插件名称       | 支持 v2 | 支持 v3 | 备注 |
| -------------- | ------- | ------- | ---- |
| 今日日报       |         | ✔       |      |
| 撤回机器人消息 |         | ✔       |      |
| 热搜榜         |         | ✔       |      |
| 自动复读       |         | ✔       |      |
| 速速挨打       |         | ✔       |      |
| 不可以打人     |         | ✔       |      |
| 禁言套餐       |         | ✔       |      |

## 使用指南

将 js 文件复制到`..\Yunzai-Bot\plugins\example`目录下，将 img 下的文件复制到`..\Yunzai-Bot\resources\img`目录下，没有 img 目录新建一个

### 撤回机器人消息

回复 Bot 的消息，并携带撤回，即可

![](readme/help_img_6.png)

### 热搜榜

![](readme/help_img_7.png)

![](readme/help_img_8.png)

### 自动复读

根据群内发送的**单文字**或者**单表情**进行跟随复读操作,阈值为 3，可自行更改

![](readme/help_img_9.png)

### 今日日报 cookie 获取教程

1. 访问[微信公众号](https://mp.weixin.qq.com/)官网

    ![](readme/help_img_1.png)

2. 按 f12 打开浏览器控制台,点击 Network

    ![](readme/help_img_2.png)

3. 登录微信账号
   登录成功后，在 network 页面找到下图标注的请求，点击

    ![](readme/help_img_3.png)

4. 找到 cookie 选项，右键 copy value

    ![](readme/help_img_4.png)

5. 粘贴到`my_plugin_get_day_news.js`插件的图示位置

    ![](readme/help_img_5.png)

## 更新日志

-   2022-10-08 今日日报添加定时触发，优化部分提示异常，新增**撤回机器人消息**插件
-   2022-10-09 新增**热搜榜**和**自动复读**插件

## 其他

-   [Yunzai-Bot](https://github.com/Le-niao/Yunzai-Bot)
-   Yunzai-Bot 插件库：[☞github](https://github.com/yhArcadia/Yunzai-Bot-plugins-index) [☞gitee](https://gitee.com/yhArcadia/Yunzai-Bot-plugins-index)
