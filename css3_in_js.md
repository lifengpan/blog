# css3 js transform

> 准备写一个js操作transofrm的工具，虽然用的不多.但是项目里确实要用到


.  第一步先搞清楚css3最方便多操作，1）一次性操作多个属性 ， 入 rotate(30deg) translate(10px, 20px) 2）单个操作如rotate(90deg)
.  操作常用多步骤1）可以直接操作matrix 2）分析字符串，但是区分2d和3d时情况很多，比较麻烦


> css3变换其实就是坐标多变换，说白了就是矩阵运算


# 文档相关

[css3-v0.3.js](https://github.com/chunnallu/Css3js/blob/master/css3-v0.3.js)

[controlling-css-animations-transitions-javascript](https://css-tricks.com/controlling-css-animations-transitions-javascript/)

[all-the-transform-ways](http://danielcwilson.com/blog/2017/10/all-the-transform-ways/)

[sylvester](https://github.com/jcoglan/sylvester/tree/master/src)

> 矩阵相关

[matrix](https://github.com/mljs/matrix/tree/master/src)

[matrix](https://github.com/mil-tokyo/sushi/blob/master/src/sushi.js)


*****[rematrix](https://github.com/jlmakes/rematrix)*****

> 这个可以直接用来生成 css所需要多矩阵


> [dynamics](https://github.com/michaelvillar/dynamics.js)

> coffee 写的缓动动画，但是我这里只需要transform相关的


> https://github.com/bcherny/transform-to-matrix/blob/master/transform-to-matrix.js


> https://jellybo.com/articles/article4.php

> https://github.com/Zhangdroid/CSS-Matrix3d/blob/master/src/index.js


> https://developer.mozilla.org/zh-CN/docs/Web/API/WebGL_API/Matrix_math_for_the_web

> https://github.com/mattdesl/tween-css-transform

> https://github.com/daniel-lundin/snabbt.js/blob/master/src/matrix.js

> https://gist.github.com/shogito/8436825

> https://en.wikipedia.org/wiki/Transformation_matrix
