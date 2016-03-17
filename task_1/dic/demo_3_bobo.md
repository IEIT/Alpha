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