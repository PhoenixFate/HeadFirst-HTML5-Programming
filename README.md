# Head First HTML5 Programming 
> 第一版 代码
```
电子书地址：

百度网盘：
https://pan.baidu.com/s/1in00XOmjJo6-CnvPnINl2w

提取码
9cc2
```

### html4->html5
+ 
```
    old: <!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">
    new: <!doctype html>
```
+
```
    old: <link type="hext/css" rel="stylesheet" href="lounge.css">
    new: <link rel="stylesheet" href="lounge.css">
    old: <script type="text/javascript“ src="lounge.js"></script>
    new: <script src="lounge.js"></script>    
```
+
```
    old: <meta http-equiv="content-type" content="text/html;charset=UTF-8">
    new: <meta charset="utf-8">
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
+ 获得dom
    window.getElementById("xxx")
    window.getElementByTagName("head")[0]    

+ 创建元素
    window.createElement("li");
    window.createElement("script")
+ 元素设置属性
    element.setAttribute("src")
    element.setAttribute("id")
    element.setAttribute("href")
    element.setAttribute("class")
+ 将一个元素插入到指定元素的子节点中
   var ul=window.getElementById("playList");
   ul.appendChild(li)//尾插法
+ 替换dom节点
    window.replaceChild(newElement,oldElement);
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
