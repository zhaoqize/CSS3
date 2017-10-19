## 时间下拉选择框
**效果图**


**dom结构**
![dom](../images/time-picker.png)
![dom](../images/time-picker.png =100x100)
<img src="../images/time-picker.png" width = "300" height = "200" alt="图片名称" align=center />

**思路**
- 效果移入input区域，右侧文字(图标)变化，border变色(不要使用outline来做)
- 点击input区域缓动出现下拉列表

**如何控制滚动条样式**

一种就是在原来的content基础上，将content上下延伸出去十几个像素，然后自己写滚轮，这样兼容性最好!
![dom](../images/picker1.png)