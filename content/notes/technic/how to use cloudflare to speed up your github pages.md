---
title: "how to use cloudflare to speed up your github pages"
tags:
- github
- cloudflare
- namesilo
- 2022
- 四月
---



> 如何用cloudflare加速你的github pages

## 背景

许多人开始用github pages服务开放免费的blog功能。
但是github pages在国内的访问速度非常缓慢。
于是可以用cloudflare加速域名解析。

## 操作

### 申请github账号并开通pages服务

略，改日。

### 申请域名

可以在[namesilo](https://www.namesilo.com/login)上申请域名。过程非常简单和便宜。然后在申请好的域名的位置，配置第三方DNS解析服务商的地址。**是的，没错，我们不用namesilo自己的，因为不够快。**

### 换掉默认的NameServer

首先，你申请了域名以后，namesilo会提供给你他们自己的nameserver地址。你看不到，只有你开始给你申请的域名进行绑定具体的地址的时候，这个nameserver才会进入你关注的视线。不过这都不重要，没有影响。

好，现在要做的，你要先开一个cloudflare的账号，自己去申请，免费的。然后人家cloudflare就会提供一个更牛逼的nameserver给你，免费的。那么我们要做的就是将这个更牛逼的nameserver替换掉当你namesilo（你申请域名的那个网站）申请域名的时候，这个网站自带的nameserver服务器。方法非常简单，你申请好的域名会在 `manage my domain`最上方的菜单里。点击，你就看到你申请的地址在下面的表格里中。然后，先选中这个域名，在上面一行巨丑的图标中有一个叫`change namesever`的。具体在这里

![更换掉默认的nameserver](notes/images/Pasted%20image%2020220413212433.png)

点他！

然后你就会明晃晃的看到，两个空的地方给你填写，如果你填写过，或者它默认的也会现在里面，还是灰色的，似乎是不可以该的样子。其实是可以改的，你写上cloudflare网站提供给你的更好的那个nameserver，然后点提交。完毕！

![如何更改namesilo中的nameserver](notes/images/Pasted%20image%2020220413213301.png)
