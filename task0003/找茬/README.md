#任务一，找茬#

网站：[索尼官网](http://www.sony.com.cn/)

-----


**大量重复使用元素**


- 头部

![](http://i.imgur.com/MBA93q6.png)

头部应该使用`<header>`标签内嵌`<nav>`再用`<ul>`的`<li>`标签来表达所有链接。但是官网基本都使用div元素，无论是头部还是导航。完全没有语义。

----

- 主体部分

![](http://i.imgur.com/1Z8pOqs.jpg)

所有图片都包含在`<div>`标签内,这些都可以使用`<figure>`元素

----
- 脚部

![](http://i.imgur.com/ZzLmm2f.png)

在html5中`<footer>`标签可以代替`<div>`标签

