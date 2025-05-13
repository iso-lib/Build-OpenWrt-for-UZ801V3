<p align="center"><img src="logo.png" /></p>
<h1 align="center">HandsomeMod 21.03</h1>

## 说明
- 移动网络没法使用
- 为高通410的随身WiFi UZ801V3编译OpenWrt。
- 固件仓库来自[HandsomeMod](https://github.com/HandsomeMod/HandsomeMod)
- 修复了一些下载错误与编译错误[HandsomeMod](https://github.com/LeeHe-gif/HandsomeMod)
- 使用本仓库的文件链接来安装依赖
## 使用方法
1. 点击右上角的fork按钮，复制一份代码到你自己的仓库
2. 确保你已经设置好了GITHUB_TOKEN
3. 如果你不需要其他功能请忽略本条。修改 .config 文件，添加自己需要的包，完成后保存
4. 打开 action 选项，点击左侧， Build OpenWrt 按钮 ，点击右侧 Run workflow 按钮，即开始编译，大概需要1到2小时左右的时间。
5. 编译完成的固件会在 releases 中发布。
