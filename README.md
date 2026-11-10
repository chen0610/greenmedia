# greenmedia

公开的媒体投放仓库，用来放演示视频、开源项目 demo，以及临时分享的文件。

视频以 **GitHub Release** 附件发布，再用直接下载链接分享，例如：

https://github.com/chen0610/greenmedia/releases/download/v1/demo.mp4

## 不要把视频提交进 git

不要把体积较大的视频文件 `git add` / `git commit` 进仓库。请把它们发布为 Release 附件。`.gitignore` 已忽略常见视频格式，避免误提交。

## 如何发布

1. 打开本仓库页面
2. 进入 **Releases**
3. 点击 **Draft a new release**
4. 填写标签，例如 `v1`
5. 把 mp4 拖进 **Assets**
6. 点击 **Publish release**

## 如何获取分享链接

在 Release 页面，右键附件（例如 `demo.mp4`）→ **Copy link address**。链接形如：

https://github.com/chen0610/greenmedia/releases/download/<tag>/<filename>

## 大小限制

单个 Release 附件的上限是 **2 GB**。超过这个大小的文件无法作为 Release 附件上传。

## 已发布

- （暂无）
