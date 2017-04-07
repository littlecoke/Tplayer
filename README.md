# HAOTOWN TPlayer
![image](https://ooo.0o0.ooo/2016/12/16/585359df46d72.png)
@(CSS3)[Javascript]
本项目是一款基于css3和js弹幕系统。<br>
未全部完善  [具体demo][3]
![image](https://ooo.0o0.ooo/2016/12/20/5858df24293f5.png)
## 使用方式
引用Tplayer.js和colorpicker.js文件
```
<script src="colorpicker.js" type="text/javascript" charset="utf-8"></script>
<script src="Tplayer.js" type="text/javascript" charset="utf-8"></script>
```
执行
```
Tplayer(Element,videourl,videoposter,danmuserver,danmuid,videotype);
```

| Field              | Type                  | Description                              |
| ------------------ | --------------------- | ---------------------------------------- |
| `Element`          | `Element Object`      | 要插入播放器的元素                       |
| `videourl`         | `String`              | 视频播放地址                             |
| `videoposter`      | `String`              | 视频封面地址                             |
| `videourl`         | `String`              | 弹幕服务器地址                           |
| `danmuid`          | `Int`              	 | 弹幕ID                                   |
| `videotype`        | `String`              | 视频格式 支持flv与mp4 使用flv时需引用flv.js |


后端 `node`
[flv.js github][2]
[flv.js cdn][1]
  [1]: http://www.bootcdn.cn/flv.js/
  [2]: https://github.com/Bilibili/flv.js
  [3]: https://haocity.github.io/Tplayer/
