![image-20200918232711404](homework.assets/image-20200918232711404.png)

![image-20200918232726706](homework.assets/image-20200918232726706.png)

* 启动活动

  ```
  2020-09-18 23:04:27.331 6614-6614/com.yxj.lifecycle D/myTag: onCreate
  2020-09-18 23:04:27.373 6614-6614/com.yxj.lifecycle D/myTag: onStart
  2020-09-18 23:04:27.374 6614-6614/com.yxj.lifecycle D/myTag: onResume
  
  ```

* 杀死活动

```
2020-09-18 23:04:57.256 6614-6614/com.yxj.lifecycle D/myTag: onPause
2020-09-18 23:04:58.315 6614-6614/com.yxj.lifecycle D/myTag: onStop
2020-09-18 23:04:58.317 6614-6614/com.yxj.lifecycle D/myTag: onDestroy

```

* 停止活动

```
2020-09-18 23:00:35.916 6614-6614/com.yxj.lifecycle D/myTag: onPause
2020-09-18 23:00:36.877 6614-6614/com.yxj.lifecycle D/myTag: onStop

```

* 重启活动

```
2020-09-18 23:05:43.309 6614-6614/com.yxj.lifecycle D/myTag: onRestart
2020-09-18 23:05:43.314 6614-6614/com.yxj.lifecycle D/myTag: onStart
2020-09-18 23:05:43.315 6614-6614/com.yxj.lifecycle D/myTag: onResume

```

