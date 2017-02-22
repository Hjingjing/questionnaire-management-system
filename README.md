做按钮是要更改radio的默认样式和颜色
<input id="radio"  type="radio" name="age" /><label for="radio"><span><span></span></span></label>
几个关键点：
（1）设置input的opacity为0。
（2）在input后面添加一个label，for属性绑定input的id。
（3）在label中加入两个<span>标签，内部标签负责checked样式，外部负责未选中样式边框。然后在css中修改想要的样式就可以了，样式类似这个样纸。
