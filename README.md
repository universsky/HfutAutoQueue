HfutAutoQueue
=============

合肥工业大学财务处报账自动排队

## 使用说明
输入用户名密码后点击排队，会自动计时并到8点后开始取号。在程序所在目录会生成print文件夹，里面包含取号的打印页面。请保持系统时间的正确。

如有bug请[反馈](http://bbs.hfut.edu.cn/forum/viewthread.php?tid=928510)

## 隐私说明

本软件不会记录任何用户信息，用户的账户和密码仅仅会<b>明文</b>提交至财务处网站。

鉴于可以通过软件直接读取本程序密码框中的密码，所以请不要在公共电脑上使用，以免发生密码泄露。

## 更新记录

#### 20130719-v0.3

添加了保存打印页面设置，并修正了一些bug

#### 2013223-v0.2

初步修正取号后网页无取号结果显示问题

#### 20130124-v0.11

修正死循环的安全隐患，每次最多请求5000次（80多分钟）

#### 20130124-v0.1

发布第一个版本

## BUG

<del>取到号后有时候网页页面上不会显示取到的号，但是系统提示已经取过号，请尝试在登录系统后再访问http://210.45.241.169/baobiao/Queue/QueuePrint.aspx</del>
解决方法是直接将取号后得到的打印页面保存下来，目前还未再次发现这个问题
