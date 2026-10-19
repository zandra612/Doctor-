# Doctor白作品网站

这是可独立部署的静态网页，保留原页面、角色素材及 Mac 安装包下载。

## Vercel 设置

- Framework Preset：Other
- Root Directory：./（上传本目录内容作为仓库根目录）
- Build Command：留空；不需要构建
- Output Directory：.（仓库根目录；若自动识别正常可保持默认）
- Install Command：留空；无依赖需要安装
- Environment Variables：不需要

GitHub 仓库可以设为 Private，网站是否公开由 Vercel 的部署访问设置决定。
上传本目录中的文件和子文件夹，保持 assets/ 和 downloads/ 层级；不要只上传压缩包。

## 本地预览

在本目录运行 `python3 -m http.server 8765`，浏览器访问 http://127.0.0.1:8765。

## 上线验收

1. 用项目的生产环境默认网址打开首页，确认无需登录即可访问。
2. 检查角色素材、导航锚点、使用说明和两个下载按钮。
3. 下载 DMG 并核对 SHA-256 文件中的值。安装包未取得苹果公证，页面已说明。
4. 此网站提供介绍和下载安装包；桌面应用运行在 Mac 上，网页没有在线聊天后端。
5. 反馈区当前为禁用状态，尚不支持提交。

本目录不包含桌宠源码、设计草稿、API Key 或网站原发布平台配置。
