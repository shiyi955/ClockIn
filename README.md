## 疫情无小事,防控靠大家。真的有什么状况即时上报

## 食用方法

- 1.首先保证你有一个GitHub账号

- 2.fork一份到自己仓库

- 3.打开settings，找到secrets，新建secret
[secret图片说明链接](https://s3.ax1x.com/2021/01/26/svlE80.png)

- 4.DEVICETOKEN获取方法可关注微信公众号“听说名字越长越容易通过WX审核“通过历史文章查看。

- 5.sever酱使用参见[官网](http://sc.ftqq.com/3.version)。

- 6.开启 Actions 并触发每日自动执行
Github Actions 默认处于关闭状态，大家请手动开启 Actions ，执行一次工作流，验证是否可以正常工作。
[图片](https://s3.ax1x.com/2021/01/27/sxz1IJ.png)

- 7.如果需要修改每日任务执行的时间，请修改 `.github/workflows/autoClockIn.yml`，在第 8 行左右位置找到下如下配置。

```yml
  schedule:
    - cron: '10 21 * * *'
    # cron表达式，Actions时区是国际时间，国际时间21点的时候，国内时间是5点。
    # 示例： 每天早上5点10分执行 '10 21 * * *'
```

- 8.经纬度可以进入[高德地图API](https://developer.amap.com/api/webservice/guide/api/georegeo#geo)下翻至服务示例，输入你的定位地点后于返回的数据中获取
[点我看图](https://s3.ax1x.com/2021/01/28/y9Ml5Q.png)

- 9.误操作造成的后果自负哦，谨慎使用。

### Q群：717104836
