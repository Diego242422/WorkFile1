## the shadow of the div
```
<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8"> 
<title>菜鸟教程(runoob.com)</title> 
<style> 
div
{
	width:300px;
	height:100px;
	background-color:yellow;
	box-shadow: 10px 5px 2px #888888;
}
</style>
</head>
<body>

<div></div>

</body>
</html>
```
## the round & radius
```
<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8"> 
<title>菜鸟教程(runoob.com)</title> 
<style> 
#example1
{
	border:2px solid #a1a1a1;
	padding:10px 40px; 
	background:#dddddd;
	width:300px;
	border-radius:25px;
}
#example2 {
  border: 2px solid red;
  padding: 10px;
  border-radius: 50px 20px;
}
</style>
</head>
<body>
<div id="example1">
  <p>border-radius 属性允许您为元素添加圆角边框！</p>
</div>
<br><br>
<div id="example2">
  <p>如果设置了两个值，第一个用于左上角和右下角，第二个用于右上角和左下角。</p>
</div>
</body>
</html>
```
## background-clip
```
<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8"> 
<title>菜鸟教程(runoob.com)</title> 
<style>
#example1 {
    border: 10px dotted black;
    padding:35px;
    background: yellow;
}

#example2 {
    border: 10px dotted black;
    padding:35px;
    background: yellow;
    background-clip: padding-box;
}

#example3 {
    border: 10px dotted black;
    padding:35px;
    background: yellow;
    background-clip: content-box;
}
</style>
</head>
<body>

<p>没有背景剪裁 (border-box没有定义):</p>
<div id="example1">
<h2>Lorem Ipsum Dolor</h2>
<p>Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat.</p>
</div>

<p>background-clip: padding-box:</p>
<div id="example2">
<h2>Lorem Ipsum Dolor</h2>
<p>Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat.</p>
</div>

<p>background-clip: content-box:</p>
<div id="example3">
<h2>Lorem Ipsum Dolor</h2>
<p>Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat.</p>
</div>

</body>
</html>
```
##