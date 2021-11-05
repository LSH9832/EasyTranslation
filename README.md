# <img src="icon.png" width="45">EasyTranslation(仅支持Linux)简易翻译工具
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;windows下的翻译软件很多，但是貌似linux没有多少，看外文文献有点不方便，使用本工具可以稍微方便一些。
<strong>使用本工具之前，你需要确定你的linux系统中有python3环境，并且安装了python3-pip</strong>

## 安装
```bash
git clone https://github.com/LSH9832/EasyTranslation.git
cd EasyTrainslation
chmod +x ./setup
./setup
```
即可安装完毕。在应用菜单中搜索EasyTrainslation即可找到。为了方便使用可以固定到侧边栏。
## 使用
本工具使用的是百度翻译的API。首次翻译后会出现id&key.ini文件，默认的是热心网友提供的appid和key, 但是开通的功能是普通版(qps=1, 实际使用感觉还要更慢)，速度有的时候感觉特别慢，如果需要使用自己的API账号开通高级版（qps=10, 每月前200万字符免费，超出部分49RMB/百万字符，余额不足当月自动停用），请自行更改文件配置。<a href='https://api.fanyi.baidu.com/product/11'>点此获取自己的appID和key</a><br><br>
打开后用鼠标选中文字即可翻译。
