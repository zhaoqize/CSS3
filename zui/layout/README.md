## 输入框
**思路**

一共分为24栏，分别为:
- zui-col-24(100%)
- zui-col-12(50%)
- zui-col-8(33.3333%)
- zui-col-6(25%)
- zui-col-4(16.66667%)

**问题**

在处理两栏布局的时候，设置div为inline-block，div之间会出现间隙
- 采用float布局来出来div，并通过伪类清除浮动(还是这种方式最好)
- 采用inline-block，在父元素上设置`font-size:0`
具体见:[how-to-remove-the-space-between-inline-block-elements](https://stackoverflow.com/questions/5078239/how-to-remove-the-space-between-inline-block-elements)

