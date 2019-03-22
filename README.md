# QCircleImg
自定义圆形图片

（https://github.com/qylfzy/QCircleImg/image/1.png）

## 准备工作

### 在project的build.gradle中添加
~~~
	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
~~~

### 在module的build.gradle中添加
~~~
implementation 'com.github.qylfzy:QCircleImg:v1.1'
~~~

### 使用方法
~~~
<com.qiyou.qcircleimageview.CircleImageView
        qiyou:q_img_scr="@drawable/my"
        qiyou:q_circle_border_width="6dp"
        qiyou:q_ciecle_color="@color/colorAccent"
        qiyou:q_show_border="true"
        android:layout_width="200dp"
        android:layout_height="200dp" />
~~~

### 说明

qiyou:q_img_scr 设置要显示的图片
qiyou:q_circle_border_width 设置外边框宽度 默认5dp
qiyou:q_ciecle_color 设置外边框颜色 默认黑色
qiyou:q_show_border 设置是否显示外边框 true显示 false不显示 默认为true


