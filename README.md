# CustomRatingBar
自定义评分组件

```
<TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="默认图片" />

    <com.dzq.widget.CustomRatingBar
        android:layout_width="200dp"
        android:layout_height="20dp"
        android:isIndicator="true"
        android:rating="2.5" />

    <com.dzq.widget.CustomRatingBar
        android:layout_width="200dp"
        android:layout_height="20dp"
        android:layout_marginTop="10dp"
        android:rating="2.5" />

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="20dp"
        android:text="自定义图片" />

    <com.dzq.widget.CustomRatingBar
        style="@style/CustomRatingBarStyle"
        android:layout_width="200dp"
        android:layout_height="20dp"
        android:numStars="7"
        android:rating="2.5" />
```

![image](https://github.com/dingzuoqiang/CustomRatingBar/blob/master/Screenshot_2017-08-09.png)
