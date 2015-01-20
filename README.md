#MiNumToPic


## 目的


写了个简单的方法，利用精灵图片，把数字转化为设计师想要的字体。

## 资源需要

- 需要设计师按照![Alt text](http://page.zgenk.com/images/749979cbafb15117b47fd9ce417e9512.png)
- 横排排列
- 必须起点为0,按照顺序排列 
- 暂时不支持，小数点，负数等的显示


## 调用方法

> 假设已经引用jquery

```javascript
        //省略引入index.html中的numToPic方法
        $(function(){
            var imgurl="http://page.zgenk.com/images/749979cbafb15117b47fd9ce417e9512.png";
            numToPic(imgurl);//详见index.html
        });
```
```html
   <div class="J_minum" >
       234234
   </div> 
```

> 具体调用方法，以及实现逻辑,详见[index.html](https://coding.net/u/fyddaben/p/MiNumToPic/git/blob/master/index.html)

## 效果截图

![text](http://page.zgenk.com/images/5f46f05f7c8a5b58823dd07aa348a636.jpg)

