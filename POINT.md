## class的命名
- 命名形式：zui-btn-primary [ui名称+html元素+属性/皮肤]
	- zui-form-select -> zui-form-selected
	- zui-form-checkbox
	- zui-form-radio

## 添加class的哲学
- 一般将class类添加在父类,通过`.zui-form-checkbox dl`的向下选择子类的形式进行操作
- 圆角UI一般不用百分比的形式去做，使用px
- css的叠加原则取决于该class在文件中的定义顺序，后面的覆盖前面的
- tap-highlight-color
- @keyframes
- animation
	- animation-iteration-count 规定动画的播放次数
- cursor:not-allowed!important 鼠标禁止的手势
	- `button`元素可以使用这个避免点击行为,其他的则不行(需要使用js控制)
- 注意`font-size:0`的使用

## CSS3
CSS3动画特效区域

### CSS-图片旋转和放缩
- 使用的css属性：transform,transition
- 使用方法:
具体参见:[transform](http://www.w3school.com.cn/cssref/pr_transform.asp) ,[transition](http://www.w3school.com.cn/cssref/pr_transition.asp)
- 兼容性:
- transform:

	ie10,firefox,opera支持

	ie9支持-ms-transform（仅支持2d）

	safari和chrome支持-webkit-transform(支持2d和3d)

	opera仅持2d
	
- transition:

	e10,firefox,opera,chrome支持

	safari支持-webkit-transition
	
	ie9以及更低版本不支持

