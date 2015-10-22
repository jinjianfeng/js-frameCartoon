FrameCartoon
====================
version: 0.0.1

javascript 逐帧动画组件

[Check out the demo](http://gafish.github.io/demo/frameCartoon/)

## Example

###### HTML
```
    <div id="demo"></div>
```

###### JAVASCRIPT
```
  var frameCartoon = new FrameCartoon({
    el: '#demo', //必填，容器节点
    frameNum: 10, //必填，总帧数
    framerate: 24, //必填，帧速率
    url: 'demo.png', //必填，连续帧合并sprite图
    direction: 'horizontal', //可选，逐帧动画方向，默认为水平方向(horizontal)，也支持垂直方向设为 vertical
    iteration: 10, //可选，循环次数，infinite 为无限循环
    complete: function(){} //可选，每次动画完成回调
  });
```