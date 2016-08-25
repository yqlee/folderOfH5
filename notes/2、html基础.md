## html基础 ##
1. meta标签介绍：  
   &lt;meta charset="utf-8">：设置字符集  
   &lt;meta name="keywords" content=“精品女装”>：关键字，方便被搜索引擎搜索到，对网站进行优化的作用 SEO  
   &lt;meta name="description" content="精品女装">：对网站的描述，对网站进行优化的作用 SEO    
   &lt;meta http-equiv="refresh" content="5;url=http://www.baidu.com">：网页重定向  
   
2. Link标签介绍：  
   &lt;link rel="icon" href="favicon.ico">：给网页title中放置小图标  
   &lt;link rel="stylesheet" href="1.css">：引入外部样式表
  
3. 表格（table）  
   作用：显示数据    
   组成：table：定义表格；tr：行；td：列（单元格）；th：设置表格标题，用法与td一致；     
   属性：   
   border：设置表格边框；  
   width：设置表格宽度；  
   height：设置高度；  
   cellspacing：设置单元格之间的距离；  
   cellpadding：文字距离单元格边框的距离；  
   bgcolor：设置背景颜色；  
   align：设置文字居中；  
   
4. 表单（form）  
   作用：收集信息；  
   属性：  
   action：处理用户数据信息；  
   Method：get/post  
   get提交数据：通过地址栏的方式进行数据提交，将用户输入的信息显示出来；get提交安全性差；  
   Post：数据通过后台进行提交，不会将用户信息显示出来，安全性比较好；  

5. 标签语义化  
   1、尽可能少的使用无语义的标签div和span；  
   2、在语义不明显时，既可以使用div或者p时，尽量用p，因为p在默认情况下有上下间距，对兼容特殊终端有利；  
   3、不要使用纯样式标签，如：b、font、u等，改用css设置；  
   4、需要强调的文本，可以包含在strong或者em标签中，strong默认样式是加粗(不要用b)，em是斜体(不用i);