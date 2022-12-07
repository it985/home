
### 个人主页

>这是我的个人主页

### 注

- 访问地址：[个人主页](http://trurun.top)
- 使用了 [一言](http://hitokoto.cn/) 的 API 服务
- ~~使用了 [Bing 壁纸 API](https://github.com/xCss/bing/) 服务~~
- ~~使用了 [Yahoo Query Language (YQL)](https://developer.yahoo.com/yql/) 来解决获取 Bing 壁纸跨域问题~~
- ~~原先 YQL 服务将被淘汰，现改用 [JsonBird](https://bird.ioliu.cn/)~~
- 使用 `GitHub Action` 来获取 Bing 壁纸，使用 `JSONP` 获取 Bing 壁纸 URL 文件

### GitHub Action 补充说明

- 利用 `Github Action` 提交代码需要一个 `GitHub API` 令牌, 可以在 [Create Tokens](https://github.com/settings/tokens) 这个地址，点击 `Generate new token` 按钮来创建
  - `Expiration` 过期时间设置为 `not expiration`
  - `Select scopes` 勾选 `repo`
  - 点击 `Generate Token` 生成
- 在仓库的 `Settings` ——>`Secrets` 功能栏中，点击 `new repository secrets` 按钮
  -  在 `Name` 框中填写 `GH_TOKEN`
  - 在 `Value` 栏中填写第一步生成的 `token` 值