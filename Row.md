### Row

####  源码解析

```
Row({
  Key key,
  MainAxisAlignment mainAxisAlignment = MainAxisAlignment.start,
  MainAxisSize mainAxisSize = MainAxisSize.max,
  CrossAxisAlignment crossAxisAlignment = CrossAxisAlignment.center,
  TextDirection textDirection,
  VerticalDirection verticalDirection = VerticalDirection.down,
  TextBaseline textBaseline,
  List<Widget> children = const <Widget>[],
})
```

- mainAxisAlignment：主轴方向的对齐方式，分别有：start、center、end、spaceAround、spaceBetween、spaceEvenly
- crossAxisAlignment：在交叉轴的对齐方式，默认居中
- mainAxisSize：在主轴方向上占有多少空间，默认max
- textDirection：阿拉伯语系的兼容设置，一般无需处理
- verticalDirection：定义了children摆放顺序，默认是down



#### 其他

- 使用SizedBox保持固定的间距
- 使用Space填充尽可能大的空间