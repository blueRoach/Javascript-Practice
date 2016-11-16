# Javascript Practice
用原生JS实现常用的表单、图片、轮转、内容等操作。 
## chapter1 ：表单常用代码
* 去除字符串左右的空格
* 验证用户是否输入
* 禁止用户输入
* 关闭用户中文输入法
* 禁止用户复制和粘贴
* 限制只能输入数字
* 限制字符串长度
* 仿微博提示可输入剩余字数
* 换行文本自动滚动
* Ctrl + Return提交表单
* 文本内容进行关键字过滤
* 全选反选少选复选框
* 动态操作下拉选项
* 联级菜单
* 可添加的下拉选项

### chapter1总结:

#### 那些遗忘或者根本不知道的知识点们 ：

1. a.replace(b,c) 第二个参数c可以是函数，c的参数是所匹配到的值，函数的返回值便是替换值
2. oncopy onpaste 复制与粘贴事件；oninput 当用户尝试在input里输入时触发 等同于onkeydown+onkeyup
3. input 的禁止输入是  H5：disabled , H5前：disabled="disabled" ; 
maxlength 可以限制 input textarea最大value值
4. checked selected 判断复选框是否打开，下拉框是否选中。返回布尔值
5. selectedIndex 被选中索引 ; select.options 返回一个数组，所有的option值
6. 短路表达式 ：a && b 当a为fals返回false 否则返回b ;
  a || b 当a为true返回false 否则返回b

#### tips ：

1. a.replace(b,c) 第二个参数c可以是函数，c的参数是所匹配到的值，函数的返回值便是替换值
2. 当属性名是一个变量的时候，只能用“【】”，而不能用“。”
3. 可以通过innerHTML给元素直接添加子节点
4. 可以用value.length < 1 来判断为空
5. 一个布尔值变量可以当开关
6. o.parentNode.insertBefore（target,o.nextsibling）

#### 写在后面 ：

很早之前我就知道了豪情大哥这个练习项目，可我一直没用去做它。直到最近我很受挫，遇到很多问题我能想到但是做不出来，或者是突然忘记了一个知识点。
然后我就开始怀疑，我是不是不适合编程。感觉我什么都学过，但是又什么都不会。
之前也做过一些小项目，也在某公司实习过，但好像全都忘了。
突然发现，好像之前的都白学了。然后开始找原因。

* 看了很多书，虽然也是跟着敲但也只是跟着敲。
* 经常发现许多有趣的好玩的东西，却只是浅尝辄止，没用深入的去了解它，导致下次遇到好像从未遇见一般。
* 遇到困难根本很少去思考。

于是这次我是先自己实现功能，不管花多少时间查多少资料都要先实现后再与之对比，领会其精髓，再修改。
慢慢的我发现我已经有了思路，现在遇到问题，不会盲目的直接敲，会先分析想个大概再上手。一步一步，感觉所有东西都很简单。我想我是找到了正确的方向，
有了一点点的编程思想。
那就走下去吧！

## chapter2 ：常用图片相关代码

* 鼠标移入移出改变透明度
* 图片放大镜效果
* 点击图片逐渐放大
