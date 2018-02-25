# Richiezhong.github.io
# This is a project for my personal blog.
<!DOCTYPE html>
<html>
<body>

<form action="/example/html5/demo_form.asp" id = "form1" method="get" autocomplete="on">
Fisrt name:<br>
<input type="text" name="firstname" value = "John"  size="40" required="required">
<br>
Last name:<br>
<input type="text" name="lastname" value ="Richie" maxlength="10" autofocus><br>
<input type="image" src="/Users/zhongzhehao/Desktop/WechatIMG9293.jpeg" alt = "Submit" width="128" height="128"><br>
Choose picture: <input type="file" name="img" multiple="multiple" />
<input type="submit" />
<br>
Numbers: <input type="number" name ="points" step="3">
</form>

Latst name: <input type ="text" name ="lame" form ="form1">
<br>

Country Code: <input type = "text" name="country_code" pattern="[A-Za-z]{3}" title="Three letter country code" form="form1">
</body>
</html>
