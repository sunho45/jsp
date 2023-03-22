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
3-5
```
%@ page contentType="text/html; charset=utf-8" %>
<html>
<head>

<title>



Directives Tag



</title>




</head>




<body>
<%@ page info="Date 클래스를 이용한 날짜 출력하기"%>
Today is <%=new java.util.Date() %>






</body>
</html>

```



3-6
```
<html>
<head>

<title>



Directives Tag



</title>




</head>




<body>
<% String str=null;
out.println(str.toString());%>






</body>
</html>
```
3-7
```
%@ page contentType="text/html;charset=utf-8" %>
<%@ page isErrorPage="true" %>
<html>
<head>

<title>



Directives Tag



</title>




</head>




<body>

<h4>에러가 발생했습니다.</h4>
<h5> exception 내장 객체 변수</h5>
<% exception.printStackTrace(new java.io.PrintWriter(out)); %>







</body>
</html>
```
