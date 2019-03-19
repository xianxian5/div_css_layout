### 固定头部底部布局
'
<!doctype html>
<html>
<head>
<meta charset="utf-8">
<title>无标题文档</title>
<style>
*{ padding:0px; margin:0px;}
.top,.bottom{ width:100%; position:absolute; background:#000; height:60px;}
.bottom{ bottom:0px;}
.content{ position:absolute; top:60px; bottom:60px; width:100%;}
.left{ float: left; height:100%; background:red; width:200px;}
.right{ margin-left:200px;}
</style>
</head>

<body>
	<!--头尾固定中间自适应-->
	<div class="top"></div>
    <div class="content">
        <div class="left"></div>
        <div class="right">asdfasdf</div>
    </div>
    <div class="bottom"></div>
</body>
</html>
'
