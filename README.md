javascript_clock
================
<html>
<head>
<title>Clock</title>
<script language="JavaScript">
function clock_form()
         {
	 day=new Date()
	 clock_f=day.getHours()+":"+day.getMinutes()+":"+day.getSeconds()
	 document.form.f_clock.value=clock_f
         id=setTimeout("clock_form()",100)
	 }
</script>
</head>
<body bgcolor="ffffff" onLoad="clock_form()">
<center>
<form name=form metod="get">
<input name=f_clock maxlength=8 size=8>
</form>
</center>
</body>
</html>
