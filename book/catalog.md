<link rel="stylesheet" href="http://yandex.st/highlightjs/6.2/styles/googlecode.min.css">
 
<script src="http://code.jquery.com/jquery-1.7.2.min.js"></script>
<script src="http://yandex.st/highlightjs/6.2/highlight.min.js"></script>
 
<script>hljs.initHighlightingOnLoad();</script>
<script type="text/javascript">
 $(document).ready(function(){
      $("h2,h3,h4,h5,h6").each(function(i,item){
        var tag = $(item).get(0).localName;
        $(item).attr("id","wow"+i);
        $("#category").append('<a class="new'+tag+'" href="#wow'+i+'">'+$(this).text()+'</a></br>');
        $(".newh2").css("margin-left",0);
        $(".newh3").css("margin-left",20);
        $(".newh4").css("margin-left",40);
        $(".newh5").css("margin-left",60);
        $(".newh6").css("margin-left",80);
      });
 });
</script>
<div id="category"></div>

* 目录
* [前言](preface.md)
* 1. [CometD商业支持服务](1/1.0.md)
* 2. [贡献给ComentD](2/2.0.md)
 - 2.1. [通过邮件列表贡献](2/2.1.md)
 - 2.2. [通过报告问题作出贡献](2/2.2.md)
 - 2.3. [贡献代码修复和增强](2/2.3.md)
 - 2.4. [促进文档和教程](2/2.4.md)
* 3. [安装](3/3.0.md)
 - 3.1. [下载和安装](3/3.1.md)
 - 3.2. [运行演示](3/3.2.md)
 - 3.2.1 [使用Maven运行演示](3/3.2.1.md)
 - 3.2.2 [与运行Jetty或者另一个Servlet容器的演示](3/3.2.2)
* 4. 故障排除
* 5. 底漆
* 6. 概念和体系结构
* 7. JavaScript库
* 8. Java库
* 9. 扩展
* 附录A: 建筑
* 附录B: 从ComentD 2移植
* 附录C: Bayeux协议规范
* 附录D：提交者发布说明
