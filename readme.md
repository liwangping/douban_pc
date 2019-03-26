PC moblie
flex 在一些老的浏览器，IE10+
布局： float 撑起来pc布局

float 会离开文档流
BFC
float 离开文档流跟position:absolute不一样
float 是魔鬼 会影响兄弟元素

两列式布局，除了float还有inline-block

white-space: nowrap;/*文字不换行*/
    overflow: hidden;
    text-overflow: ellipsis;
这三行可以实现将多出一行的内容变成...三个点。

 /* img超出 ，对图片的操作    */
    overflow: hidden;
    white-space:nowrap;

letter-spacing: normal; 字间距为0

注：对于两个inline-block中的元素来说，虽然说子div将父容器分割成了40%和60%可由于存在div之间的
换行的转义字符的存在，所以会产生间隔，所以他们排布在两行上，两种解决方法
1. 将源代码中div之间的换行删去
2. 将父容器的font-size置为0,这样的换行符大小也为0;，不必担心子容器，可以相应的设置font-size.

- 在以往的网页编写中，语义化很重要，标签为特定标签。
如section划分为大片区域
wrapper划分小型区域，
mod为小的模块化的区域
另外学习了整体css的规范化书写
/*
 * auth ysw
 * date 2019-3-26
 */
/*reset*/
针对性的重置可以提高浏览器的运行效率
另外对a标签的下划线去除之类的一种优化。形成一种整体风格
  /* 通用样式 */
这里一般是通用的样式。主要是布局的大体。
/*组件样式  框架*/

  /*业务样式*/
每天主要更改的是这个，具体的某个页面的样式。

另外页面的实现一定是移动优先