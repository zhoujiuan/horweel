# horweel
改进horweel.js无法移除滚动条横向滚动


首先,需要horwheel:

var horwheel = require('horwheel');


然后,定义你的wrapper:

var wrapper = document.querySelector('#wrapper');


最后,执行horwheel函数包装器参数:

horwheel(wrapper);

独立的

另外，你可以在没有组件的情况下使用它。首先，添加独立文件：

<script src="../standalone/horwheel.js"></script>
然后,定义你的wrapper:

最后,执行horwheel函数包装器参数:

horwheel(wrapper);

删除滚动条横向滚动事件
horwheel(wrapper,"removeEvent");
