## 要求 

新建index.js文件，写程序输出9*9乘法表。输出结果如下：

```
1*1=1
2*1=2 2*2=4
3*1=3 3*2=6 3*3=9
……
9*1=9 9*2=18 9*3=27 …… 9*9=81
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>js8</title>
</head>
<body>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>乘法表</title>
    <script type="text/javascript">
        //用表格形式显示一个九九乘法表
        document.write("<table>");
        for (var x = 1; x <= 9; x++)
        {
            document.write("<tr>");
            for (var y = 1; y <= x; y++)
            {
                document.write("<th>"+y+"*"+x+"="+y*x+"</th>");
            }
            document.write("</tr>");
        }
        document.write("</table>");
    </script>
</head>
<body>
</body>
</html>

