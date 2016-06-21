             Android Studio方法注释模板
##交流QQ群：221537774  邮箱：2402091500@qq.com   qq2402091500@gmail.com
步骤

* 1 File->Setting->Editor->Live Templates

* 2点击+，创建一个Template Group

![](https://github.com/2402091500/android_doc/blob/master/2.png)

* 3 填个你要的group名，我的叫custom

![](https://github.com/2402091500/android_doc/blob/master/3.png)

* 4 选中你刚刚创建的group，创建Live Template

![](https://github.com/2402091500/android_doc/blob/master/4.png)

* 5 填写Abbreviation,我这里填的是cmt,也即你这个注释的快捷方式，你敲cmt加回车，模板就出来了

* 6 Template text是注释的模板，具体你模板要怎么写都可以，我的模板如下

![](https://github.com/2402091500/android_doc/blob/master/6.png)

* 7 要设置你这个cmt快捷键在哪里生效，我的选择是在声明的时候生效，也即你在方法名上打cmt加回车就可以了




* 8 注意到，我的Template text有定义了三个变量 desc,date,time,后面两个我要生成日期和时间，所以我们要编辑这两个变量
![](https://github.com/2402091500/android_doc/blob/master/7.png)


* 9 点击Edit variables，在弹窗里分别为date 和time就是设置对应的方法，date()这个方法会生成日期，time()这个方法会生成时间
![](https://github.com/2402091500/android_doc/blob/master/8.png)


* 10 点击Apply一切完成。现在，你只要在方法名上敲上cmt回车，就会自动生成注释模板了，效果如下，时间是自动生成的

![](https://github.com/2402091500/android_doc/blob/master/9.png)