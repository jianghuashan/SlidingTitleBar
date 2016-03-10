
SlidingTitleBar
===================================
  一款用来滑动的导航条组件，主要就是用于配合ViewPager实现滑动的导航条，以容纳无限多的Tab\<h1\><br />
 ![](https://github.com/heavenxue/SlidingTitleBar/raw/master/docs/截图.png)

Features
-----------------------------------
  有4个属性控制这个组件，分别为<br />
  ![属性](https://github.com/heavenxue/SlidingTitleBar/raw/master/docs/attr.png "属性")

      allowWidthFull 是否充满屏幕
      disableViewPager 是否禁用viewPager
      disableTensileSlidingBlock 是否禁用拉伸滑动块
      slidingBlock 滑动块
  
### 使用
  在eclipse和AndroidStudion中都可以使用<br />
  1、引用
      compile 'me.xiaopan:sketch:2.0.0'

  2、在布局中引用slidingtitlebarlib
     ![](https://github.com/heavenxue/SlidingTitleBar/raw/master/docs/1.png)

   3、设置viewpager
      ViewPager moreViewPager = (ViewPager) findViewById(R.id.viewPager);
      moreViewPager.setAdapter(...);
      pagerSlidingTabStrip.setViewPager(moreViewPager);


### 注意!!!
    在调用setViewPager(ViewPager)方法之前要先设置ViewPager的Adapter
        
