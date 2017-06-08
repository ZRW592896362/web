# web
1. <!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<script src="http://libs.baidu.com/jquery/1.10.2/jquery.min.js">
</script>
<script>
$(document).ready(function(){
  $("#btn1").click(function(){
    $("p").append(" <b>追加文本</b>。");
  });

  $("#btn2").click(function(){
    $("ol").append("<li>追加列表项</li>");
  });
});
</script>
</head>

<body>
<p>这是一个段落。</p>
<p>这是另外一个段落。</p>
<ol>
<li>List item 1</li>
<li>List item 2</li>
<li>List item 3</li>
</ol>
<button id="btn1">添加文本</button>
<button id="btn2">添加列表项</button>
</body>
</html>


2. <!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<script src="http://libs.baidu.com/jquery/1.10.2/jquery.min.js">
</script>
<script>
$(document).ready(function(){
  $("button").click(function(){
    $("#div1").remove();
  });
});
</script>
</head>
<body>

<div id="div1" style="height:100px;width:300px;border:1px solid black;background-color:yellow;">

这是 div 中的一些文本。
<p>这是在 div 中的一个段落。</p>
<p>这是在 div 中的另外一个段落。</p>

</div>
<br>
<button>移除div元素</button>

</body>
</html>
