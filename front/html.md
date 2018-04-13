## 块级元素 & 内联元素

* 块级元素在浏览器显示时，通常会以新行来开始（和结束）

```html
<h1>, <p>, <ul>, <table>
```

* 内联元素在显示时通常不会以新行开始

```html
<b>, <td>, <a>, <img>
<span>
```

## HTML5

* SVG 与 Canvas两者间的区别

    - SVG 矢量图优点：
        + 不失真，放大缩小图像都很清晰
        + 学习成本低，也是一种 DOM 结构
        + 使用方便，设计软件可以直接导出
        + SVG功能更完善，适合静态图片展示，高保真文档查看和打印的应用场景
    - Canvas 像素图
    优点（在元素特别多的情况 1000+）：
        
        + 性能高，可以自己控制绘制过程，还能使用 WebGL
        + 可控性高，像素级控制
        + 内存占用恒定，就是像素点个数
        + Canvas提供的功能更原始，适合像素处理，动态渲染和大数据量绘制


### 新属性

### 本地存储

### 缓存

### 本地 SQL 数据

### XHTMLHttpRequest 2