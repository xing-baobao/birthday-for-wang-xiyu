# 致王希羽 · 生辰星礼

这是一个纯静态生日祝福网页，默认内容为：

- 祝福人：赵金星
- 生日对象：王希羽
- 风格：深色香槟金 / 高级感 / 星空仪式感
- 功能：开场启封、艺术字姓名、原创氛围旋律、交互许愿、烟花、网页分享、二维码生成与 PNG 保存
- 部署目标：GitHub Pages

## GitHub Pages 部署（网页操作版）

### 1. 创建 GitHub 仓库
登录 GitHub 后点击右上角 `+` → `New repository`。

推荐仓库名：

`birthday-for-wang-xiyu`

如果你使用 GitHub 免费账户，请把仓库设为 `Public`，然后创建仓库。

### 2. 上传文件
进入刚创建的仓库：

`Add file` → `Upload files`

把这个压缩包解压后的以下文件上传：

- `index.html`
- `.nojekyll`

然后点击 `Commit changes`。

> `README.md` 可以一起上传，也可以不上传。

### 3. 开启 GitHub Pages
进入仓库：

`Settings` → 左侧 `Pages`

在 `Build and deployment` 中：

- `Source` 选择 `Deploy from a branch`
- `Branch` 选择 `main`
- 文件夹选择 `/(root)`
- 点击 `Save`

稍等片刻后，GitHub 会显示你的网站地址。

通常是：

`https://你的GitHub用户名.github.io/birthday-for-wang-xiyu/`

### 4. 打开网页并生成二维码
先打开上面 GitHub Pages 的公网地址。

滚动到页面最后，点击：

`生成永久二维码`

此时二维码编码的是 GitHub Pages 公网地址。

点击：

`保存二维码 PNG`

就可以把 PNG 发给王希羽，或者打印到贺卡上。

## 二维码会不会过期？

二维码图片本身没有过期时间，它只是保存了一个网址。

只要以下条件持续成立，二维码就可以一直使用：

1. GitHub Pages 页面仍然存在；
2. 不删除这个仓库；
3. 不关闭 Pages；
4. 不修改 GitHub 用户名或仓库名（否则默认网址会变化）。

因此，不要使用会过期的短链接或第三方动态二维码服务，直接把 GitHub Pages 的正式网址做成二维码即可。

## 一个小建议

如果你希望这个二维码很多年以后仍保持原地址，部署后尽量不要：

- 重命名 GitHub 账号；
- 重命名仓库；
- 删除仓库；
- 更换 Pages 发布路径。

GitHub Pages 的默认 `github.io` 地址本身不需要购买域名或每年续费。
