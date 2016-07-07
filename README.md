# 基于jquery的拖拽插件！

    抄抄改改，写了个简单的拖拽，旋转，放大缩小的小插件!很丑!
    先加载jquery,再加载drag.js
    <script src="jquery.js"></script>
    <script src="drag.js"></script>

#### 使用

##### html

    <div class="palette" style="width:600px;height:600px;background:#ccc;position:relative;margin:0 auto">
        <div class="box" id='box1'>
            <div class="coor_4"></div>
            <div class="rotate"></div>
            1
        </div>
    </div>

##### js

    var div1 = new Drag({
            plant: $('.palette'),
            div: $('#box1'),
            coor: '.coor_4',
            rotate: '.rotate'
        });