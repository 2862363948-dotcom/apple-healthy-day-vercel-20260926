# 苹果健康一天：Vercel 云端渲染

这个目录基于官方 HyperFrames Vercel 模板，已经完成：

- 组合路径：`public/compositions/apple-healthy-day/`
- 竖屏尺寸：`1080 × 1920`
- 预览与渲染目录：`lib/preview.ts`
- 页面播放器尺寸：`app/page.tsx`

## 部署

1. 将整个目录上传到 GitHub 新仓库。
2. 打开 https://vercel.com/，选择 `Add New Project`。
3. 选择这个 GitHub 仓库并点击 `Deploy`。
4. 部署完成后打开网站，点击页面上的 `Render`。
5. 等待云端渲染完成，页面会返回 MP4 下载链接。

Vercel 云端会负责运行 Chromium、HyperFrames 和 FFmpeg，本机无需安装 FFmpeg。
