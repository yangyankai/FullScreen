# FullScreen
Android 全屏

在Android 开发中全屏显示的方式有三种，分别介绍如下：
1、在Activity中进行设置，代码如下：
getWindow().setFlags(WindowManager.LayoutParams.FLAG_FULLSCREEN, WindowManager.LayoutParams.FLAG_FULLSCREEN);
此行代码必须写在Activity指定布局文件之前，否则会报错误。
2、在android项目的主配置文件的application的属性中设置，设置方式一：
android:theme="@android:style/Theme.NoTitleBar.Fullscreen"
3、在android项目的主配置文件的application的属性中设置，设置方式二：
android:theme="@style/fullscreem"
