# 事件经过

## 后门删除用户本地存储内容

- 原post by `crimethinking`

```
So Huawei put a backdoor into their own Android?

Just read a post from a local (Hong Kong) forum saying that a China user using a Huawei phone got his image downloaded from Twitter automatically deleted by the OS.

Doesn't it means that Huawei got backdoor on the user's phone? Probably they have to verify image/checksum with their own (China) server's to do it. Probably why US Government ban their products.

A link from a Taiwan media is here https://tw.appledaily.com/new/realtime/20190119/1503813/

EDIT: Credit to @crimethinking , proof is here https://streamja.com/1n96

EDIT 2: Please help me spreading this out so we can ask Twitter what is happening https://twitter.com/ckmichael8/status/1087298412842635265?s=19

EDIT 3: Remove possibly misleading statement about backdoor

EDIT 4: Report from TechRadar https://www.techradar.com/news/huawei-promises-it-isnt-deleting-photos-downloaded-from-twitter

So we are all wrong, Twitter is not deleting it, Huawei is not deleting as well, Twitter moves it instead.
```

- [录屏演示](https://streamja.com/1n96)


## 敏感信息回传

- 原post

```
无聊翻华为平板的系统目录:
/system/etc/hiview下存有日志系统的XML配置
定期会回传日志，信息包括但不限于连接到Wi-Fi的BSSID，周边基站信息，所安装的App，App的运行时间段，设备IMEI或MEID等。
不同国家使用不同报告配置，美国和中国用户有专门的服务器。
检测到国家是俄罗斯，朝鲜等时不回传数据。
```

- 附图 XML 日志配置文件

![](https://pbs.twimg.com/media/D7rsYRHU8AMXBmn?format=png&name=small)
![](https://pbs.twimg.com/media/D7rsYRGU8AAyKsc?format=png&name=small)
![](https://pbs.twimg.com/media/D7rsYRGUwAEOFgO?format=png&name=small)
![](https://pbs.twimg.com/media/D7rsYRHV4AAbEy6?format=png&name=small)
![](https://pbs.twimg.com/media/D7rtJ_aUwAELdym?format=png&name=small)

# 参考资料

> [[Vendor Backdoor?] Huawei deletes images downloaded from Twitter](https://www.reddit.com/r/Android/comments/ai5tfe/vendor_backdoor_huawei_deletes_images_downloaded/)

> [华为手机回传中国包括但不限于连接到Wi-Fi的BSSID，周边基站等信息](https://twitter.com/ZhynLn/status/1133478163088941056)


华为手机恶意监听用户信息, 删除用户本地内容
