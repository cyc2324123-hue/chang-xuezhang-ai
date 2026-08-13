# 常学长AI V2.7正式版｜GitHub Pages公开发布包

这是从开发工程中独立整理出的公开网站包，只包含网站运行必需的页面、样式和公开图片。

## 目录说明

```text
GitHub_Pages_公开发布包/
├─ README.md                 当前说明
├─ 发布与更新说明.md          面向非技术使用者的操作说明
└─ docs/                     GitHub Pages唯一发布目录
   ├─ index.html             网站入口
   ├─ .nojekyll              让GitHub直接发布静态文件
   ├─ app/globals.css        页面视觉与动效
   └─ public/                头像、分享封面、校园照片和功能图标
```

## 公开边界

本目录不包含：启动包、内部指令、开发脚本、作品集原稿、个人协作资料、API密钥、数据库、日志或托管凭据。

## 发布方式

GitHub仓库设置为公开后，在 `Settings → Pages` 选择：

- Source：Deploy from a branch
- Branch：main
- Folder：/docs

以后只需要更新 `docs` 目录并推送，公开网址会自动刷新。
