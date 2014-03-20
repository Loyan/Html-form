<html>
<head>
<meta http-equiv="Content-Type" content="text/html; charset=windows-1251"/>
 <link rel="stylesheet" media="screen,projection,tv" href="//support.cdn.mozilla.net/static/css/common-min.css?build=f7d846f" />
<title>Форма</title>
</head>
<body bgcolor="">
<script type="text/javascript">
function poschitat(){
var marka_tovara=1;
alert(document.forms[0].marka[2].checked)
if (document.forms[0].marka[0].checked==true){
marka_tovara=0;}
if (document.forms[0].marka[1].checked==true){
marka_tovara=1;}
if (document.forms[0].marka[2].checked==true){
marka_tovara=2;}
if (document.forms[0].marka[3].checked==true){
marka_tovara=3;}
alert(marka_tovara)
}
</script>
<p>
<form method="GET" action="login.php" enctype="multipart/form-data" name="login">
<BR><B><Big>Registration</Big></B></BR>
<input type="text" name="login" size="20"maxlength="30"><B>Login</B><BR>
<input type="password" name="password"><B>Password</B><BR>
<br><input type="checkbox"><B>Замовити</B>
<br><input type="checkbox"><B>Замовити</B>
<br><input type="checkbox"><B>Замовити</B>
<H3>Оберіть марку кросівок</H3>
<input type="radio" name="marka" value="Nike">Nike<Br> 
<input type="radio" name="marka" value="Addidas">Addidas<Br>
<input type="radio" name="marka" value="Puma">Puma<Br>
<input type="radio" name="marka" value="Reebok">Reebok<Br>
<B>Кількість</B> <input type="text" name="login" size="20"maxlength="30"><BR>
</p> 
<H3>Оберіть місто доставки</H3>
<select name="region">
<option value="1" selected>Київ</option>
<option value="2" selected>Донецьк</option>
<option value="3" selected>Львів</option>
<option value="4" selected>Чернігів</option>
<option value="5" selected>Одеса</option>
<option value="6" selected>Харків</option></select>
<br><br><input type="button" value="Порахувати" onclick="poschitat()">
<input type="button" value="Замовити">
<H3>Залишіть свій відгук</H3>
<textarea name="vidguk" cols="25" rows="3"> </textarea>
<input type="text" id="123">
</form>
</body>
</html>
