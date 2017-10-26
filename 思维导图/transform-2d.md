# transform-2d



## transform	

主要就是三个方法

语法

translate:移动 第2个参数不传默认为0

transform;translate(x,y);

scale:缩放  传递的是比例 比如1倍  0.5倍等

transform:scale(x,y);

rotate:旋转 传递的是角度 360deg等于一圈

transform:rotate(45deg);

skew:斜方向扭曲   传递的是角度  360deg等于一圈 第2个参数不传默认为0

transform:skew(xAngle,yAngle);

对个值通过空隔分隔

transform:translate(10px,10px)  rotate(180deg)   scale(1.5,1.5);

# transform-orgin

这个属性指定的是移动时，以什么原点作为标准

语法：

x:50px   y:中心 作为原点

transform-orgin:50px;

x:50px  y:50px 作为原点

transform-origin:50px 50px;

x:10% y:20% 作为原点

transform-origin:10% 20%;

传入的单词

可选：top left right  center  bottom

左上作为原点

transform-orgin:left top;

`中心作为原点

transform-origin:center center;









 



