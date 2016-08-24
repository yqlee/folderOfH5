## html基础 ##
1. web前端简单介绍  
   web前端包含：pc端网页、移动端页面；  
   web前端首先要解决用户体验的问题；  
   浏览器插件f12，开发工具，用于查看网页源码；  

2. 认识网页  
   网页主要是由文字、图片和按钮元素构成。当然，除了这些元素，网页还可以包含音频、视频以及flash等；  

3. web标准  
   w3c万维网联盟组织，制定web标准的结构；  
   web标准：制作网页要遵循的规范；  
   web标准规范分类：结构标准、表现标准、行为标准；  
   结构：html标签、表现：css；行为：javascript;  

4. 浏览器介绍  
   浏览器是网页运行的平台，常用的浏览器有IE、火狐（Firefox）、谷歌（Chrome）、Safari和Opera等；  
   浏览器内核：也就是浏览器所采用的渲染引擎，渲染引擎决定了浏览器如果显示网页的内容以及页面的格式信息；  
   IE：trident；  
   谷歌/Opera：blink；  
   火狐：gecko；  
   苹果 ：webkit；  

5. 浏览器与服务器  
   1、浏览器与服务器交互，请求--响应（通过http协议）；  
   2、http协议：超文本传输协议，也就是浏览器和服务器端的网页传输数据的约束和规范；  
   
6. html简介  
  html：hyper text markup language,超文本标签语言，主要通过html标签对网页中的文本、图片、声音等内容进行描述；    
  html之所以称为超文本标记语言，不仅是因为它通过标签描述网页内容，同时也由于文本中包含了所谓的“超链接”，通过超链接可以实现网页的跳转，从而构成丰富多彩的web页面；  
  <pre><code>
  &lt;!DOCTYPE html>
   &lt;html lang="en">
	 &lt;head>
	     &lt;meta charset="utf-8">
		 &lt;title> &lt;/title>
	 &lt;/head>
	 &lt;body>
	 &lt;/body>
 &lt;/html>
 </code></pre>  
  &lt;html>称为根标记，用于告知浏览器其自身是一个 HTML 文档， &lt;html>标记标志着HTML文档的开始，&lt;/html>标记标志着HTML文档的结束，在他们之间的是文档的头部和主体内容。  
  &lt;html  lang="en">   向搜索引擎表示该页面是html语言，并且语言为英文网站，其"lang"的意思就是“language”，语言的意思，而“en”即表english；  
这个主要是给搜索引擎看的，搜索引擎不会去判断该站点是中文站还是英文站，所以这句话就是让搜索引擎知道，你的站点是中文站，对html页面本身不会有影响；  

7. html标签关系  
  嵌套关系；  
  并列关系；
8. html标签分类
  双标记；  
  单标记；
9. sublime快捷键使用  
  ctrl+K+B:快速打开/隐藏侧边栏；  
  ctrl+shift+d：快速复制；  
  ctrl+L：快速选中；  
  ctrl+鼠标左键：集体输入；  
  ctrl+h：查找替换；  
  ctrl+f：标签查找；  
  ctrl+shift+上下箭头：整体移动；  
  [http://blog.csdn.net/moyan_min/article/details/11530751](http://blog.csdn.net/moyan_min/article/details/11530751)  
10. html标签  
   &lt;hr/>：水平线标记；  
   &lt;!--注释语句-->：注释标记；  
   &lt;br/>：换行标记；  
   &lt;p>&lt;/p>：段落标记；  
   &lt;hn>&lt;/hn>：标题标记；n=123456;  
   &lt;font>&lt;/font>；文本样式标记；  
   
11. 顶顶顶