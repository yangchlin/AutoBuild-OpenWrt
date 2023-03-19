# 自动生成OpenWrt

使用GitHub Actions构建OpenWrt固件 [Lean's OpenWrt](https://github.com/coolsnowwolf/lede)  
在此感谢 P3TERX 的脚本: https://github.com/P3TERX/Actions-OpenWrt/

## 用法

- 登录到 [GitHub Actions](https://github.com/features/actions/signup)
- Fork [此 GitHub repository](https://github.com/esirplayground/AutoBuild-OpenWrt)
- 单击 [.github/workflows] 文件夹 on the top of repo and you could see few workflow files, Each for one particular architecture(device).
- Edit the workflow file you desire，uncomment push section 3 lines together and submit the commit.(Other 2 methods wait you to discover)
- The build starts automatically. Progress can be viewed on the Actions page.
- When the build is complete, click the `Artifacts` button in the upper right corner of the Actions page to download the binaries.
- Default Web Admin IP: `192.168.5.1`, username `root`，password `password`

[For the details please visit my Y2B Channel (in Chinese) | 视频教程](https://www.youtube.com/c/esirplayground)
