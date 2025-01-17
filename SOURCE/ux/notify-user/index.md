> 编写:[fastcome1985](https://github.com/fastcome1985)

> 校对:

# 通知提示用户

* Notification是一种在你APP常规UI外展示、用来指示某个事件发生的用户交互元素。用户可以在使用其它apps时查看notification，并在方便的时候做出回应。

*  [Notification设计指导](developer.android.com/design/patterns/notifications.html)向你展示如何设计实用的notifications以及何时使用它们。这节课将会教你实现大多数常用的notification设计。

* 完整的Demo示例：[NotifyUser.zip](developer.android.com/shareables/training/NotifyUser.zip)

## Lessons  

* [建立一个Notification](build-notification.html)
  学习如何创建一个notification [Builder](developer.android.com/reference/android/support/v4/app/NotificationCompat.Builder.html)，设置必要的特征，以及发布notification。
   
* [当启动Activity时保留导航](nav.html)
   学习如何为一个从notification启动的[Activity](http://developer.android.com/intl/zh-cn/reference/android/app/Activity.html)执行合适的导航。

* [更新notifications](update-notification.html)
  学习如何更新与移除notifications


* [使用BigView风格](expand-notification.html)
   学习用扩展的notification创建一个BigView，同时仍然向后保持兼容。

* [在notification中展示进度](progess-notification.html)
   学习在notification中显示某个操作的进度，既可以用于那些你可以估算已经完成多少（确定进度，determinate）的操作，也可以用于那些你无法知道完成了多少（不确定进度，indefinite ）的操作