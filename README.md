# Chrome PUT 拦截器

一个 Chrome 扩展，用于在请求发出前拦截所有网站的 HTTP/HTTPS `PUT` 请求。适用于 Chrome 91 及以上版本。

## 安装

1. 下载或克隆本仓库。下载 ZIP 时先解压。
2. 在 Chrome 打开 `chrome://extensions`，开启右上角的 **开发者模式**。
3. 点击 **加载未打包的扩展程序**，选择包含 `manifest.json` 的目录。

## 使用

扩展加载后立即生效。规则只匹配 `PUT`，依赖 `PUT` 的保存或上传操作会失败。要暂停拦截，在 `chrome://extensions` 关闭 **拦截所有 PUT 请求** 的开关。
