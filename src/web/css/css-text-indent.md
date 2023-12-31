# 段落首行缩进

## 业务需求

实现类似 Word 文档，段落首行缩进效果。

![](./images/css-text-indent/Snipaste_2021-06-11_12-00-37.png)

## 解决方法

如果使用空格替代，感觉不是非常好，并且在不同端展示的效果无法保证。

我们可以使用 css 中的一个属性 `text-indent` 来实现首行缩进效果，同时搭配 `em` 单位来实现缩进同等字符大小。

```html
<body>
  <div>
    <span>
      今天（6月11日），国家航天局举行天问一号探测器着陆火星首批科学影像图揭幕仪式，公布了由“祝融号”火星车拍摄的着陆点全景、火星地形地貌、“中国印迹”和“着巡合影”等影像图。首批科学影像图的发布，标志着我国首次火星探测任务取得圆满成功。
    </span>
  </div>
  <style>
    div {
      width: 300px;
      text-indent: 2em;
    }
  </style>
</body>
```
