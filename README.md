5a.中国  
https://hylxing.github.io  
  
  &ensp;&ensp;开源主页，使用者请删除index.html里我的百度统计，如果你不删除直接就使用我的。  
你的点击访问ip不光看不到，还会全部出现在我的统计后台里。  
以前就有几个叼毛不看源码，也不改代码，只改里面的内容文字图片，又不删掉我的统计id.  
结果别人访问他的网站，我后台看的一清二楚。  
请删掉  <!--百度统计-->
```
		<script>
			var _hmt = _hmt || [];
			(function() {
			  var hm = document.createElement("script");
			  hm.src = "https://hm.baidu.com/hm.js?962b95c3**e*65***********"
			  var s = document.getElementsByTagName("script")[0]; 
			  s.parentNode.insertBefore(hm, s);
			})();
			</script>
```
  
  这一整段。  
  &ensp;&ensp;或者自己换上你自己的百度统计id.
  里面自带一个是卜蒜子统计，我已更新最新，这个不用动，但看不到后台谁谁访问。
  建议自己添加自己的百度统计。
  很多地方我都加了注释。
  
  
  官网主页：https://hy6xing.gitee.io  
  个人博客：https://hy6xing.cn  
  个人主页：https://5a.中国  
  不懂就要问，不要瞎搞。
