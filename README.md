<!DOCTYPE html>
<html>
<head>
	<title>web8</title>
	<meta charset="utf-8">
	<style type="text/css">
	*{
		margin:0px;
		padding-top:0px;
	}
	select{
		border:none;
	}
	a{
		text-decoration: none;
		color:black;
	}
	#top ul{
		display:inline-block;
		float:left;
		margin-left:50px;
	}
	li{
		display: inline-block;
		list-style-type:none;
	}
	#top{
        height:50px;
	}
	.topp{
		margin-left:550px;
		font-size:14px;
		color:grey;
		float:left;
	}
	.topone li{
         height:50px;
         width:100px;
         font-size:14px;
         display:inline-block;
	}
	#hh{
		width:50px;
	}
	#second{
         height:100px;
	}
	.search{
		height:43px;
		margin-bottom:20px;
		width:500px;
		text-align:center;
		color:grey;
		font-size:14px;
		background-image:url(img/search.png);
		background-position: 95% 50%;
		border:1px black solid;
		float:left;
		background-repeat: no-repeat;
		margin-left:150px;
	}
	#s{
		height:30px;
		margin-top:12px;
	}
	#ma{
		float:left;
		margin-left:250px;
		margin-bottom:10px;
	}
	#che{
		float:left;
		margin-left:200px;
		margin-bottom:10px;
	}
	#third{
          height:50px;
	}
	#third form{
		margin-left:250px;
		float:left;
	}
	.head{
		float:left;
	}
	.head li{
          height:40px;
          text-align: center;
          width:110px;
          display:inline-block;
	}
	
	.head li:hover{
		border-bottom:4px  solid rgb(58,167,71);
	}
	.head li a:hover{
		color:rgb(58,167,71);
	}
	#fix{
		position:fixed;
		top:140px;
		right:0px;
	}
	#fix li{
		height:60px;
		width:40px;
		background-color: black;
		display:block;
		margin-bottom:2px;
		padding-top:25px;
		padding-left:11px;
	}
	#fouth{
		height:50px;
	}
    .biao p{
         height:30px;
         width:90px;
         text-align:center;
         padding-top:15px;
         display:inline-block;
    }
    .grey{
    	background-color:rgb(229,229,229);
    }
    .biao  a:hover{
         color:rgb(113,187,121);
    }
    #batu{
      margin-left:250px;
      margin-top:50px;
    }
    .tu{
      height:300px;
      width:240px;
      margin:10px;
      display:inline-block;
      border:1px black solid;
      float:left;
      background-repeat:no-repeat;
      background-position:50% 20%;
    }
    .tu img{
      margin-top:30px;
    }
    .he{
      height:70px;
      width:240px;
      background-color:rgba(71,71,66,0.9);
      float:left;
      color:white;
      margin-top:230px;
      text-align:center;
      font-size:14px;
    }
    .tu:hover .he{
      height:190px;
      font-size:22px;
      width:240px;
      background-color:rgba(71,71,66,0.9);
      float:left;
      margin-top:0px;
      padding-top:110px;
      color:white;
      text-align:center;
    }
    #last li{
       text-align:center;
       border-right:1px white solid;
       width:110px;
       font-size:14px;
       margin-top:20px;
    }
    #last li a{
      color:white;
    }
    #last{
      margin-left:300px;
    }
    .option div{
      height:100px;
      width:150px;
      border:1px solid black; 
      font-size:16px;
    }
    .option div:hover{
      background-color:green;
      color:white;
    }
	</style>
