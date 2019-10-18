# Python-HTML-Gen
Quick and easy way to generate HTML files on the fly.

Make the HTML dynamic by inserting strings like this:
```
str1 = "Hello"
str2 = "World!"

contents = '''<!DOCTYPE html PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN">
<html>
<head>
  <meta content="text/html; charset=ISO-8859-1" http-equiv="content-type">  
</head>
<body>
%s, %s
</body>
</html>
''' % (str1, str2)
```

The resulting HTML:
```
<!DOCTYPE html PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN">
<html>
<head>
  <meta content="text/html; charset=ISO-8859-1" http-equiv="content-type">  
</head>
<body>
Hello World!
</body>
</html>
```
