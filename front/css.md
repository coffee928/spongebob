## 布局

### float

* float会让父元素高度塌陷

    - 文字环绕

* 清除浮动

  >清除浮动带来的影响
  
  1. 底部插入 clear: both
    - div
    - .clearfix:after {}
    - IE6/7 .clearfix {*zoom: 1;}
  
  2. BFC  / haslayout
  

* 浮动带来的影响
    - 使元素block化
    - 去空格化

### position
* position:relative     
    - 相对定位相对的是它原本在文档流中的位置而进行的偏移;
    - relative定位也是遵循正常的文档流，它没有脱离文档流，但是它的top/left/right/bottom属性是生效的;
    - 可以说它是static到absoult的一个中间过渡属性；
    - 最重要的是它还占有文档空间，而且占据的文档空间不会随 top / right / left / bottom 等属性的偏移而发生变动
    
        ```
        定位自身
        无侵入定位，可以用来做拖拽
        
        top bottom 和 left right 同时存在的表现：
        
        绝对定位是拉伸，相对定位是斗争
        top  > bottom
        left > right
        
        使用原则：
        尽量不使用
        最小化
        ```
* position:absolute
    - 相对于其包含元素的位置而言
* position:fixed
    - 相对于浏览器窗口
