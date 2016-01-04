#介绍
1: LoopView<br />
2: LoopViewPager（新增）<br />
可以无限循环，自动旋转，停靠的3D旋转布局控件,无需编写代码，直接在布局中加入自己的布局即可。<br />
仅使用三角函数,使用ValueAnimation,继承FrameLayout.兼容所有滑动组件<br />
##[点击下载最新版本jar文件   jar file](https://github.com/zhuxiujia/LoopView/blob/master/loopview-1.4.1.jar?raw=true)<br />
<br />
![image](demo.gif)
##优势
*3d旋转GrallyView，继承FrameLayout<br />
*LoopViewPager不仅支持无限循环，还支持左右和上下切换，同时支持Handler实现的自动切换
*支持使用Handler实现的自动旋转，相比使用线程更加节省性能<br />
*可直接在xml添加元素即可添加列数据。无需编写代码添加<br />
*优良的兼容性，和尺寸控制<br />
##如何使用？
###Step1:导入jar文件到项目
###Step2:在你的layout目录下编写加入你的xml文件
        <com.cry.loopviews.LoopView
        android:layout_width="fill_parent"
        android:layout_height="fill_parent"
        android:gravity="center_vertical"
        >
              <!--此处添加你的任意View或者layout元素 -->
        <ImageView
        android:layout_width="200dp"
        android:layout_height="200dp"
        android:src="@drawable/ic_launcher"    
        />
              <!-- 可以包裹任意多的view 和layout -->
        </com.cry.loopviews.LoopView>
##问题反馈和联系方式
qq:347284221<br />
邮箱:zhuxiujia@qq.com<br />
##原理示意图
![ABC](hao.png)