# Music
## 我的修改

* 增加网易云logo以及圆角属性。
* 修改为单段代码，方便在wordpress中以 页头脚本/页尾脚本 形式加入。

```html
<style>
#momo{
	position: fixed;
	bottom: -300px;
	left: -270px;
	transition:2s bottom,0.4s left;
	z-index:1000;
}
#momo:hover{
	bottom: -0px;
	left: -0px;
}

#momo-bidy{
	background-color: darkgray;
}


#momo div{
	top:10px;
	right: -10px;
	position: absolute;
	width: 20px;
	height: 90px;
	text-align: center;
	line-height: 90px;
	background-color: red;
	color: #fff;
	border-radius: 0 10px 10px 0;
}
</style>

	<script crossorigin="anonymous" src="https://lib.baomitu.com/jquery/3.3.1/jquery.min.js"></script>
		<!--
        	开始
        	更换音乐直接换歌单外链即可
        -->
		<div id="momo">
		 <iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width=280 height=450 src="//music.163.com/outchain/player?type=0&id=6973396249&auto=0&height=430"></iframe>
		 <div id="">
		 	<img src="https://s1.music.126.net/style/favicon.ico?v20180823" height="20" >
		 </div>
		</div>
		<!--
        	结束
        -->
```







-----

## 以下为原始ReadMe

网易云外链小改成为左悬浮控件

###这是由网易云外链小小修改后的成果

如果需要修改音乐直接改外链即可

![配置](http://www.tzr.me/images/2019/03/04/b6c564937614cf50.png)

##效果
隐藏时:
![](http://www.tzr.me/images/2019/03/04/4df83ea525437dc6.png)



显示时:
![](http://www.tzr.me/images/2019/03/04/ZUX5GEAJW26WP4VTODQL.png)

#现在是地址

演示地址:[https://xiangmomo.github.io/Music/](https://xiangmomo.github.io/Music/)

下载地址:[https://github.com/xiangMOMO/Music](https://github.com/xiangMOMO/Music)
