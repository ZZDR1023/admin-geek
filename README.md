# Issue #238 验收证据

比赛应用与比赛管理页面的改前 / 改后截图，供 PR 引用。这些图是临时证据，
合并后可删。

- `before-*`：改动前的 `origin/stage`（4d1bdef），桌面与手机上都没有「比赛」入口。
- `after-desktop-competitions-1440x900.png`：桌面开「比赛」窗口（开发样板数据）。
- `after-desktop-real-api-1440x900.png`：同一窗口在 `?__data=live` 下渲染**真实服务**的响应。
- `after-phone-competitions-390x844.png`：手机主屏幕打开「比赛」。
- `after-console-list-*.png`：控制台「比赛」列表（1440×900 / 1280×800）。
- `after-console-form-1440x900.png`：控制台新建比赛表单（日期是原生 date 输入）。

截图命令：Playwright（Chromium），视口见文件名；样例见任务 #238 的执行记录。
