# DashView

###一个在Android上实现绘制虚线的控件，可以指定虚线的样式以及方向

##效果图

###水平虚线

![img](https://github.com/SmallLee/DashView/blob/master/%E6%B0%B4%E5%B9%B3%E8%99%9A%E7%BA%BF.png)

###竖直虚线

![img](https://github.com/SmallLee/DashView/blob/master/%E5%9E%82%E7%9B%B4%E8%99%9A%E7%BA%BF.png)

##使用

```Java
 <com.thomas.dashview.DashView
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
当设定虚线的方向后，对应方向的属性的模式就要设置为EXACTLY,例如当前为水平虚线，那么控件的layout_width属性就必须为match_parent或者固定数值




