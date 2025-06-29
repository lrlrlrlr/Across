# AcrossTheWall
最后更新: 2025/06/29
如何搭梯子(一键脚本)

# 目的:   
  - 自己搭建梯子, 翻墙浏览网页

# 特点:
  - 无需会编程, 有鼠标键盘就能自己搭建梯子
  - 自己搭建的梯子更安全, 更稳定, 价格低廉
  - 全程只需要5分钟, 一键脚本快速搭建无需复杂设置!

# 翻墙原理简述
 ![image](https://user-images.githubusercontent.com/27357380/222922751-9e07dd0b-fc38-4e44-b140-773f75e67de0.png)


# 前置条件:
  - 电脑一台, Windows和Mac系统均可;
  - 需要使用到的软件:
    - 浏览器(Chrome, Firefox 等等)
    - Trojan-Qt5: 翻墙插件
    - 需要一定英文基础(或者使用翻译插件)


# 步骤
1. 请配合视频《五分钟学会自己搭梯子翻墙》 https://youtu.be/LPOY6YvLar0 
1. 购买海外云服务虚拟机(VPS);
1. 注册域名并配置DNS;
1. 配置云服务器; 
1. 使用Trojan-Qt5插件连接云服务器, 翻墙完成!


# 详细步骤
1. 购买海外云服务虚拟机(VPS);
   - 使用我的邀请链接可以免费获得$100体验金: https://www.vultr.com/?ref=8952730-8H 
   - 注册好之后创建云服务器VPS, 推荐选择美国硅谷或者日本东京的服务器
   - 生成好云服务器后,保留好**IP地址**/登录用户名/密码备用

1. 购买域名
   - 可以使用阿里云/腾讯云/NameCheap等网站购买域名, 学生用户可免费获得域名.
   - 购买域名成功后进入**DNS设置页面**, 填入上一步注册的**云服务器的IP地址**.
     ![image](https://github.com/user-attachments/assets/06137fd2-9895-48a4-9262-f58d0d29557a)


1. 配置云服务器; 
  - 在云服务器上面安装Trojan web管理面板，一键安装:

      ```
      wget -N --no-check-certificate "https://raw.githubusercontent.com/V2RaySSR/Trojan_panel_web/master/trojan-web-panel.sh" && chmod +x trojan-web-panel.sh && ./trojan-web-panel.sh
      ```
4. 使用Trojan-Qt5插件连接云服务器, 翻墙完成!
