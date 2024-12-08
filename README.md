# TV
电视/广播图标库：
类 别	调用路径	最后更新
📺电视	https://live.fanmingming.com/tv/{name}.png	2024.12.01
📻广播	https://live.fanmingming.com/radio/{name}.png	2024.8.29
⛓️创建您的m3u订阅链接：
下载 demo.m3u 空白示例文件并使用文本编辑软件打开。

https://live.fanmingming.com/tv/m3u/demo.m3u
参考下方示例代码将可用的CCTV1节目源替换为您当地可用的直播源链接，依此类推逐个替换。

#EXTM3U x-tvg-url="https://live.fanmingming.com/e.xml"
#EXTINF:-1 tvg-name="CCTV1" tvg-logo="https://live.fanmingming.com/tv/CCTV1.png" group-title="央视",CCTV-1 综合
可用的CCTV1节目源
此处省略...
将编辑完成的m3u文件上传到您的Github仓库。
为您的Github仓库开启Pages。
通过播放器订阅您的m3u链接。
关于Github Pages：https://docs.github.com/en/enterprise-cloud@latest/pages/quickstart

🛠️工具
📆EPG接口地址：
https://live.fanmingming.com/e.xml
🏞️Bing每日图片：
https://fanmingming.com/bing
🎞️m3u8在线下载：
https://live.fanmingming.com/m3u8
🆕TXT转M3U格式：
https://live.fanmingming.com/txt2m3u
📄在线M3U转TXT：
Demo🔗 https://fanmingming.com/txt?url=https://live.fanmingming.com/tv/m3u/ipv6.m3u
演示🔗 https://fanmingming.com/txt?url=https://live.fanmingming.com/tv/m3u/ipv6.m3u
🌐M3U8 Web Player:
🌐M3U8 网络播放器：
Demo🔗 https://live.fanmingming.com/player/?vurl=https://0472.org/hls/cgtn.m3u8
演示 https://live.fanmingming.com/player/?vurl=https://0472.org/hls/cgtn.m3u8🔗
📖说明
项目EPG接口为112114.xyz站点分发，本项目无法确保其准确性。
通过M3U8 Web Player测试直播源需使用https协议的直播源链接。
在线M3U转TXT工具构建在Vercel，不会记录您的访问日志请放心使用。
TXT转M3U工具为前端网页转换，无需上传文件，粘贴即转换，安全不偷源。
本项目不存储任何的流媒体内容，所有的法律责任与后果应由使用者自行承担。
项目/tv/m3u/和/radio/m3u/目录下的内容收集于互联网，仅供测试研究使用，本项目无法保证其有效性。
主域名【live.fanmingming.com】的WEB访问通过Github Pages自动构建，由CloudFlare提供CDN和安全防护。
镜像域名【live.fanmingming.cn】提供完整的资源WEB访问，通过Github Actions自动构建在CloudFlare Pages。
项目所有文件均托管在GitHub且自动构建，由项目发起人公益维护，欢迎Star本项目或点击Issues反馈您的问题。
您可以Frok本项目到您的Github账户，将缺失的频道Logo上传到tv或radio目录下并发起拉取请求，收到请求后我们会对您提交的内容进行验证，审核通过后会自动为您署名并发布。
