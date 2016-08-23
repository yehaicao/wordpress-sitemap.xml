# wordpress-sitemap.xml
[![](http://www.wordpressleaf.com/logo.png)](http://www.wordpressleaf.com/)
<br/><br/> 
<a href="http://www.wordpressleaf.com/2016_729.html"><img align="right" src="http://www.wordpressleaf.com/logo-app.png" width="248" height="auto"/></a>
wordpress-sitemap.xml是利用sitemap.php来生成wordpress的sitemap.xml，这样做的目的是为了更好的被搜索引擎所收录。你也可以使用插件来达到这样的效果。



你可以访问我们[**wordpress-sitemap.xml**](https://github.com/yehaicao/wordpress-sitemap.xml)项目获取源代码。

## 演示地址
> [**观看演示**](http://www.wordpressleaf.com/sitemap)

## 如何使用

1) 复制sitemap.php文件到WordPress网站的根目录。注意，是网站的根目录，不是主题的根目录。一般赋予只读权限就可以了。

2) 复制以下代码到网站根目录下的.htaccess文件中。注意，这是指你使用的是apache服务器。

```html

# BEGIN sitemap.xml
<IfModule mod_rewrite.c>
RewriteRule ^(sitemap)\.xml$ $1.php
</IfModule>

# END sitemap.xml

```


## Other install options:

Service     | Link
:---------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
官网 *      | [**官网**](http://www.wordpressleaf.com/)
github *    | [**github**](https://github.com/yehaicao/wordpress-sitemap.xml)


## 关于
wordpress-sitemap.xml为 [**WordPress Leaf**](http://www.wordpressleaf.com/)  荣誉出品。