# jsp
3-2
```
<%@ page contentType="text/xml;charset=utf-8" %>
<html>
<head>

<title>



Directives Tag



</title>




</head>




<body>
<h2>contentType 디렉티브 </h2>
<h4>text/html:HTML 출력 </h4>
<h4>
charset=utf-8</h4>
</body>
</html>


```
3-3
```
<html>
<head>

<title>



Directives Tag



</title>




</head>




<body>
<%@ page import="java.util.Date" %>
Today is <%=new Date() %>




</body>
</html>

```
3-4
```
<html>
<head>

<title>



Directives Tag



</title>




</head>




<body>
<%@ page buffer="16kb" %>
Today is <%=new java.util.Date() %>




</body>
</html>
```
