## 如何用CSS3实现按钮动画

这段时间在学习CSS3，所以在完成一个小demo之后做一个学习记录

光通过`<a>`标签只能实现静态按钮，所以我们通过借助另外的标签来实现效果。

CSS3 有新的 `transform` 属性，下面介绍一下这个属性。
1.translate(x,y)　平移向右x，向下y
2.rotate(angle)　旋转　angle角度，可为负值
3.scale(a)　缩放　a比例

transition-property 规定设置过渡效果的 CSS 属性的名称。

transition-duration 规定完成过渡效果需要多少秒或毫秒 

transition-timing-function 规定速度效果的速度曲线 linear 匀速 ease 慢快慢 

transition-delay 定义过渡效果何时开始

z-index 属性设置元素的堆叠顺序。拥有更高堆叠顺序的元素总是会处于堆叠顺序较低的元素的前面。


效果实现：

![双斜边动画](http://i2.buimg.com/567571/cc5ecce822e8f2fe.gif)
![斜边动画](http://i2.buimg.com/567571/5be4297783f053fb.gif)
![圆角动画](http://i2.buimg.com/567571/33520b07b7e4c741.gif)
-----
参考demo：button.html