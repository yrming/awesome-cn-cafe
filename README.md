# Awesome CN Café
![CI](https://github.com/ElaWorkshop/awesome-cn-cafe/workflows/CI/badge.svg)

那些网速快咖啡好的咖啡馆。不同颜色的标记代表不同的下载速度。

<table>
<tr><th>标记</th><th>下载速度</th><th>色值</th></tr>
<tr><td><img src="resources/markers/slow.png" width="50" alt="Slow marker"></td><td>0 ~ 4 Mbps</td><td>#C24740</td></tr>
<tr><td><img src="resources/markers/moderate.png" width="50" alt="Moderate marker"></td><td>4 ~ 10 Mbps</td><td>#F3AE1A</td></tr>
<tr><td><img src="resources/markers/fast.png" width="50" alt="Fast marker"></td><td>10+ Mbps</td><td>#50C240</td></tr>
</table>


## 咖啡馆列表

你可以通过 web app 查看所在城市的咖啡馆：[https://cafe-cn.netlify.app](https://cafe-cn.netlify.app)。  
Web app 由 [@antfu](https://github.com/antfu) 维护：https://github.com/antfu/awesome-cn-cafe-web  
VSCode Extension 由 [@YRM](https://github.com/yrming) 维护：https://github.com/yrming/vscode-awesome-cn-cafe

或直接点击下面的链接在 GitHub 上查看。

* [北京 (139)](beijing.geojson)
* [上海 (74)](shanghai.geojson)
* [南京 (6)](nanjing.geojson)
* [武汉 (5)](wuhan.geojson)
* [杭州 (13)](hangzhou.geojson)
* [广州 (6)](guangzhou.geojson)
* [深圳 (37)](shenzhen.geojson)
* [贵阳 (3)](guiyang.geojson)
* [成都 (8)](chengdu.geojson)
* [南昌 (1)](nanchang.geojson)
* [呼和浩特 (1)](hohhot.geojson)
* [洛阳 (1)](luoyang.geojson)
* [芜湖 (2)](wuhu.geojson)
* [青岛 (1)](qingdao.geojson)
* [沈阳 (1)](shenyang.geojson)
* [哈尔滨 (1)](harbin.geojson)
* [大连 (3)](dalian.geojson)
* [长沙 (14)](changsha.geojson)
* [西昌 (1)](xichang.geojson)
* [重庆 (3)](chongqing.geojson)
* [玉林 (1)](yulin.geojson)
* [佛山 (3)](foshan.geojson)
* [保定 (1)](baoding.geojson)
* [南宁 (4)](nanning.geojson)

## 贡献

欢迎发 pull request 添加你去过的咖啡馆。请通过手机 app 或浏览器等方式获取网络速度和经纬度，然后添加到相应的 [geoJSON](http://geojson.org/geojson-spec.html) 中。如果没有你所在的城市，请新建一个 geoJSON 文件。格式请参见 [shanghai.geojson](shanghai.geojson)。

### 通过手机 App

推荐使用 [Speedtest](http://www.speedtest.net/mobile/)（[iOS](https://itunes.apple.com/app/speedtest-net-mobile-speed/id300704847?mt=8) / [Android](https://play.google.com/store/apps/details?id=org.zwanoo.android.speedtest)），既可测试网速也能获取当前经纬度。

### 通过 macOS App

推荐使用 [Speedtest 应用](https://apps.apple.com/us/app/speedtest-by-ookla/id1153157709?mt=12)，既可测试网速也能获取当前经纬度。

### 通过浏览器

请用 [Speedtest](http://speedtest.net) 或其他工具测试网速、在 Mapbox 的[显示经纬度](https://www.mapbox.com/mapbox.js/example/v1.0.0/select-center-form/)中拖拽图中的红色地标获取经纬度。如果你正在咖啡馆并且可以翻墙，也可以使用 [whereami](https://xavierchow.github.io/whereami/) 获得当前经纬度。在 Google Maps 上通过 What’s here 取得的经纬度有些许偏差。

## 授权
[CC-BY](http://creativecommons.org/licenses/by/4.0/)
