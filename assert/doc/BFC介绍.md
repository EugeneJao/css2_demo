#BFC介绍

## 概念

BFC全称block formatting context，中文为“块级格式化上下文”。

##特性

1. 渲染时内部元素不会影响BFC元素外部的元素。
2. 渲染时外部元素也不会影响BFC元素的内部元素布局。
3. BFC元素margin不会发生重叠。
4. BFC元素可以用来清除浮动带来的高度塌陷的影响。


##触发条件

1. html根元素
2. float值不为none
3. overflow为auto、scroll或hidden
4. dispaly的值为table-cell、table-caption、inline-block中的任何一个。
5. position的值不为relative和static。

##官网介绍
1. [w3c标准定义](https://www.w3.org/TR/CSS21/visuren.html#block-formatting)
2. [中文解释](https://www.zhangxinxu.com/wordpress/2015/02/css-deep-understand-flow-bfc-column-two-auto-layout/)