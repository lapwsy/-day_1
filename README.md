# -day_1
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8">
        <style>
        	*{
        		margin:0;
        		padding:0;
        	}
        	html{
        		background-color:#d8ddde;
        		height:100%;
        	}
        	#content{

        		width:960px;
        		height:100%;
        		font-family: "宋体";
    			font-size: 12px;
				margin:0 auto;
				background-color:#FFF;	
        	}
        	li{
        		list-style:none;	
        	}
        	a{
        		text-decoration:none;
        	}
        	.headFoot{
        		font-family:"宋体";
        		color:black;
        		font-size:12px;
        		width:100%;
        		height:100px;
        		/* background-color:#119; */
        		position:relative;
        	}
        	.headFoot a:visited{
        		color:black;
        	}
        	.headFoot a:active{
        		color:black;
        	}
        	.headFoot a:hover{
        		color:blue;
        	}
        	.headFoot li+li a{
				border-right:1px solid;
				padding:6px;
        	}
        	.headFoot li{
        		/* background-color: red; */
        		height:30px;
				float:right;
				list-style:none;
				position: relative;
				right:18px;
				top:3px;
				padding:10px 0px;
        	}
        	.button{
        		position:absolute;
        		font-size:12px;
        		font-family:"宋体";
        		padding:4px 4px;
        	}
        	#button1{
				top:50px;
				right:189px;
        	}
        	#button2{
        		top:50px;
				right:25px;
        	}
			#logo{
        		position:absolute;
        		top:10px;
        		left:0;
        	}
        	#navColor{
        		height:4px;
        		width:100%;
        		background-color: blue;
        	}
        	#nav{
        		position:absolute;
        		width:960px;
        		height:310px;
				/* background-color: #ccc; */
        	}
        	#menuePic{
        		position:absolute;
				top:260px;
        	}
        	#menue{
        		width:100%;
        		height:51px;
        		font-family:"黑体";
        		text-align:center;
        		color:white;
        		font-size:14px;
        		position:absolute;
        		top:260px;
        	}
        	a:link {
        		color:white;
				padding:16px 10px;
        	}		
			a:visited {
				color:white;
				padding:16px 10px;
			}	
			a:hover {
				color:white;
				padding:16px 10px;
				border-bottom:5px white solid;
			}	
			a:active {
				color:white;
				padding:16px 10px;
			}
			#advertisement{
				position:absolute;
				top:100px;
				right:100px;
			}

			button:hover{
				color:white;
				background-color:blue;
				cursor: pointer;
			}
        </style>
    </head>
    <body style="height: 100%">
    	<div id="content">
   			<div class="headFoot">
    			<ul style="height:20px">
    				<li ><a href="#">English</a></li>
    				<li ><a href="#">繁体</a></li>
    				<li ><a href="#">移动客户端</a></li>
    				<li ><a href="#">官方微博</a></li>
    			</ul>
    			<img id="logo" src="../images/logo.gif" height="68" width="160" alt="logo" style="float:left"/>
    			<a href="http://www.sinopecgroup.com/group/"><button class="button" id="button1">中国石油化工集团有限公司</button></a>
    			<a href="http://www.sinopec.com/listco/"><button class="button" id="button2">中国石油化工股份有限公司</button></a>
    		</div>
    		<div id="nav">
    			<div id="navColor"></div>
				<div>
					<img src="../images/pic_new2.jpg" height="306" width="960" alt="news">
					<img id="menuePic" src="../images/menu.png" height="51" width="960" alt="menue">
				</div>

					<table id="menue">
						<tr>
							<td><a href="#">关于我们</a></td>
							<td><a href="#">投资者关系</a></td>
							<td><a href="#">产品与服务</a></td>
							<td><a href="#">科技创新</a></td>
						</tr>
					</table>
    		</div>
    		<div id="advertisement">
    			<img src="../images/footer.gif" height="50" width="45" alt="advertisement">
    		</div>
    	</div>
    </body>
</html>
