##一.基础知识
meta 标签分两大部分：HTTP 标题信息（http-equiv）和页面描述信息（name）。

####1.1 设定页面使用的字符集

```
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
```

####1.2

```
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
```
字段说明  


| First Header | Second Header | Third Header |
| ------------ | ------------- | ------------ |
| width | [pixel_value \| device-width]的宽度  | 范围[200 ~ 10000]|
| height | [pixel_value \| device-height ]  | viewport 的高度，范围[223 ~ 10000] |initial-scale:|float_value，|初始的缩放比例 （范围从 > 0 到 10）
|minimum-scale:|float_value，|允许用户缩放到的最小比例
|maximum-scale:|float_value，|允许用户缩放到的最大比例
|user-scalable:|[yes | no] |用户是否可以手动缩放
|target-densitydpi: |[dpi_value | device-dpi | high-dpi | medium-dpi | low-dpi] 目|


###标屏幕像素密度

`minimal-ui:`是iOS 7.1的safari添加的属性，会隐藏地址栏和导航栏

####1.3


```

<meta name="format-detection" content="telephone=no" />
```

忽略页面中的数字识别为电话号码

```
<meta name="format-detection" content="telephone=no，email=no,date=no" />
```
忽略页面中的email和时间

####1.4

```
<meta name="author" contect="liudanyun, liudy1024@163.com" />
```

设置作者姓名及联系方式

1.5

```
<meta http-equiv="Cache-Control" content="no-cache"/>
```
设置缓存 NO-CACHE

参考的链接有：

[http://www.cnblogs.com/liyunhua/p/4614251.html](http://www.cnblogs.com/liyunhua/p/4614251.html)

[http://ued.qunar.com/mobile/guide/mobile/2014/10/17/mobile-fe-dev-html.html
](http://ued.qunar.com/mobile/guide/mobile/2014/10/17/mobile-fe-dev-html.html
)


##二.实际中遇到的问题

```
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
```
设置`user-scalable=no` 没设置`maximum-scale=1.0` 在android中是可以防止用户缩放的，但是在ios中还是没作用，此时就必须加上`maximum-scale=1.0`






