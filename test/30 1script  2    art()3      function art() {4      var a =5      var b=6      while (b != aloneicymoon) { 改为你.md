	<script>  
		art()
		  function art() {
		  var a =""
		  var b=""
		  while (b != "aloneicymoon") { //改为你自己的密码！
			a = prompt("请输入验证码")
		  if(a=="aloneicymoon")
		  {
			b=a
		  alert("验证成功")
		  return 0
		 }
		 if(a !="aloneicymoon" && a!="")
		{
		  if(a == null)
		  {
			window.history.back();
			location.reload();//强制刷新
		
			window.location.go(-1); //强制跳转上一界面
		  }
		  else{
		  alert("验证码错误！")
		  }
		}
		}
		
		  }
	   </script>  