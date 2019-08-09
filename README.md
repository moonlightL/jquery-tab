# jquery-tab

## 一、介绍

jquery-tab 是一款列表页面标签 tab 插件。

## 二、教程

### 1.引入资源文件

```
<link rel="stylesheet" href="css/bootstrap.min.css">
<link rel="stylesheet" href="js/waves-0.7.5/waves.min.css">
<link rel="stylesheet" href="font/material-design-iconic-font/css/material-design-iconic-font.min.css">
<link rel="stylesheet" href="css/jquery-tab.css">

<script src="js/jquery.min.js"></script>
<script src="js/waves-0.7.5/waves.min.js"></script>
<script src="js/BootstrapMenu/BootstrapMenu.min.js"></script>
<script src="js//jquery-tab.js"></script>
```

### 2.页面布局

```
<div class="row">
  <div class="col-sm-3 col-md-2 sidebar">
    <ul class="nav" id="nav">
      <li><a href="javascript:;" data-url="home.html">菜单一</a></li>
      <li><a href="javascript:;" data-url="home2.html">菜单二</a></li>
      <li><a href="javascript:;" data-url="home3.html">菜单三</a></li>
      <li><a href="javascript:;" data-url="home4.html">菜单四</a></li>
      <li><a href="javascript:;" data-url="home5.html">菜单五</a></li>
      <li><a href="javascript:;" data-url="home6.html">菜单六</a></li>
      <li><a href="javascript:;" data-url="home7.html">菜单七</a></li>
      <li><a href="javascript:;" data-url="home8.html">菜单八</a></li>
      <li><a href="javascript:;" data-url="home9.html">菜单九</a></li>
      <li><a href="javascript:;" data-url="home10.html">菜单十</a></li>
    </ul>
  </div>
  <div class="col-sm-9  col-md-10 main">
        <div id="tab-container"></div>
  </div>
</div>
```
在 a 标签中使用自定义属性 data-url 配置页面 url。

tab-container 是子窗口容器 id 值。

### 3.插件使用

```
<script>
    $(function() {
      $("#tab-container").tab({
        homeUrl: "home.html",
        homeName: "菜单一"
      });
    });
</script>
```

## 三、效果图

![](http://images.extlight.com/jquery-tab.gif)


