# Interactive Birthday Letter

一个单页交互式生日祝福网页，采用深色背景与暖金色视觉体系，强调“实体入口 → 网页启封 → 阅读 → 互动 → 结尾”的完整体验。

## Features

- 沉浸式启封封面与滚动阅读结构
- 响应式布局，适配手机与桌面浏览器
- 星点、滚动渐入与烟花动效
- `prefers-reduced-motion` 动效降级支持
- Web Audio 氛围音乐，默认自动播放
- 生日签随机互动与许愿蜡烛
- Web Share / 链接复制
- 访问二维码生成与 PNG 保存
- 基础无障碍优化：键盘焦点、Dialog 语义、Escape 关闭、ARIA 状态
- `noindex,nofollow,noarchive`，降低被搜索引擎收录的概率

## Files

- `index_best.html`：完整页面，可直接作为站点入口使用
- `README.md`：项目说明

## Deployment

可部署到任意静态托管服务。部署后请确认最终访问地址稳定，再将该地址用于实体二维码或分享。


## Notes

- 页面主体无需构建工具，直接使用 HTML / CSS / JavaScript。
- 二维码功能通过外部 QRCode.js 加载；即使该资源加载失败，其余页面仍可正常使用。
- 氛围音乐使用 Web Audio API 生成，不依赖音频文件。
- 建议至少在 iPhone Safari、Android/微信内置浏览器和桌面浏览器各测试一次。
- README 仅记录项目实现信息，不记录收件人、制作者或双方关系等个人内容。
