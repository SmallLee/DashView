# DashView

###一个在Android上实现绘制虚线的控件，可以指定虚线的样式以及方向

##效果图

###水平虚线

![img](https://github.com/SmallLee/DashView/blob/master/%E6%B0%B4%E5%B9%B3%E8%99%9A%E7%BA%BF.png)

###竖直虚线

![img](https://github.com/SmallLee/DashView/blob/master/%E5%9E%82%E7%9B%B4%E8%99%9A%E7%BA%BF.png)

#引入

```Java

dependencies {
    compile 'com.fang:dashview:v1.0.0'
}
```

##使用

```Java
 <com.fang.dashview.DashView
        android:layout_marginLeft="40dp"
        android:layout_width="wrap_content"
        android:layout_height="300dp"
        app:dashWidth="2dp"
        app:lineWidth="4dp"
        app:lineColor="@android:color/holo_green_light"
        app:dashOrientation="1"
        app:lineHeight="1dp"
        />
```
###属性介绍

```Java
dashWidth:两段线段之间的间距
lineWidth:每条线段宽度
lineColor:线段颜色
dashOrientation:虚线方向 0，水平，1，竖直
lineHeight:线段高度
```

##注意事项
当设定虚线的方向时，对应方向的wrap_content显示效果为match_parent,因为在实际情况中，虚线的尺寸总是固定的数值。




