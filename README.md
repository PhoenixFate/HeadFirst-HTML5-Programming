#Head First HTML5 Programming 源码
## 个人学习使用

### html4->html5
+ 
```
    https://www.baidu.com/s?wd=idea+%E9%80%89%E4%B8%AD%E4%B8%80%E8%A1%8C&tn=84053098_3_dg&ie=utf-8
    <!doctype html>
```
+
```
    <link type="hext/css" rel="stylesheet" href="lounge.css">
    <link rel="stylesheet" href="lounge.css">    
```
+
```
    <meta http-equiv="content-type" content="text/html;charset=UTF-8">
    <meta charset="utf-8">
```

### javascript
+ 加载完页面之后，执行脚本
    window.onload=xxx
+ button绑定电击事件 
    button.onClick=xxx
+ 修改dom节点
    window.getElementById("xxxx").innerHTML="xxxx"
+ 获得表单输入值
    window.getElementById("sss").value;
+ 创建元素
    window.createElement("li");
+ 将一个元素插入到指定元素的子节点中
   var ul=window.getElementById("playList");
   ul.appendChild(li)//尾插法
   
+ 匿名函数
    function(abc){}
    var f=function(){}
    
+ 对象
   1. 创建对象--使用{ } 创建对象
   var obj={name:"abc",email:"ss"}
   var obj=new Object()
   2. 访问对象属性
   obj.name
   obj["name"]
   3. 枚举对象的所有属性
   for(prop in obj){ //prop是key值}
   4. 删除对象属性
   delete obj.name
