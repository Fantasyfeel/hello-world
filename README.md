书写

这是一个说明

<h0>  这是一个非常好的交互式说明 </h0>

wide过
<h1>  这是一个非常好的交互式说明 </h1>
 
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSTusoSfnmndO6qB4xtGz1KJXwsOEIV_DcDsj0wv1JflZ2qKw8i-o78W7L-ITwXXaL0GmE&usqp=CAU" >

<h2>  说明 </h2>



<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta charset="UTF-8">


    <title>我的文档</title><!--文档名-->
    <link rel="stylesheet" type="text/css" href="style.css">
    <script src="script.js"></script>
</head>
<body>
    <div class="container">
        <div class="sidebar">
            <ul>
                <li>

                </li>
            </ul>
            <div class="return" data-target="content1.html" onclick="Return(event)"></div>
            <div class="file" data-target="content1.html" onclick="loadContent(folder, event)">【0】新手-指南</div>
            <div class="file" data-target="content2.html" onclick="loadContent(folder, event)">【1】资源-链接</div>
            <div class="folder" data-target="文档/content2.html" onclick="JumpHtml(event)">【2】外部-网址</div>
            
        </div>
        <div class="content" id="content">
            <!-- 这里将通过JavaScript加载内容 -->
        </div>
    </div>
</body>
</html>
