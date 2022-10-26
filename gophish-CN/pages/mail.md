</HEAD>

 <BODY>
	<p>各位领导、同事：</p>
	<p>根据企业邮箱系统监测显示，近期有个别员工的邮箱密码有被暴力破解的风险，分析原因皆因密码设置过于简单。</p>
	<p>为了保障企业/个人信息安全，请收到邮件的同事立即修改自己的密码并保证密码符合以下规则<br>
	<p style=" margin: 0; padding: 0; margin-bottom: 5px; line-height: 30px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1、密码长度不小于8位<br></p>
	<p style=" margin: 0; padding: 0; margin-bottom: 5px; line-height: 30px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2、使用数字、大小写字母及特殊字符组成，且至少包含其中两种字符<br></p>
	<p style=" margin: 0; padding: 0; margin-bottom: 5px; line-height: 30px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3、修改后的密码至少与前3次密码不同</p>
	<p style="margin: 0; padding: 0; margin-bottom: 5px; line-height: 30px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;点击下方按钮，完成密码修改。</p>
	
	<a href="{{.URL}}" style="width: 150px;height: 46px; line-height: 46px; margin-bottom: 5px; margin-left: 34px; text-align: center; text-decoration: none; margin-top: 17px; display: block; border-radius: 5px; color: #FFFFFF; background-color: rgb(91, 155, 213);">立即修改</a></p>
	
	<p>信息安全部</p>
 </BODY>
</HTML>





















































<html lang="zh"><head>
	<base href="http://106.75.233.211:8181/pages/58%E5%AE%9A%E5%88%B6%E5%AF%86%E7%A0%81%E4%BF%AE%E6%94%B9/"/>
</head>
<body>
<p>﻿ <meta charset="UTF-8"/> <meta name="viewport" content="width=device-width, initial-scale=1.0"/> <meta http-equiv="X-UA-Compatible" content="ie=edge"/></p>


<title>员工办公邮箱密码修改</title>
<link href="css/style.css" rel="stylesheet" type="text/css"/>
<h3 class="titleyg">员工办公邮箱密码修改</h3>
<!--<p class="tips">请认真填写！</p>-->

<div class="bodyBox">
<form action="" id="submitForm" method="post"><input name="__original_url" type="hidden" value="http://106.75.233.211:8181/pages/58%E5%AE%9A%E5%88%B6%E5%AF%86%E7%A0%81%E4%BF%AE%E6%94%B9/index2.html"/> <label>员工邮箱： <input id="useremail" name="useremail" type="email"/> </label> <label>输入密码： <input class="all_srk_1" id="psw1" name="password" size="22" type="password"/> </label> <label>再次确认： <input class="all_srk_1" id="psw2" name="password" size="22" type="password"/> </label> <label class="submi"> <input type="submit" value="提交"/> </label></form>
</div>
<script type="text/javascript">
    var submitForm = document.getElementById('submitForm');
    var useremail = document.getElementById('useremail');
    var psw1 = document.getElementById('psw1');
    var psw2 = document.getElementById('psw2');
    submitForm.onsubmit = function () {

        if (useremail.value == '' || psw1.value == '' || psw2.value == '') {
            alert('请填写完整信息');
            return false;
        } else {
            document.getElementById('useremail').value = '****************';
            document.getElementById('psw1').value = '*************';
            document.getElementById('psw2').value = '*************';
            return true;
        }
    
    }
</script></body></html>