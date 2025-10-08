# 假的哔哩哔哩弹幕网三连检查页面

群友在群里提到这个页面，下载下来发现是个弱智页面，特此记录。


## 工作流程

访问后，会先检查浏览器的&nbsp;LocalStorage&nbsp;，如果没有访问过，就会把一个标记存进去，并停留在当前页面，显示你不给我三连就让你飞起来，如果已经访问过，就会跳转到指定页面。

原版页面通过写死方式写进了&nbsp;Vant&nbsp;UI&nbsp;组件库的&nbsp;CSS&nbsp;和&nbsp;qrCode&nbsp;页面的&nbsp;CSS&nbsp;(估计是别的系统复制下来的页面)，还有一个无用的&nbsp;Vue&nbsp;JS&nbsp;文件。

原版在页头写了网站统计，我都去掉了。直接替换&nbsp;`https://imprk.me`&nbsp;为你自己想要的页面就可以了。
