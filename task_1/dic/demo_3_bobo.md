## demo_3

- float
元素的水平方向浮动，意味着元素只能左右移动而不能上下移动，元素在文档中的顺序就很重要了。

- 防止图片被鼠标拖动
 ```
 # CSS中
 -webkit-user-select:none; /*防止选中*/
 pointer-events: none; /*避免拖动*/
 # HTML5中
 < img src="1.jpg" alt="pic" draggable="false">
 # 或用背景插入
 ```

## demo_4

实现垂直居中
 
```
/* 外边包一个块元素，设置此元素 line-height: 100%; */ 
display:inline-block

/* 借用表格垂直居中（内容可变时选） */
display: table; 

display:table-cell;
vertical-align: middle;

/* 用绝对定位 */
position:absolute；
top:50%；
margin-top:-height/2；

```

- relative 定位中

只有设定父元素 height 值，才能使用 top 属性。