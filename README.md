# jiwenhao666.github.io
<!DOCTYPE html>
<html lang="china">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>我的第三个网页

    </title>
   
<style>
    ul{
        list-style-type: none;
        
        margin: 0;
        padding: 0;
        overflow: hidden;
        background-color: #333;
}
    a:link,a:visited{
      
        display: block;
     
        color: white;
        width: 80px;
        height: 40px;
        text-align: center;
        font-family: 'Courier New', Courier, monospace;
        text-decoration: solid;

    }
    a:active{
        
        background-color: cyan;
        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    }
    li {
       float: left; 
    }

    .active {
    background-color: #4CAF50;
}
.el-carousel__item h3 {
    color: #475669;
    font-size: 14px;
    opacity: 0.75;
    line-height: 150px;
    margin: 0;
  }

  .el-carousel__item:nth-child(2n) {
     background-color: #99a9bf;
  }
  
  .el-carousel__item:nth-child(2n+1) {
     background-color: #d3dce6;
  }
</style>
<body>
  <h1 style="text-shadow:5px 5px #4CAF50  5px;">我的主页</h1>
<hr>
	<script>
		function doSearch(value){
			alert('You input: ' + value);
		}
	</script>

    <template>
        <div class="block">
          <span class="demonstration">默认 Hover 指示器触发</span>
          <el-carousel height="150px">
            <el-carousel-item v-for="item in 4" :key="item">
              <h3 class="small">{{ item }}</h3>
            </el-carousel-item>
          </el-carousel>
        </div>
        <div class="block">
          <span class="demonstration">Click 指示器触发</span>
          <el-carousel trigger="click" height="150px">
            <el-carousel-item v-for="item in 4" :key="item">
              <h3 class="small">{{ item }}</h3>
            </el-carousel-item>
          </el-carousel>
        </div>
      </template>
    <ul >
        <li ><a class="active" href="#home" >主页</a></li>
        <li><a href="#news">了解</a></li>
        <li><a href="#contact">信息</a></li>
        <li><a href="#school">我的学校</a></li>
        <li><a href="#clas">我的班级</a></li>
        <li><a href="#information">我的详情</a></li>
        <li><a href="#want">我的目标</a></li>
        <li style="float: right;"><a class="active" href="#about">关于我</a></li>
        <li style="float: right;"><a class="active" href="#about">联系我们</a></li>
        <li style="float: right;"><a class="active" href="#about">基础信息</a></li>
    </ul>
   
    <hr>
    
	<p>输入你想输入的关键字</p>
  <input type="text" style="width: 300px;" value="关键字">
  <input type="submit" value="搜索">
	<div style="margin:20px 0;"></div>
	
 
      </div>
      <div id="container" style="width: 500px;">
        <div id="header" style="background-color:#4CAF50;">
            <h1 style="bottom: 10px; text-align: center;">这是一个大标题</h1>
        </div>

    </div>
    <div id="menu" style="float:left;width: 100px ;height: 200px;background-color:#4CAF50;">
        <h2 style="color: aliceblue; text-align: center;">菜单</h2>
        <h3 style="color: aliceblue;text-align: center;">java</h3>
        <h3 style="color: aliceblue;text-align: center;">js</h3>
        <h3 style="color: aliceblue;text-align: center;">css</h3>
    </div>
    <div id="content" style="float:left; background-color:aliceblue;height: 200px;width: 400px;text-align: center;">
      <br>
      <br>
        <b>这是内容加粗</b>快来编写
    </div>
 
    <div id="sil" style="background-color:#4CAF50; text-align:center; height: 20px;width: 500px;float: left;text-align: center;">
        这是属于我的作品
    </div><br>
</body>
</html>

