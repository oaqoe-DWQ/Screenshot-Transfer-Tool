

# 图片传输工具

👀 这个工具会大大方便测试工程师备案和传输图片。

兼容测试的手机众多，怎么处理反复登陆的麻烦？只需一键操作，工具会自动创建备案文件夹，并把相关截图存进去。不再需要一个个登录微信或者QQ传输截图啦！

设计验收经常遇到的问题：图片被裁剪了，不是原图？？？工具会保留原始图片，不会对其进行压缩和裁剪。这样设计师才能准确对比UI界面，毕竟不能让压缩的图片搞乱了他们的审美眼。

BUG评审：我的图片跑哪里去了？？？传输后的图片将被长期保存，不会因为项目迭代而丢失。这样，后续的BUG评审就有依据了，测试工程师可以随时查看之前的截图，帮助找问题和做验证。

视频太大了，需要传输半天？这个工具也可以进行视频的传输。

## 工具


引入这个工具后，测试工程师的工作会快人一步，备案和传输图片都能快速搞定！

## 使用方法

1. 解压安装包
2. 打开upload-file文件夹
3. 找到main.exe文件并点击打开
4. 设置自己的端口，也可以使用默认的端口，点击启动服务
5. 使用手机扫描二维码，苹果手机可使用相机扫码，安卓手机可使用浏览器扫码。请确保手机已连接公司的Wi-Fi。这样就可以进行原图传输了，图片尺寸与手机原尺寸一致。
6. 扫码后的界面如下所示。点击 "选择多文件" 按钮以选择要上传的图片，选择完成后点击 "开始上传" 按钮，图片将会上传到 "upload-file" 文件夹的 "recfiles" 目录中。

# Image Transfer Tool

👀 This tool is designed to facilitate image sharing and archiving for testing engineers.

With compatibility across numerous devices, how can we streamline the process of repeatedly logging in? With just one click, this tool automatically creates a folder for archiving and stores relevant screenshots. No more need to log in to different messaging apps like WeChat or QQ to transfer images!

Design acceptance often encounters issues like cropped images not reflecting the original design. This tool preserves the original images without compression or cropping, enabling designers to accurately compare UI interfaces without compromising image quality.

Bug reviews sometimes face the problem of missing images. But fear not! Images transferred using this tool are saved long-term and won't be lost during project iterations. This provides a solid foundation for bug review, allowing testing engineers to easily access previous screenshots for issue identification and verification.

Is your video too large, taking forever to transfer? This tool also supports video transfer.

## Usage

1. Unzip the installation package.
2. Open the "upload-file" folder.
3. Locate and open the "main.exe" file.
4. Set your desired port, or use the default port, and click "Start Service".
5. Scan the QR code using your phone. For iPhone users, you can use the camera app to scan; for Android users, you can use a browser to scan. Please ensure that your phone is connected to the company's Wi-Fi. This will enable the transmission of original images, preserving the exact dimensions of the screenshots.
6. After scanning the QR code, the interface will appear as shown below. Click the "Select Multiple Files" button to choose the images you want to upload. Once the selection is complete, click the "Start Upload" button, and the images will be uploaded to the "recfiles" directory within the "upload-file" folder.
