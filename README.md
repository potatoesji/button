button css 
=========

使用方法：
--------

	* 页面引入font-face.css btn.css 
	<link rel="stylesheet" type="text/css" href="`font-face.css`">
	<link rel="stylesheet" type="text/css" href="`btn.css`">

	*给a标签添加 btn- 0~11 的class
	<a href="javascript:;" class="`btn-0`">0</a>

	* a 标签中的span标签不能省略 如：
	<a href="#" class="`btn-6`">6`<span></span>`</a>
	<a href="#" class="`btn-7`">`<span>7</span>`</a>


规范的README文件开头都写上一个标题，这被称为大标题。

大标题  --文本下面加上等于号 = ，那么上方的文本就变成了大标题。等于号的个数无限制，但一定要大于0个
==== 

中标题  --在文本下面加上 下划线 - ，那么上方的文本就变成了中标题，同样的 下划线个数无限制。
----

	`补空行：`是很常用的用法，当你不想上下两个不同的布局方式交错到一起的时候，就要在两种布局之间补一个空行。


标题还有等级表示法
#一级标题  
##二级标题  
###三级标题  
####四级标题  
#####五级标题  
######六级标题 

##普通文本：##
	不能直接通过回车来换行，需要使用<br>(或者<br/>)
	这是一段普通的文本，  
	直接回车不能换行，<br>  
	要使用\<br>
	注意第三行的<br>前加了反斜杠 \ 。目的就是实现 <  的转义。

##多行文本: ##
		多行文本和单行文本异曲同工，只要在每行行首加两个Tab

#部分文字的高亮 #
如果你想使一段话中部分文字高亮显示，来起到突出强调的作用，那么可以把它用 `  ` 包围起来

##文字超链接##
		给一段文字加入超链接的格式是这样的 [ 我的git地址 ]( https://github.com/potatoesji )。

##鼠标悬停显示的文本##
		`[我的git地址](https://github.com/potatoesji "土豆碰上冰")`

##插入符号##
`圆点符 ---使用的是星号 *`   ,此外还有二级圆点和三级圆点。就是多加一个Tab。
* 昵称：果冻虾仁  
	* 别名：隔壁老王  
		* 英文名：Jelly 

##缩进##
>树形结构  
>>一级树
>>>二-一级树  
>>一级树  
>>>二-二树

##来源于网络的图片##
`![](https://avatars3.githubusercontent.com/u/28727401?s=400&u=fad36d9faa63e25f6a911fab411f53623146a5e7&v=4 "头像--皮卡丘")`  

##给图片加上超链接 ##
[![头像]](https://github.com/potatoesji)  
[头像]:https://avatars3.githubusercontent.com/u/28727401?s=400&u=fad36d9faa63e25f6a911fab411f53623146a5e7&v=4 "自己头像"  

##插入代码片段 ##
```javascript
	at this monment ,you know what I think about
```
