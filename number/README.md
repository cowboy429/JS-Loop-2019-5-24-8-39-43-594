## 要求 
    
新建index.js文件，用任何一种方式写一个循环，实现以下需求：从0循环到20，分别判断该数是奇数还是偶数，并输出。输出结果如下：

```
1是奇数。
2是偶数。
3是奇数。
……
19是奇数。
20是偶数。
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>js9</title>
</head>
<body>
<script>
    for (var i=0;i<=20;i++){
        if (i%2==0){
            console.log(i+"是偶数")
        } else {
            console.log(i+"是奇数")
        }
    } 
</script>
</body>
</html>
