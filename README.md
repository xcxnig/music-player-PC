# music-player-PC
##web版网易云音乐(900行html+1200行css+1100行js)
##<a href="http://onlyfzz.p.imooc.io/">网易云音乐pc版（点击进入）</a><br>
这是我第一次写这么多的js,写完感觉还是有一点成就感的...<br>
###主要实现的功能如下:
<ol>
<li>跨域实现歌曲搜索功能,在搜索框内直接搜索即可.</li>
<li>可以从搜索结果中直接双击播放,点击爱心图标可以将音乐添加进我喜欢的音乐中.</li>
<li>手写jq插件实现了跑马灯轮播图效果,鼠标滑过下拉层显示.</li>
<li>实现了大量的tab切换.</li>
<li>点击用户名,登录面板显示.</li>
<li>点击“+”按钮,可以新建歌单,点击展开按钮,可以展开/拉起歌单列表.</li>
<li>可以对歌单进行编辑,可以随时更改歌单名称/标签/内容.</li>
<li>实现了右键菜单,在“我喜欢的音乐”右键点击,菜单显示,并且可以实现播放以及下一首.(我喜欢的音乐为默认歌单,不允许编辑)</li>
<li>在我喜欢的音乐歌单中点击爱心图标可以移除歌曲.</li>
<li>在新建的歌单右键点击,可以实现删除歌单和编辑歌单.</li>
<li>使用插件更改默认的滑动条样式.</li>
<li>底部为播放器,实现了播放,上一首,下一首,调节播放进度,显示缓冲进度,显示播放进度,调节音量,静音,单曲循环,列表循环.</li>
<li>底部最右侧为播放列表,点击显示播放列表,单击歌曲可以播放,并且可以清空列表(有2首为自带歌曲,无法清空).</li>
<li>以上所有操作(创建歌单、编辑歌单、删除歌单、添加我喜欢的音乐、清空播放列表)都采用本地存储记录,刷新或者关闭浏览器都不会改变数据.</li>
</ol>
###不足之处:
<ol>
<li>不应该使用插件更改滑动条,应该自己写一个的.这个插件是挺好用的,但是它更改了我的一些结构,还添加了一些样式,导致我后面骑虎难下,有些地方的结构和样式只能妥协,显得不太合理,不过这个插件还是替我省了事,如果我自己写的话估计还得查资料.</li>
<li>轮播图有时候会莫名其妙的出现bug,这个我现在还没解决.</li>
<li>歌曲总时间有时会出现NaN,这个完全无解,因为不是本地的原因,有时候获取的数据会出现问题.</li>
</ol>

