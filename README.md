# 自动生成OpenWrt

使用GitHub Actions构建OpenWrt固件 [Lean's OpenWrt](https://github.com/coolsnowwolf/lede)  
在此感谢 P3TERX 的脚本: https://github.com/P3TERX/Actions-OpenWrt/

## 用法

- 登录到 [GitHub Actions](https://github.com/features/actions/signup)
- Fork [此 GitHub repository](https://github.com/esirplayground/AutoBuild-OpenWrt)
- 单击 [.github/workflows] 文件夹 on the top of repo and you could see few workflow files, Each for one particular architecture(device).
- Edit the workflow file you desire，uncomment push section 3 lines together and submit the commit.(Other 2 methods wait you to discover)
- The build starts automatically. Progress can be viewed on the Actions page.
- 构建完成后，单击Actions页面右上角的“Artifacts”按钮下载编译好的文件。
- 默认Web管理 IP: `192.168.5.1`, 用户名 `root`，密码 `password`

[For the details please visit my Y2B Channel (in Chinese) | 视频教程](https://www.youtube.com/c/esirplayground)