</head>
<body>
       <div id="top">
       <p class="topp">嘿，欢迎来买猜商城！</p>
       <form>
       <ul class="topone">
       <li style="font-weight:bold;"><a href="#">请登录</a></li>
       <li  style="font-weight:bold;" ><a href="#">免费注册</a></li>
       <li>
       <select>
       <option>我的订单</option>
       </select>
       </li>
       <li>
       <select>
       <option>我的买猜</option>
       </select>
       </li>
       <li><a href="#">帮助中心</a></li>
       <li id="hh">  <img src="img/wb.png"></li>
       <li id="hh">  <img src="img/wx.png"></li>
       </ul>
       </form>
       </div>


       <div id="second">
       <img src="img/logo.png" id="ma">
       <div class="search"><p id="s">请输入搜索内容</p></div>
       <img src="img/cart.png" id="che">
       </div>


       <div id="third">
       <form >
       <select>
               <option  style="font-weight:bold; font-size:16px;">全部商品的分类</option>
               <option  class="option"><div>休闲食品</div></option>
               <option  class="option"><div>茗茶</div></option>
               <option  class="option"><div>洗护用品</div></option>
               <option  class="option"><div>土特产</div></option>
               <option  class="option"><div>名酒</div></option>
               <option  class="option"><div>玉石</div></option>
       </select>
       </form>
       <ul class="head">
       <li><a href="#">首页</a></li>
       <li><a href="#">名酒</a></li>
       <li><a href="#">茗茶</a></li>
       <li><a href="#">玉石</a></li>
       <li><a href="#">休闲食品</a></li>
       <li><a href="#">洗护用品</a></li>
       <li><a href="#">土特产</a></li>
       <li><a href="#">积分商城</a></li>
       <li><a href="#">抽奖游戏</a></li>
       </ul>
       </div>

       <img src="img/banner.png" style="width:100%;margin-top:-6px;margin-bottom:10px;">
       <ul id="fix">
       <li><img src="img/cart1.png"></li>
       <li><img src="img/qq.png"></li>
       <li><img src="img/zuji.png"></li>
       <li><img src="img/erweima.png"></li>
       <li><img src="img/gotop.png"></li>
       </ul>
        <div id="fouth">
        <a href="#" style="margin-left:280px;">首页</a>><a href="#" style="color:grey;">玉石</a>
        <p style="color:grey;margin-left:800px;display:inline-block;">共200件相关商品</p>
        </div>
        <div class="biao" style="border-top:1px grey solid; border-left:1px grey solid;  margin-left:270px; border-right:1px grey solid; margin-right:240px;">
        <p class="grey"><a href="">玉石</a></p>
        <p ><a href="" >白玉</a></p>
        <p ><a href="">碧玉</a></p>
        <p ><a href="" >黄玉</a></p>
        <p ><a href="" >和田玉</a></p>
        <p ><a href="" >翡翠</a></p>
        <p ><a href="" >绿松玉</a></p>
        <p ><a href="" >墨玉</a></p>
        <p ><a href="" >&nbsp</a></p>
        <p ><a href="" >&nbsp</a></p>
        </div>
        <div class="biao" style="border-top:1px grey solid; border-left:1px grey solid;  margin-left:270px;  border-right:1px grey solid;margin-right:240px; " >
        <p class="grey" ><a href="" >其他</a></p>
        <p><a href="">吊坠</a></p>
        <p><a href="">扳指</a></p>
        <p><a href="">手镯</a></p>
        <p><a href="">&nbsp</a></p>
        <p><a href="">&nbsp</a></p>
        <p><a href="">&nbsp</a></p>
        <p><a href="">&nbsp</a></p>
        <p><a href="">&nbsp</a></p>
        <p><a href="">&nbsp</a></p>
        </div>
        <div class="biao" style="border-top:1px grey solid; border-bottom:1px solid grey; border-left:1px grey solid;  margin-left:270px;  border-right:1px grey solid;margin-right:240px;" >
        <p class="grey" "><a href="">地区</a></li>
        <p><a href="">北京</a></p>
        <p><a href="">安徽</a></p>
        <p><a href="">福建</a></p>
        <p><a href="">内蒙古</a></p>
        <p><a href="">宁夏</a></p>
        <p><a href="">黑龙江</a></p>
        <p><a href="">河北</a></p>
        <p><a href="">&nbsp</a></p>
        <p><a href="">更多</a></p>
        </div>

        <div id="batu">
        <div class="tu" style="background-image: url(img/img1.png)"><div class="he"><br/>竞猜价：￥ 399.00&nbsp&nbsp<br/>翡翠千手观音吊坠</div></div>
        <div class="tu" style="background-image: url(img/img2.png)"><div class="he"><br/>竞猜价：￥1980.00 &nbsp&nbsp<br/>翡翠龙凤吊坠</div></div>
        <div class="tu" style="background-image: url(img/img3.png)"><div class="he"><br/>竞猜价：￥199.00 &nbsp&nbsp<br/>翡翠花蕊吊坠</div></div>
        <div class="tu" style="background-image: url(img/img4.png)"><div class="he"><br/>竞猜价：￥199.00 &nbsp&nbsp<br/>翡翠如意吊坠</div></div>
        <div class="tu" style="background-image: url(img/img5.png)"><div class="he"><br/>竞猜价：￥99.00 &nbsp&nbsp<br/>翡翠蝉吊坠</div></div>
        <div class="tu" style="background-image: url(img/img6.png)"><div class="he"><br/>竞猜价：￥99.00 &nbsp&nbsp<br/>翡翠观音（浅色）吊坠</div></div>
        <div class="tu" style="background-image: url(img/img7.png)"><div class="he"><br/>竞猜价：￥199.00 &nbsp&nbsp<br/>翡翠平安扣（深色）吊坠</div></div>
        <div class="tu" style="background-image: url(img/img8.png)"><div class="he"><br/>竞猜价：￥199.00 &nbsp&nbsp<br/>翡翠如意吊坠</div></div>
        </div>

        <div style="background-color:rgb(245,245,245);height:80px;padding-top:30px;float:left;width:100%;margin-top:150px;">
        <ul>
        <li style="width:220px;margin-left:250px;border-right:1px rgb(200,200,200) solid; margin-right:40px;"><img src="img/f1.png" style="float:left;"><p style="font-size:20px;display:inline-block;">资质认证</p><p style="font-size:14px;margin-left:50px;">服务和100%实名认证</p></li>
        <li style="width:220px; border-right:1px rgb(200,200,200) solid; margin-right:40px;"><img src="img/f2.png"  style="float:left;"><p style="font-size:20px;display:inline-block;">支付安全</p><p style="font-size:14px;margin-left:50px;">明码标价支付即信息安全</p></li>
        <li style="width:220px; border-right:1px rgb(200,200,200) solid; margin-right:40px;"><img src="img/f3.png"  style="float:left;"><p style="font-size:20px;display:inline-block;">保险赔付</p><p style="font-size:14px;margin-left:50px;">为您提供担保赔付</p></li>
        <li style="width:220px;"><img src="img/f4.png"  style="float:left;"><p style="font-size:20px;display:inline-block;">售后无忧</p><p style="font-size:14px;margin-left:50px;">服务出问题经理全程跟进</p></li>
        </ul>
        </div>

        <div style="background-color:rgb(50,50,50);height:100px;width:100%;float:left;">
        <ul id="last" >
        <li><a href="#">首页</a></li>
        <li><a href="#">工商代理</a></li>
        <li><a href="#">财务代记账</a></li>
        <li><a href="#">股权交易与变更</a></li>
        <li><a href="#">企业贷款</a></li>
        <li><a href="#">办公室租赁</a></li>
        <li><a href="#">社保公积金代理</a></li>
        <li style="border-right:1px rgb(50,50,50) solid;"><a href="#">法律服务</a></li>
        </ul>
        <br/>
        <p style="color:white;margin-left:700px;font-size:14px;">O&nbsp2017-2018&nbsp买猜商城有限公司&nbsp版权所有</p>
        </div>
      
</body>
</html>
