# WebClient
10.29
换行标签<br/>
横线标签<hr></hr>
标题标签<h1></h1>
段落标签 <p> </p>
格式化标签（突出显示信息）
文字加粗 <strong></strong>或者<b></b>
文字斜体 <em></em>或者<i></i>
文字下划线 <ins></ins> 或者<u></u>
文字加颜色或大小 <font color=" "size=""></font>  color属性：设置文字颜色 size属性：设置文字大小 不需要单位
删除线标签  <del></del>或者<s></s>
其他双标签(网页布局）  <div></div>（横元素）  span></span>（竖元素）   
图片标签 <img> 相关属性  src="" :通过该属性设置图片的相对路劲或者绝对路劲，用来浏览器展示图片  
                       title="":设置鼠标悬停图片上的文字提示
                       alt="":设置图片描述信息（注意：该属性不是给用户展示的，为搜索引擎提供服务的）
                       width=""：设置宽度 height="":设置高度 （有自己的缩放比例）
 路径 
     绝对路径：带有磁盘目录或者网站地址的路劲   
     相对路劲：相对路劲必须保证在同一个根目录下  没有磁盘目录和网站地址
        如果当前页面（html）和要访问的资源（图片），在同一个文件夹中,src="图片名称"
        如果当前页面（html）和要访问的资源（图片），不在同一个文件夹中，如果页面在图片上一级目录中，src="文件夹名称/+图片名称"
        如果当前页面（html）和要访问的资源（图片），不在同一个文件夹中，如果页面在图片下一级目录中，src="../图片名称"
超链接
     作用：实现页面跳转 <a herf="目标页面的路径">文字</a> 
     属性介绍：target="blank"在新窗口中打开页面 
              target="-self"默认值在当前窗口中打开页面  
      在head标签中添加base标签，在base标签中设置target属性-blank;
      title:设置鼠标悬停超链接上的文字提提示
超链接在本页面内部跳转
      直接设置href的值为="#"
      锚链接 <a href="id属性值"></a>(一般用于返回页面头部）
特殊字符
     &nbsp: 空格
     &lt: <
     &gt: >
语义标签
<nav></nav> 表示的就是导航区域  该标签的用法和div用法一样（网页布局） 该标签有语义，div没有语义
<header></header> 在网页布局中的头部  该标签的用法和div用法一样（网页布局） 该标签有语义，div没有语义
<footer></footer>在网页布局中的结尾部分  该标签的用法和div用法一样（网页布局） 该标签有语义，div没有语义
<article></article> 该标签的用法和div用法一样（网页布局） 标签的用法和div用法一样（网页布局） 该标签有语义，div没有语义
<aside></adise> 在网页布局中侧边栏部分 该标签的用法和div用法一样（网页布局） 该标签有语义，div没有语义
<section></section> 该标签的用法和div用法一样（网页布局） 该标签有语义，div没有语义
10.30 列表
有序列表 ：
 <ol>
   <li>列表项</li>
 </ol>
 无序列表：
 <ul>
   <li>列表项</li>
 </ul>
自定义列表：（一般用于网页尾部）
<dl>
  <dt>列表项的标题</dt>
  <dd>列表项</dd>
</dl>
多媒体标签
视频标签
<video></video> 属性：src=" " 设置视频的路劲  controls 显示控制栏  loop 设置视频循环播放  autoplay 设置自动播放
                或者<video controls>
                      <source src=" ">
                      <source src=" ">
                    </video>
音频标签 <audio></audio> 同上

meta标签  <meta charset="UTF-8">  charst:字符集  utf-8：属于字符集中的一种编码格式  作用：设置网页编码-->防止网页乱码
          <meta name="keywords"content="写的关键字"（网页关键字为搜索引擎提供）
          <meta name="description" content="关键信息"(网页描述信息）
          <meta http-equiv="refresh" content="几秒；网址 "(实现网页重定向)
link标签 设置网页图片
         <link rel="icon" href="favotion.ico/"> 注意：一般将网页的图标放置到网站的根目录下
表格标签   
    容器<table></table>  行<tr></tr>   列<td></td>  作用：数据展示  网页布局
    属性：border:设置边框 默认为0 height:设置高度 width:设置宽度 cellspacing:设置行和列的距离 默认距离是2  align:设置对齐方式（left/center/right) bgcolor:设置背景颜色
其他标签 <th></th>设置表格标题用法与td一样
    



  
                     
 











