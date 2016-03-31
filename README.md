# HyBy
##Layout
```
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:orientation="vertical"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context="com.baylrock.trainingtasks.happybirthday.MainActivity">

    <TextView
        android:layout_weight="1"
        android:gravity="center"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:fontFamily="sans-serif-light"
        android:textSize="36sp"
        android:padding="5dp"
        android:textStyle="bold"
        android:textColor="@color/title_text"
        android:background="@color/title_bg"
        android:text="@string/jams" />
    <ImageView
        android:layout_weight="50"
        android:id="@+id/bg"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:scaleType="centerCrop"
        android:src="@drawable/hb"
        android:contentDescription="@string/bg_img" />
    <TextView
        android:gravity="center"
        android:layout_weight="1"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:fontFamily="sans-serif-light"
        android:textSize="36sp"
        android:padding="5dp"
        android:textStyle="bold"
        android:textColor="@color/title_text"
        android:background="@color/title_bg"
        android:text="@string/from_vlad"/>
</LinearLayout>
```

##Result
![alt tag](http://i.prntscr.com/e54f5513b83a4ad5bd16abb41a233cd1.png)
