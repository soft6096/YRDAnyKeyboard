一, 功能如下
a, 支持 价格，手机号，座机电话，身份证等场景下的数字键盘 </br>
b, 支持 确定键 智能启用（依据的文本框的内容长度） </br>
c, 支持 所有的按键回调(YRDAnyKeyboardDelegate) </br>
d, 支持 UITextFieldDelegate 和 YRDAnyKeyboardDelegate 独立回调 </br>


二, 依赖的第三个类库 </br>
a, Aspects 切面编程框架</br>


三, 兼容性
a, 系统实测兼容 iOS7 +
b, 屏幕实测兼容 iPhone4 +

四, todo list
a, 删除功能建的 long press 快速删除文档框内容 </br>
b, 兼容到 UIKeyboardType 中 </br></br></br></br>

五, 修改的问题
5.1 , 增加了UITextField (Helper)分类，修正了textField: shouldChangeCharactersInRange: replacementString: 中的range参数，更精准定位光标位置，而不是之前的textField.text的长度所在的位置，感谢大家的反馈 

真机演示如下:kiss:</br>
![Image of Demo](https://raw.githubusercontent.com/276452915/YRDAnyKeyboard/master/AnyKeyboard.gif)