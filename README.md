
# Cyber Matrix Screensaver Pack

## 内容
- 2 首原创赛博安全诗歌
- 2 个动态 Matrix 风格屏保（HTML5 Canvas）
- 2 个静态 1920x1080 壁纸（PNG）

## 文件
- poem1.txt
- poem2.txt
- matrix_screensaver_1.html
- matrix_screensaver_2.html
- wallpaper_1.png
- wallpaper_2.png

## macOS 使用说明

### 动态屏保
方法1：浏览器全屏
1. 使用 Safari / Chrome 打开 HTML 文件
2. 按 F 键进入全屏
3. 可配合:
   - Safari -> 文件 -> 添加到 Dock
   - 或使用 Electron / Nativefier 打包

方法2：WebViewScreenSaver
推荐项目：
https://github.com/liquidx/webviewscreensaver

安装后:
~/Library/Screen Savers/

将生成的 .saver 放入以上目录。

系统级目录:
/Library/Screen Savers/

### 静态壁纸
系统设置 -> 墙纸 -> 添加照片
选择 wallpaper_1.png 或 wallpaper_2.png

### 格式转换
HTML -> 视频:
ffmpeg -i input.html output.mp4

视频 -> .mov:
ffmpeg -i output.mp4 output.mov

GIF:
ffmpeg -i output.mp4 output.gif

### 技术实现
- HTML5 Canvas 实时渲染
- 字符源仅来自原创诗歌
- 多速率随机字符雨
- 1920x1080 原生输出
