# DecHex 法务页面（GitHub Pages 用）

两个静态页面，无外部依赖、自适应深色模式：

- `index.html` —— 技术支持页
- `privacy.html` —— 隐私政策

> 联系邮箱已填好：`232235382@qq.com`（每个页面 2 处：可见文字 + mailto 链接）。要换邮箱就全局替换这个地址。

## 发布到 GitHub Pages

1. 登录 GitHub → 右上角 **+** → **New repository**
2. 仓库名填 `dechex-site`，可见性选 **Public**（私有仓库用不了免费 Pages），点 **Create repository**
3. 在新仓库页面点 **uploading an existing file**，把 `index.html` 和 `privacy.html` 拖进去 → **Commit changes**
4. 仓库 **Settings** → 左侧 **Pages**
5. **Source** 选 `Deploy from a branch`，**Branch** 选 `main` + `/ (root)`，点 **Save**
6. 等 1~2 分钟，页面顶部会出现网址：`https://tranjazz.github.io/dechex-site/`

## 填到 App Store Connect

| 字段 | 填 |
|---|---|
| 隐私政策 URL | `https://tranjazz.github.io/dechex-site/privacy.html` |
| 技术支持 URL | `https://tranjazz.github.io/dechex-site/` |

## 注意

- 仓库必须是 **Public**，否则 Pages 需要付费计划
- 页面不能要求登录，必须能匿名访问（GitHub Pages 默认满足）
- 自动提供 HTTPS，符合 App Store 要求
- 以后改了内容，重新上传文件即可，Pages 会自动重新部署（约 1 分钟）
