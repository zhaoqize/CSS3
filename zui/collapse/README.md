## 基础手风琴
**dom结构图**
![dom](../images/collspse.png)

**思路**
- 这样具有明显层次结构的dom，在命名的时候注意尽量使用比较语义话的单词
- 使用独立的`zui-show`类来处理展开
- 每次点击时，给该点击行添加`zui-show`，其他都移除
- 动效通过过渡属性`transition: all .2s`实现


