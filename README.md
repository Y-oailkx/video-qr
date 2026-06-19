# 视频二维码落地页

这是用于 GitHub Pages 的稳定中转页。

## 当前跳转目标

https://weixin.qq.com/sph/AokStIsJb5

## 部署方式

1. 新建一个 GitHub 仓库，例如：`video-qr`
2. 上传本目录里的 `index.html` 和 `.nojekyll`
3. 进入仓库 `Settings` → `Pages`
4. `Build and deployment` 选择：
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
5. 保存后等待 GitHub Pages 发布

发布后的地址通常是：

```text
https://你的GitHub用户名.github.io/仓库名/
```

拿到这个地址后，再把这个地址生成二维码。
以后要换视频，只需要改 `index.html` 里的目标链接，二维码不用换。
