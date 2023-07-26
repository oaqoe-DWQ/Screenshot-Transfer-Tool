# 图片传输工具

👀 这个工具会大大方便测试工程师备案和传输图片。

兼容测试的手机众多，怎么处理反复登陆的麻烦？只需一键操作，工具会自动创建备案文件夹，并把相关截图存进去。不再需要一个个登录微信或者QQ传输截图啦！

设计验收经常遇到的问题：图片被裁剪了，不是原图？？？工具会保留原始图片，不会对其进行压缩和裁剪。这样设计师才能准确对比UI界面，毕竟不能让压缩的图片搞乱了他们的审美眼。

BUG评审：我的图片跑哪里去了？？？传输后的图片将被长期保存，不会因为项目迭代而丢失。这样，后续的BUG评审就有依据了，测试工程师可以随时查看之前的截图，帮助找问题和做验证。

视频太大了，需要传输半天？这个工具也可以进行视频的传输。

## 工具原理

- 前端使用lay-ui框架
- 客户端使用pyqt5
- 后端使用（请填写）

引入这个工具后，测试工程师的工作会快人一步，备案和传输图片都能快速搞定！

## 使用方法

1. 解压安装包
2. 打开upload-file文件夹
3. 找到main.exe文件并点击打开
4. 设置自己的端口，也可以使用默认的端口，点击启动服务
5. 使用手机扫描二维码，苹果手机可使用相机扫码，安卓手机可使用浏览器扫码。请确保手机已连接公司的Wi-Fi。这样就可以进行原图传输了，图片尺寸与手机原尺寸一致。
6. 扫码后的界面如下所示。点击 "选择多文件" 按钮以选择要上传的图片，选择完成后点击 "开始上传" 按钮，图片将会上传到 "upload-file" 文件夹的 "recfiles" 目录中。

