# HiZoom

> HiZoom: 一个简单，易用，轻量（3KB）的jQuery放大镜插件。



**[English](./README.md)**

#### 特性

------

- 简单：文档详细清楚，直接上手
- 轻量: 压缩后的文件仅仅**3KB**，是 MagicZoom 插件的 **1/24**
- 兼容性强：Chrome，Firefox，Safari，IE9+



#### 依赖

------

- jQuery



#### 开始

------

```shell
// 下载项目
git clone https://github.com/javashop/HiZoom.git
```

在项目中直接引入

```Html
<!-- 其余代码省略... -->
<link rel='stylesheet' href='./hizoom.min.css'>

<div class='hizoom gakki'>
  <img src='./gakki.png'>
</div>
<div class='hizoom ldy'>
  <img src='./ldy.png'>
</div>

<script>
  // 调用
  $('.gakki').hiZoom({
    width: 400,
    position: 'right'
  });
  $('.ldy').hiZoom({
    width: 300,
    position: 'left'
  });
</script>
```



#### 可选配置

------

| 属性         | 描述                    | 可选值                      | 默认值   |
| ---------- | --------------------- | ------------------------ | ----- |
| width      | 放大镜容器的宽高（目前只支持正方形放大镜） | 任何正数                     | 400   |
| position   | 被放大区域的位置              | left\|right\|top\|bottom | right |
| background | 放大镜背景色                | 合法CSS颜色值                 | #FFF  |
| opacity    | 放大镜透明度                | 0~1（合法CSS值）              | 0.7   |
| distance   | 被放大区域和放大镜容器间的距离       | 任何正数                     | 20    |



#### 待完成

---

* 处理长方形图片放大
* 自定义放大倍数
*  . . . 



# Javashop出品

本开源产品源自优质网店系统供应商：Javashop（ http://www.javamall.com.cn ）
