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
        如果当前页面（html）和要访问的资源（图片），不在同一个文件夹中，如果页面在图片同一级目录中，src="图片名称"
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
      锚链接 id="test"
特殊字符
     &nbsp: 空格
     &lt: <
     &gt: >
     
                     
     
                 
 
