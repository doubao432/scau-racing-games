# 更新日志

## 2026-09-21 首次在线发布准备

- 文件：zhuifeng.html、wushan.html、.nojekyll、README.md。
- 原因：将用户提供的两个独立 HTML 游戏发布到 GitHub Pages，提供各自游玩网址。
- 结果：保留原游戏玩法与资源；仅将两个版本共用的 localStorage 键改成各自专用名称，避免同域存档冲突；未增加外部资源或服务。
- 验证：两份来源文件完整保留；发布副本可逆替换存档键后与来源逐字符一致。发布状态以 GitHub Pages 部署记录为准。
- 后续：启用 main 分支根目录的 GitHub Pages，并验证线上访问与进入比赛。

## 2026-09-21 发布验收

- 发布账号：doubao432；仓库 scau-racing-games。GitHub Pages 使用 main 根目录并强制 HTTPS。
- 初次部署：Actions 35526330002 的 build、report-build-status、deploy 全部成功。
- 验证：两个正式游戏网址均返回 HTTP 200；线上 HTML 与发布副本内容一致（忽略 Git 换行转换）；浏览器实测两个版本均可进入比赛并显示三维赛道。
- 结果：两个游戏可通过 README 中各自网址直接访问，访客无需 GitHub 登录。
- 范围：完成发布烟雾验证，未进行全赛程通关或所有手机型号兼容性测试。原游戏保持单机运行。
