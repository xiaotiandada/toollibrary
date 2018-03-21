### ToolLibrary 工具库

addEvent.js  来自于张鑫旭博客没有测试使用过 判断滚动方向 [传送门](http://www.zhangxinxu.com/wordpress/2013/04/js-mousewheel-dommousescroll-event/)

> 使用方法
``` bash
addEvent(dom, "mousewheel", function(event) {
    if (event.delta < 0) { alert("鼠标向上滚了！"); }
});
```

mousewheel.js 滚动方向判断插件

小栗子 [demo仓库](https://github.com/xiaotiandada/Case/tree/master/fullscreenscroll) [demo演示](https://xiaotiandada.github.io/Case/fullscreenscroll/)

> 使用方法
``` bash
dom.one('mousewheel', mouse_)

function mouse_(event) {
    if (event.deltaY < 0) {
        down()
    } else {
        up()
    }
}
```