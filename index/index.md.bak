<!doctype html>
<html lang="en">
	<head>
		<meta charset="UTF-8">
		<meta name="Keywords" content="">
		<meta name="Descritpion" content="">
		<title>廖茂金</title>
		<link rel="icon" href="images/favicon.ico" type='icon'>
		<style type="text/css">
			html{
				height: 100%;
				width: 100%;
				display:table;
			}
			body{
				background: url('images/login_bg2.jpg') center no-repeat;
				display:table-cell;
				height: 100%;
			}
			.top{
				height: 89px;
				width: 100%;
				background: url('images/logo_b.png') center no-repeat;
				margin: 100px auto 30px;
			}
			 .content{
				width: 380px;
				height: 340px;
				background: #fff;
				margin: 0 auto;
				position:relative;
				
			} 
			@keyframes Left{
				25%{left: -21px}
				50%{left: 15px}
				75%{left:-9px}
				100%{left:0}
			}
			.tt{
				width: 100%;
				height: 30px;
				background: #eff3f6;
				position:absolute;
			}
			form{
				width: 304px;
				margin: 0 auto;
				position:absolute;
				top: 60px;
				left: 0;
				right: 0;
				bottom: 0;
			}
			form input{
				width: 300px;
				height: 30px;
				margin-bottom: 15px;
				border-radius: 3px;
				text-indent: 42px;
				border: 2px solid #e5e5e5;
			}
			form p{
				margin: 0;
				height: 38px;
			}
			form .text{
				width: 124px;
				margin-top: 0;
				transform: translateY(-13px);
				text-indent: 10px;
			}
			form .id{
				background: url('images/zhanghao.jpg') no-repeat left;
			}
			form .pw{
				background: url('images/mima.jpg') no-repeat left;
			}
			form img,span{
				cursor: pointer;
			}
			form a{
				display: inline-block;
				width: 160px;
				height: 40px;
				position: relative;
				overflow: hidden;
				text-align: left;
				line-height: 40px;
				color: #fff;
			}
			form b:hover{
				right: -15px;
			} 
			form i{
				z-index: 10;
				display: inline-block;
				position: absolute;
				left: 0;
				top: 0;
				font-style: normal;
				width: 100%;
				height: 100%;
				text-align: left;
				text-indent: 42px;
			}
			form b{
				display: inline-block;
				width: 175px;
				height: 40px;
				background: url('images/sprites.png');
				position: absolute;
				right: 0;
				top: 0;
				z-index: 5;
				transition: .5s;
			}
			form .submit{
				text-align: center;
				margin-top: 30px;
			}
			.button{
				width: 300px;
				height: 30px;
				margin: 36px 0;
				border-top: 1px solid #aaa;
			}
			.button p{
				text-align: center;
				font-size: 12px;
				color: #aaa;
				padding-top: 6px;
			}
		</style>
	</head>
	<body>
		<div class="wrap">
			<div class="top"></div>
			<div class="content">
				<div class="tt"></div>
				<form action="a.php" name='form'>
					<input  name='id' class='id' type="text" placeholder='用户名'>
					<input  name='pw' class='pw' type="password" placeholder='密码'>
					<p><input class='text' type="text" placeholder='验证码'>
					<img src="images/recode.png" alt="">
					<span>刷新</span>
					</p>
					<p class='submit'>
						<a href="#">
							<i>登录</i>
							<b></b>
					   </a>
					</p>
					<div class="button">
						<p>Powered by 凡商易购 ©2016-2017</p>
					</div>
				</form>
			</div>
			
		</div>
	</body>
	<script>
		var oLog = document.querySelector('form i');
		var oCon = document.querySelector('.content');
		var oA = document.querySelector('form a');
		var oB = document.querySelector('form b');
		oA.onmouseover = function(){
			oB.style.right = '-15px';
		}
		oA.onmouseout = function(){
			oB.style.right = '0';
		}
		oLog.onclick = function change(){
			var x = document.querySelector('input').value;
			if(x==null || x==''){
				oCon.style.animation='Left .5s';
			}
		}
	</script>
</html>