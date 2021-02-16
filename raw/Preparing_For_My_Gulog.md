<meta http-equiv="Content-Type" content="text/html; charset=utf-8">

# Preparing For My Blog

  I made a lot of preparation for my Blog today.
  But it's quite a difficult task ...
  放弃用英文写作了，我用中文写吧。
  整理了一下
  以上是历史版本，实际上，为什么放弃了Jekyll呢？只是使用ruby的gem时，配置有一些问题导致管理权限不清，gem的时候总是失败，然后Jekyll也运行不起来。
  于是我想，为何不直接自己做自己的网页呢？我曾经有过在小学的时候用MS Office Word绘制网页的经历，现在绘制一些新的网页放自己的博客，应该也不是什么难事。
  于是一场艰难的长征开始了。
  那时候的我其实已经把一台完全是 xfce4 + Ubuntu 的机器当作日常使用的机器了，所以第一个问题就是，我没有Front Page之类的专用软件。
  那么走老路吧，继续用文字处理程序画网页，我先是使用了LibreOffice绘制我的第一个页面，index.html——丑。
  然后我用纯文本编辑器打开了html文档，查看了一下，发现里面全都是我看不懂的标签，而且我当时甚至不知道这些标签的层叠关系，加上Office给头部加了很多可有可无的东西，我彻底懵逼了，我仅仅找到了我当作标题的那一行东西而已。
  那怎么办呢，我只有硬着头皮做下去了。
  主页太丑？那就不管了，继续丑着吧。
  markdown文本转不成html？那就继续markdown保存下去。
  我试着运用BlueFish编辑器，但是提升的便利有限。
  咕了很久之后的一天，我去掉了html文档中的很多我一眼看过去就知道明显没用的东西，比如不合现有规范但是又编辑器自动生成的&lt;font&gt;标签，还有像是文件创建编辑日期之类的东西（虽然现在想起来觉得也许有必要留下来），以及搜索如何添加分割线，如何把分割线弄得好看一点，如何设置margin，如何设置缩进，如何使用多个&lt;p&gt;标签分段，而不是在&lt;p&gt;中使用&lt;br&gt;这种不规范的方式来分段，以及后来的，硬着头皮引用css文件，然后我在style标签中的经验让我在修改css时异常顺手；
  然后咕了很久之后的一天，我向朋友吐槽说，虽然markdown在Chrome中可以浏览，但是完全就是乱码，为什么我在md开头的&lt;meta&gt;标签不起作用？
  我的朋友告诉我，&lt;meta&gt;标签需要放在&lt;head&gt;标签里面才能起作用。于是我发现了有&lt;head&gt;标签和&lt;body&gt;两个标签，那么显然功能也不一样。但是已经清楚这个规律了，我于是终于开始动手把原先的md文档转为html文档。
  然后在处理&lt;code&gt;的时候我发现了一个不应该有的text-indent，但是怎么修改都有问题。
  于是我发现了&lt;div&gt;标签，这个标签配合style真是好用。
  问题可能就在于每次手动指定style有些麻烦，另外就是一个一个md文档地改非常麻烦了。
  我已经想到了一个绝妙的办法来做，但是地方不太够我写不下了（
