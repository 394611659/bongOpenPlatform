bong开放平台
================

![image](https://github.com/Ginshell/bongOpenPlatform/blob/master/documents/cover.png?raw=true)

#### 介绍

bong开放平台可以提供接口，在用户授权的状况下提供用户的运动和睡眠数据给开发者，开发者可以向bong团队申请开发资格。

**注意：** 内测期间所有活跃点在正式推出后将清零



#### 目录
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

#### 开发资格申请

因为现在开放平台还处于内部测试阶段，感兴趣的开发者请直接添加微信bong开发者俱乐部，和我们聊聊你的想法。


````
比如下面的话题，但不限于下面话题：

- 申请理由：`比如，你想开发什么样的bong插件？为什么想开发这个插件？`
- 你做过的最hacker的事情：`比如，我开发过xxx APP，我自制过四轴直升飞机...`
````

现阶段，没有啥挑选原则，有爱的hacker们速度入。

#### 开发环境
开放平台现在开放的是app内置的插件区域，插件区域以html5的形式通过用户授权来展现。

#### 成为bong开发者你可以获得...

- 每次bong有了重大的硬件软件更新你会最先获得通知，甚至可能我们会邮寄一个测试中的手环给你，帮助你完成插件的开发工作。

- 你可以通过用户使用你的插件获得一些**活跃点** [*活跃点有啥用？*](#活跃点有啥用)
  
  *tips: 你的插件能够帮助用户动得越多睡得越好，你获得的活跃点就会越多哦。* 
  
- 想玩软硬结合的Hacker，无需找硬件工程师配合了，申请成为bong开发者即可。


#### 活跃点有啥用
bong的活跃点可以用于 bong Shop 购买商品，包括 bong 、bong相关配件、bong售后服务等。一个活跃点暂定约为1人民币

#### 开放平台案例
##### bong时之战
bong时之战是bong团队几位工程师为bong做的小插件，

#### 开发文档
##### 接口定义