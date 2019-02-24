CSS 圣杯布局（双飞翼布局）

浮动、绝对定位和相对定位、负边距、弹性布局

页面实现左中右布局的实现方案：
兼容：
1、float，margin
   width: auto; // 宽度自适应，自动填充页面

2、position：absolute；
    中间部分绝对定位，左右浮动

3、HTML table表格（可以不算是css布局）
    使用表格td切割页面，实现自适应布局

4、dispaly: table
    css 表格布局，实现表格布局
        display: table;
        display: table-cell;

可能存在兼容问题：主要是针对IE浏览器
css3：
5、css 动态计算中间部分宽度
    calc

6、flex布局
   使用方便，但是可能存在兼容问题

