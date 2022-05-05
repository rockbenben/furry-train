# 互联网小白

---start---
## 目录(2022年05月05日更新)
[Jekyll 博客迁移－从 Markdown 到 WordPress](https://newzone.top/p/2021-01-27-Blog_Jekyll_to_WordPress/)

[最后一个密码管理器－KeePass](https://newzone.top/p/2021-01-02-KeePass_the_real_lastpassword/)

[减肥日志：4 周 15 斤](https://newzone.top/p/2020-12-17-Weight_log/)

[小狼毫 3 分钟入门及进阶指南](https://newzone.top/p/2020-11-27-RIME_input/)

[这些全网卖爆的“必备”品，我劝你别买……](https://newzone.top/p/2020-11-01-Gym_equipment_throw_away/)

[真·DPC_WATCHDOG_VIOLATION 蓝屏解决方案](https://newzone.top/p/2020-10-25-DPC_WATCHDOG_VIOLATION/)

[无线路由调整，加快 WIFI 速度](https://newzone.top/p/2020-09-13-WIFI_speed_up/)

[RSS 速成篇 2：RSSHub 自部署](https://newzone.top/p/2020-03-25-RSSHub_on_vps/)

[这些「医院护肤品」你买了吗？](https://newzone.top/p/2019-10-04-Fake_AKA_hospital_skin_care_products/)

[scrcpy - 手机无线投屏到电脑](https://newzone.top/p/2019-08-26-Scrcpy_screen_projection/)

[RSS 速成篇：RSSHub 捡现成的轮子](https://newzone.top/p/2019-04-01-RSSHub_noob/)

[OpenVPN 随时随地回家的路](https://newzone.top/p/2019-03-31-OpenVPN_back_to_home/)

[加速打字，PC 端的语音输入方案](https://newzone.top/p/2018-12-28-Voice_input_try/)

[RSS 进阶篇：Huginn - 真·为任意网页定制 RSS 源（PhantomJs 抓取）](https://newzone.top/p/2018-10-07-Huginn_scraping_any_website/)

[客厅、书房、卧室，任意收看 IPTV 直播！（上海电信）](https://newzone.top/p/2018-06-19-IPTV_direckly/)

[koolproxy 无法下载 https 证书？](https://newzone.top/p/2018-06-10-koolproxy_https/)

[光猫改造 篇三：百卓 GP1700 进阶设置 - 端口映射](https://newzone.top/p/2018-06-08-Baizhuo_GP1700/)

[真· Airtable 3 分钟菜鸟入门](https://newzone.top/p/2018-05-24-Airtable_noob/)

[抛弃迅雷，Aria2 新手入门](https://newzone.top/p/2018-05-15-Aria2_a_new_download_tool-/)

[怎么用 Adobe Audition 快速剪切音频？](https://newzone.top/p/2018-05-04-Audition_cut_mp3/)

[Jekyll 扩展篇：服务器搭建 Jekyll 博客](https://newzone.top/p/2018-05-02-Jekyll_blog_on_vps/)

[Jekyll 篇一：3 分钟搭建 Github Pages 博客](https://newzone.top/p/2018-05-01-Jekyll_blog_on_github_pages/)

[新手建站神器 - 宝塔面板](https://newzone.top/p/2018-04-30-BaoTa_deploy_vps/)

[提早晚餐，饿死算逑](https://newzone.top/p/2018-03-06-No_more_dinner/)

[雇个机器人帮你干活](https://newzone.top/p/2018-01-31-Hire_a_robot/)

[小型网站管理员，快放弃 CDN！](https://newzone.top/p/2018-01-19-Forget_the_cdn/)

[怎么用 MarkDown 写博客](https://newzone.top/p/2018-01-07-Original_blog/)

---end---

网站基于[WordPressXMLRPCTools](https://github.com/zhaoolee/WordPressXMLRPCTools)，能用 Markdown 生成博客，push 更新到 Github 后，Github Actions 自动将文章更新到 WordPress，并将 WordPres 站的文章索引更新到 Github 仓库的 README.md，供搜索引擎收录。

## 常见问题

1. 无法启动 github action，显示 git denied to github-actions[bot] 和 Process completed with exit code 128.

Setting - Code and automation - Actions - General, Workflow permissions 中开启「Read and write permissions」。

2. _post 中添加了文档，但并未在 README 中显示

文档后缀必须为「.md」，不支持 .markdown。
